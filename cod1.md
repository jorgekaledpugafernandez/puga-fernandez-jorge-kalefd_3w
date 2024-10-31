print("puga fernnadez jorge kaled-3w")
print(" ")
# Definimos la lista de asignaturas
asignaturas = ["Matemáticas", "leoye", "escosistema", "ingles",]

# Creamos una lista para las asignaturas aprobadas
asignaturas_repetir = []

# Pedimos la nota para cada asignatura
for asignatura in asignaturas:
    nota = float(input(f"Ingrese la nota para {asignatura}: "))
    if nota < 6:  # Si la nota es menor que 6, se añade a las asignaturas a repetir
        asignaturas_repetir.append(asignatura)

# Mostramos las asignaturas que el usuario tiene que repetir
if asignaturas_repetir:
    print("Asignaturas que tienes que repetir:")
    for asignatura in asignaturas_repetir:
        print(asignatura)
else:
    print("¡Felicidades! Has aprobado todas las asignaturas.")

   ![image](https://github.com/user-attachments/assets/4a13dbfc-a0dc-46c4-9261-2bb793ca7a89)


