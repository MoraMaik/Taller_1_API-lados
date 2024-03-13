# Taller_1_API-lados
-------------

### Desarrollo del Taller 1 en la asignatura de Programación de Computadores - UNAL
Coordial saludo, nuestro grupo de Programacion se llama API-lados, a continuacion presentamos nuestro logo hecho con IA.

[![Whats-App-Image-2024-02-28-at-9-47-06-AM.jpg](https://i.postimg.cc/W4qjTqyc/Whats-App-Image-2024-02-28-at-9-47-06-AM.jpg)](https://postimg.cc/rdT79scf)

### Integrantes:
+ Michael Kaleth Mora Mejia (1086774311)
+ Angie Carolina Salazar Lara (1052837889)
+ Alejandro	Urrego Valencia (1000364014)

-------------

1. Como primer punto del taller se encomendo realizar un [Quiz](http://https://pythonspot.com/python-tests-quizes/ "Quiz")
 Python Beginner Quiz (20 preguntas) y adjuntar una imagen con mas del 90% de acierto. En nuestro caso logramos obtener un

-------------
2. Como segundo punto se nos asigno realizar un programa que lea tres números reales y determine cuál es el mayor.

Este código utiliza la función input() para leer los números desde la entrada estándar, luego los convierte a tipo float para permitir números reales. Después, mediante una serie de declaraciones if, elif y else, compara los números entre sí para determinar cuál es el mayor y finalmente lo imprime usando print().
```python
    # Leer tres números reales
    num1 = float(input("Introduce el primer número: "))
    num2 = float(input("Introduce el segundo número: "))
    num3 = float(input("Introduce el tercer número: "))
    
    # Determinar y mostrar el mayor de los tres números
    if num1 >= num2 and num1 >= num3:
        print("El mayor número es:", num1)
    elif num2 >= num1 and num2 >= num3:
        print("El mayor número es:", num2)
    else:
        print("El mayor número es:", num3)
    
    # Código finalizado
```
Aqui esta el diagrama de flujo.

[![PUNTO-2-2024-03-12-203040.png](https://i.postimg.cc/yNNfxDcv/PUNTO-2-2024-03-12-203040.png)](https://postimg.cc/G4ZPShMy)

El programa, al ser par, se encuentra en el repositorio con terminacion .py

-------------
3. Para el tercer punto se encomendo realizar un programa que lea un número enteros y determine si es par o impar.

Este código comienza con la lectura de un número entero utilizando input(), convirtiéndolo a entero con int() debido a que input() lee los datos como cadena de texto. Luego, utiliza una declaración if para evaluar si el residuo de dividir el número entre 2 es igual a 0. Si es así, imprime que el número es par; de lo contrario, imprime que es impar.
```python
# Leer un número entero
numero = int(input("Introduce un número entero: "))

# Determinar si el número es par o impar
if numero % 2 == 0:
    print("El número es par.")
else:
    print("El número es impar.")

# Código finalizado

```
Su diagrama de flujo.

[![PUNTO-3.png](https://i.postimg.cc/VLdLqg18/PUNTO-3.png)](https://postimg.cc/9rHhVGr8)

El programa se encuentra en el repositorio y al ser impar esta en un mismo archivo con terminacion .ipynb

-------------
4. En este punto se solicita realizar un programa que lea dos números reales y determine si el primero es múltiplo del segundo.

Este código inicia solicitando al usuario que ingrese dos números, que son almacenados en las variables num1 y num2 después de convertirlos a tipo float para permitir números reales. Luego, antes de realizar la operación de módulo, se verifica que el segundo número no sea cero para evitar un error de división por cero. Si num2 no es cero, se procede a calcular el módulo de num1 entre num2. Si el resultado es cero, se imprime que num1 es múltiplo de num2; de lo contrario, se indica que no lo es.

```python
# Leer dos números reales
num1 = float(input("Introduce el primer número real: "))
num2 = float(input("Introduce el segundo número real: "))

# Verificar si num1 es múltiplo de num2
if num2 == 0:
    print("No se puede dividir por cero.")
elif num1 % num2 == 0:
    print(f"El número {num1} es múltiplo de {num2}.")
else:
    print(f"El número {num1} no es múltiplo de {num2}.")

# Código finalizado

```
Su diagrama de flujo.

[![punto-4-2024-03-13-040503.png](https://i.postimg.cc/k4vFy9QB/punto-4-2024-03-13-040503.png)](https://postimg.cc/sQ1hVk0r)

El programa, al ser par, se encuentra en el repositorio con terminacion .py

-------------


