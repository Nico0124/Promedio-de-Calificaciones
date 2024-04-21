# Promedio-de-Calificaciones
# Este programa permite calcular las calificaciones de un estudiante, este programa solicita las calificaciones que ha sacado el estudiante y calculará el promedio general 

Notas = []
while True: 
    Nota = input("ingresa una calificación (o salir para terminar): ") 
    if Nota.lower()=='salir': 
        break
    else: 
        Notas.append(float(Nota))

Promedio = sum (Notas)/len(Notas)
print ("El promedio de notas es: ", Promedio)


