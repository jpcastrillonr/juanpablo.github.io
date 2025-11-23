# Reto 1: Simulación básica de una tortuga con texto

print("Simulación de tortuga")
distancia = int(input("¿Cuántas unidades debe avanzar la tortuga? "))

print("La tortuga avanza:")
print("→" * distancia)

# Reto 2: Tortuga bajando

print("Simulación de tortuga bajando")
pasos = int(input("¿Cuántos pasos hacia abajo debe dar la tortuga? "))

print("La tortuga baja:")
for _ in range(pasos):
    print("↓")

# Reto 3: Tortuga que avanza, gira y vuelve a avanzar

print("Simulación de movimiento con giro")

a1 = int(input("¿Cuántos pasos avanza primero la tortuga? "))
giro = int(input("¿Cuántos grados gira la tortuga (solo 90 derecha)? "))
a2 = int(input("¿Cuántos pasos avanza después del giro? "))

print("\nTortuga dibujando:")

# Primer tramo
print("→" * a1)

# Giro de 90° a la derecha
if giro == 90:
    for _ in range(a2):
        print("↓")
else:
    print("Giro no soportado.")

# Reto 4: Funciones de movimiento textual

def adelante(n):
    print("→" * n)

def abajo(n):
    for _ in range(n):
        print("↓")

# Ejemplo:
adelante(5)
abajo(3)

# Reto 5: Tortuga bajando escalones

posicion_x = 0  # Rastrea la posición horizontal acumulada

def adelante(n):
    global posicion_x
    print("→" * n)
    posicion_x += n  # Acumula posición

def abajo(n):
    global posicion_x
    for _ in range(n):
        print(" " * posicion_x + "↓")  # Espacios para mantener el alineamiento

# Ejemplo: 3 escalones
adelante(5)
abajo(2)

adelante(5)
abajo(2)

adelante(5)
abajo(2)

