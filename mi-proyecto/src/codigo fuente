# Programa para calcular el promedio de una lista de números

print("Bienvenido al programa de cálculo de promedios.")
print("Ingresa números uno por uno. Escribe 'salir' para terminar.")

# Lista para almacenar los números
numeros = []

while True:
    entrada = input("Ingresa un número (o escribe 'salir'): ")
    
    if entrada.lower() == 'salir':
        break  # Salir del bucle si el usuario escribe 'salir'
    
    try:
        # Convertir la entrada a número
        numero = float(entrada)
        numeros.append(numero)
    except ValueError:
        print("Por favor, ingresa un número válido.")
        continue

# Verificar si hay números en la lista antes de calcular el promedio
if len(numeros) > 0:
    promedio = sum(numeros) / len(numeros)
    print(f"El promedio de los números ingresados es: {promedio:.2f}")
else:
    print("No ingresaste ningún número.")

import requests

# Configuración
GITHUB_API_URL = "https://api.github.com/user/repos"
ACCESS_TOKEN = "tu_token_de_acceso_personal"  # Reemplaza con tu token
REPO_NAME = "mi-nuevo-repositorio"  # Nombre del repositorio
REPO_DESCRIPTION = "Este es un repositorio creado con la API de GitHub"  # Descripción
PRIVATE = False  # True para un repositorio privado, False para público

# Encabezados de la solicitud
headers = {
    "Authorization": f"token {ACCESS_TOKEN}",
    "Accept": "application/vnd.github.v3+json"
}

# Datos del repositorio
data = {
    "name": REPO_NAME,
    "description": REPO_DESCRIPTION,
    "private": PRIVATE,
    "auto_init": True  # Inicializa el repositorio con un README.md
}

# Crear el repositorio
response = requests.post(GITHUB_API_URL, json=data, headers=headers)

# Verificar la respuesta
if response.status_code == 201:
    print(f"Repositorio '{REPO_NAME}' creado exitosamente en GitHub.")
    print(f"URL del repositorio: {response.json()['html_url']}")
else:
    print(f"Error al crear el repositorio: {response.status_code}")
    print(response.json())