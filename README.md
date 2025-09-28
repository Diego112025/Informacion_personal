# Informacion_personal
# 1. diccionario con información ficticia
informacion_personal = {
    "nombre": "Juan Cardenas",
    "edad": 30,
    "ciudad": "Ecuador",
    "profesion": "Ingeniero"
}

# 2. Acceder al valor de la clave "ciudad" y modificarla
informacion_personal["ciudad"] = "Puyo"

# 3. Agregar una nueva clave-valor para "telefono"
informacion_personal["telefono"] = "984984851"

# 4. Verificar si la clave "telefono" existe, y si no, agregarla
if "telefono" not in informacion_personal:
    informacion_personal["telefono"] = "984984851"

# 5. Eliminar la clave "edad"
del informacion_personal["edad"]

# 6. Imprimir el diccionario final
print(informacion_personal)
