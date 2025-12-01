# Tarea 2 - Ejercicios Unidad 1 
# Linda Natalia Sanchez 

# Reto 1: Simulación básica de la tortuga con texto

print("Simulación de tortuga")
pasos = int(input("¿Cuántos pasos quieres que avance la tortuga? "))

print("Tortuga avanzando...")
print("→" * pasos)


# Reto 2: Tortuga bajando

print("Simulación: Tortuga bajando")
pasos = int(input("¿Cuántos pasos hacia abajo? "))

for _ in range(pasos):
    print("↓")


# Reto 3: Avanzar y girar para dibujar una L

print("Simulación: L con texto")

h = int(input("¿Cuántos pasos hacia adelante? "))
v = int(input("¿Cuántos pasos hacia abajo después de girar? "))

# Avance horizontal
print("→" * h)

# Movimiento vertical
for _ in range(v):
    print("↓")

 # Reto 4: Encapsular movimientos

def adelante(n):
    print("→" * n)

def abajo(n):
    for _ in range(n):
        print("↓")

print("Simulación con funciones")

adelante(5)
abajo(3)

# Reto 5: La tortuga baja escalones

posicion = 0  # Guarda la posición horizontal acumulada

def adelante(n):
    global posicion
    print("→" * n)
    posicion += n

def abajo(n):
    global posicion
    for _ in range(n):
        print(" " * posicion + "↓")

# Ejemplo de escalera:

# Escalón 1
adelante(5)
abajo(2)

# Escalón 2
adelante(5)
abajo(2)

# Escalón 3
adelante(5)
abajo(2)




for _ in range(v):
    print("↓")
