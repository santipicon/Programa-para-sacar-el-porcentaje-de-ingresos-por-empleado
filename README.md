﻿# Programa-para-sacar-el-porcentaje-de-ingresos-por-empleado

texto = input("Introduce tu texto: ")
letras =[]
texto = texto.lower()

letras.append(input("Introduce tu primera letra: ").lower())
letras.append(input("Introduce tu segunda letra: ").lower())
letras.append(input("Introduce tu tercera letra: ").lower())

print("Cantidad de letras: ")

cantidad_letras1 = texto.count(letras[0])
cantidad_letras2 = texto.count(letras[1])
cantidad_letras3 = texto.count(letras[2])

print(f"Hemos encontrado la letra {letras[0]} repetida {cantidad_letras1}")
print(f"Hemos encontrado la letra {letras[1]} repetida {cantidad_letras2}")
print(f"Hemos encontrado la letra {letras[2]} repetida {cantidad_letras3}")

print("Cantidad de palabras")
palabras = texto.split()
print(f"Hemos encontrado {len(palabras)} palabras en tu texto")

print("Letras de inicio y de fin")
letras_inicio = texto[0]
letras_fin = texto[-1]
print(f"La primera letra es: {letras_inicio} y la ultima letra es: {letras_fin}")

print("Invirtiendo el orden quedaria de esta manera")
invertido = texto[::-1]
print(invertido)

print("Buscando la palabra Python")

buscar_python = 'python' in texto
dic= {True: 'si', False: 'no'}
print(f"La palabra Python: {buscar_python}")
