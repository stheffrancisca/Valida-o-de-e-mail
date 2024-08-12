# Valida-o-de-e-mail
Validação de e-mail

### Criando um programa que dado o e-mail de um usuário, valide se aquele e-mail é válido com as seguintes regras:
    - Tem que ter .com ou .gov
    - Tem que ter @
    - Tem que ter mais de 5 caracteres
    - Não pode ter espaço

    email = input("Insira o e-mail aqui:")

if ".com" in email or ".gov" in email:
    if "@" in email and len(email) > 5 and " " not in email:
        print("Email Válido")
    else:
        print("Email Inválido")
else:
        print("Email Inválido")
