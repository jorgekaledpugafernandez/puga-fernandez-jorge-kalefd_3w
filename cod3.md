print("puga fernnadez jorge kaled")
print(" ")
# Lista de asignaturas
asignaturas = ['Matemáticas', 'leoye', 'escosistema', 'ingles']

# Diccionario para almacenar las notas
notas = {}

# Preguntar la nota por cada asignatura
for asignatura in asignaturas:
    nota = input(f"¿Qué nota has sacado en {asignatura}? ")
    notas[asignatura] = nota  # Almacenar la nota en el diccionario

# Mostrar las notas
print("\nNotas obtenidas:")
for asignatura, nota in notas.items():
    print(f"En {asignatura} has sacado {nota}.")

![image](https://github.com/user-attachments/assets/9af03635-575b-474c-a9e1-b3ac1c2ed9ed)
