## 📚 Temas Vistos en Clase: El ABC de la Programación

La programación, en su esencia, es el arte de darle **instrucciones** precisas a una computadora para que resuelva un problema. Aquí están algunos de los conceptos iniciales más importantes que hemos explorado:

### 1. ¿Qué es un Programa?

Un **programa** es un conjunto de **instrucciones** lógicas y secuenciales que una computadora ejecuta para realizar una tarea específica. Piensa en él como una receta: debe ser claro, seguir un orden, y usar ingredientes (datos) específicos.

### 2. Variables y Tipos de Datos

Una **variable** es como una caja con etiqueta que usamos para almacenar información en la memoria de la computadora. El **tipo de dato** define qué clase de información puede guardar esa caja.

* **Enteros (`int`):** Números completos (ej. 10, -5).
* **Flotantes (`float`):** Números con decimales (ej. 3.14, 0.5).
* **Cadenas de texto (`str`):** Secuencias de caracteres (ej. "Hola mundo").
* **Booleanos (`bool`):** Representan valores de verdad (True o False).

### 3. Estructuras de Control (Ej. Condicionales)

Las **estructuras de control** permiten que el flujo de ejecución de un programa cambie en función de ciertas condiciones. La más básica es el **condicional `if/else`**, que le permite al programa tomar decisiones.

---

## 🐍 Ejemplo de Código en Python

El siguiente ejemplo ilustra el uso de **variables** y una simple **estructura condicional** para determinar si un número es positivo.

```python
# Definición de una variable de tipo entero
numero = 15

# Uso de una estructura de control condicional (if/else)
if numero > 0:
    # Si la condición es verdadera
    resultado = "El número es positivo."
elif numero == 0:
    # Si la condición anterior fue falsa y esta es verdadera
    resultado = "El número es cero."
else:
    # Si ninguna de las condiciones anteriores fue verdadera
    resultado = "El número es negativo."

# Imprimir el resultado (Salida por consola)
print(f"Valor asignado: {numero}")
print(resultado)
