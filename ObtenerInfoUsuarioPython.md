# Obtener la dirección de correo electrónico del usuario.
email = input("What is your email address?: ").strip()

# Cortar el nombre de usuario.
user_name = email[:email.index("@")]

# Cortar el nombre de dominio.
domain_name = email[email.index("@")+1:]

# Format 
output = "Hola '{}' estoy observando que estás utilizando un dominio personalizado de '{}'".format(user_name,domain_name)

print(output)
