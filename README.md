# tipo de datos
los tipos de datos son esenciales para la programación porque permiten al programador organizar la información de manera eficiente y evitar errores al trabajar con datos de diferentes tipos.

# ejemplos

Entero	                int	          6, 5, -2, 675
Cadena de caracteres	str	          "Pepe", "Juan", "Coche"
Booleano	            bool	      True, False (None)
Listas	                list	      (1, 42, 3j, "Hello")

# variables
una variable es un contenedor que se utiliza para almacenar información que puede cambiar durante la ejecución de un programa. Las variables tienen un nombre único que se utiliza para hacer referencia a ellas y un tipo de dato que especifica qué tipo de información pueden contener.

```python
numeros:int=[1,2,3,4,5,6,7,8,9]
caracteres:str="angielo"
```

# Controles de flujo
El control de flujo en Python se refiere a la capacidad de un programa para tomar decisiones y ejecutar diferentes acciones según ciertas condiciones. Es como las carreteras y señales de tráfico que guían el flujo de ejecución de un programa.

if: es utilizado para crear condiciones y tomar decisiones.

**ejemplo**

```Python

edad = 18
if edad >= 18:
   print("Eres mayor de edad.")
```
for: repetir sobre una secuencia (como una lista o cadena de texto).Ejemplo

```Python
num = [2, 25, 32, 12]
for n in num:
    print(n)
# muestra por consola
2
25
32
12
```
# funciones
Las funciones en Python son bloques de código reutilizables que realizan una tarea específica. Se definen con la palabra clave def, seguida del nombre de la función y paréntesis, y se usan para organizar el código, mejorar la legibilidad y evitar la repetición. Ejemplo

```python 
def saludar():
       print("¡Hola! Bienvenido.")
   
   # Llamar a la función
   saludar()
```