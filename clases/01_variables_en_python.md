# Variables en Python

## ¿Qué es una variable?

Una variable es un nombre que se utiliza para hacer referencia a un valor. Las variables se utilizan para almacenar valores en la memoria de un ordenador. Los valores pueden ser números, cadenas de texto, listas, etc.

Las variables, por norma general, se escriben en minúsculas y se separan con guiones bajos, este tipo de notación se conoce como snake_case. Por ejemplo:

```python
# recomendado para python
numero_de_estudiantes = 10
```

Otra notación común es la camelCase, en la que la primera letra de cada palabra se escribe en mayúscula, excepto la primera palabra. Por ejemplo:

```python
# no recomendado para python
numeroDeEstudiantes = 10
```

## ¿Cómo se crea una variable?

Para crear una variable en Python, se utiliza el operador de asignación `=`. El operador de asignación asigna un valor a una variable. Por ejemplo:

```python
x = 1
```

En este ejemplo, se crea una variable llamada `x` y se le asigna el valor `1`.

El nombre de una variable puede ser cualquier combinación de letras, números y guiones bajos, pero no puede comenzar con un número. Por ejemplo:

```python
# Correcto
x = 1
y32 = 2
_z = 3

# Incorrecto
1y = 2
```

El uso de nombres de variables descriptivos ayuda a que el código sea más fácil de leer y entender. Por ejemplo:

```python
# Correcto
numero_de_estudiantes = 10

# Incorrecto
n = 10
```

Los nombres de variables son sensibles a las mayúsculas y minúsculas, lo que significa que `saludo`, `Saludo` y `sAlUdO` son variables diferentes. Por ejemplo:

```python
saludo = 'Hola soy un saludo'
Saludo = 'Hola soy otro saludo'
sAlUdO = 'Hola soy otro saludo más'

print(saludo) # imprime por consola: Hola soy un saludo
print(Saludo) # imprime por consola: Hola soy otro saludo
print(sAlUdO) # imprime por consola: Hola soy otro saludo más
```

## Tipos de datos primitivos

Los tipos de datos son los tipos de valores que se pueden almacenar en una variable. Los tipos de datos más comunes son:

- **Números Enteros (int):** Los números son valores numéricos, como `1`, `2`, `3`, etc.

- **Números de Punto Flotante (float):** Los números de punto flotante son valores numéricos con decimales, como `1.0`, `2.0`, `3.0`, etc.

- **Números Complejos (complex):** Los números complejos son valores numéricos complejos, como `1 + 2j`, `2 + 3j`, etc.

- **Cadenas de Texto (str):** Las cadenas de texto son valores de texto, como `'Hola'`, `'Mundo'`, etc.

- **Booleanos (bool):** Los booleanos son valores lógicos, como `True` y `False`.

En python es posible verificar el tipo de dato de una variable utilizando la función `type()`. Por ejemplo:

```python
x = 1
y = 2.0
z = 'Hola Mundo'
w = True
v = 5 + 6j

print(type(x)) # imprime por consola: <class 'int'>
print(type(y)) # imprime por consola: <class 'float'>
print(type(z)) # imprime por consola: <class 'str'>
print(type(w)) # imprime por consola: <class 'bool'>
print(type(v)) # imprime por consola: <class 'complex'>
```

## Tipos de datos compuestos

Los tipos de datos compuestos son tipos de datos que contienen otros tipos de datos. Los tipos de datos compuestos más comunes son:

- **Listas (list):** Las listas son colecciones ordenadas de valores, como `[1, 2, 3]`, `['Hola', 'Mundo']`, etc.

- **Tuplas (tuple):** Las tuplas son colecciones ordenadas de valores inmutables, como `(1, 2, 3)`, `('Hola', 'Mundo')`, etc.

- **Diccionarios (dict):** Los diccionarios son colecciones no ordenadas de pares clave-valor, como `{'nombre': 'Juan', 'edad': 20}`, `{'nombre': 'María', 'edad': 30}`, etc.

## Operadores aritméticos

Los operadores aritméticos se utilizan para realizar operaciones aritméticas en los valores. Los operadores aritméticos más comunes son:

- **Suma (+):** La suma se utiliza para sumar dos valores, como `1 + 2`, `2 + 3`, etc.

- **Resta (-):** La resta se utiliza para restar dos valores, como `1 - 2`, `2 - 3`, etc.

- **Multiplicación (*):** La multiplicación se utiliza para multiplicar dos valores, como `1 * 2`, `2 * 3`, etc.

- **División (/):** La división se utiliza para dividir dos valores, como `1 / 2`, `2 / 3`, etc.

- **División entera (//):** La división entera se utiliza para dividir dos valores y obtener el resultado entero, como `1 // 2`, `2 // 3`, etc.

- **Módulo (%):** El módulo se utiliza para obtener el resto de una división, como `1 % 2`, `2 % 3`, etc.

- **Exponente (**):** El exponente se utiliza para elevar un valor a una potencia, como `1 ** 2`, `2 ** 3`, etc.

## Operadores de comparación

Los operadores de comparación se utilizan para comparar dos valores. Los operadores de comparación más comunes son:

- **Igualdad (==):** La igualdad se utiliza para comprobar si dos valores son iguales, como `1 == 2`, `2 == 3`, etc.

- **Desigualdad (!=):** La desigualdad se utiliza para comprobar si dos valores son desiguales, como `1 != 2`, `2 != 3`, etc.

- **Mayor que (>):** La mayor que se utiliza para comprobar si un valor es mayor que otro, como `1 > 2`, `2 > 3`, etc.

- **Menor que (<):** La menor que se utiliza para comprobar si un valor es menor que otro, como `1 < 2`, `2 < 3`, etc.

- **Mayor o igual que (>=):** La mayor o igual que se utiliza para comprobar si un valor es mayor o igual que otro, como `1 >= 2`, `2 >= 3`, etc.

- **Menor o igual que (<=):** La menor o igual que se utiliza para comprobar si un valor es menor o igual que otro, como `1 <= 2`, `2 <= 3`, etc.

## Operadores lógicos

Los operadores lógicos se utilizan para combinar dos valores lógicos. Los operadores lógicos más comunes son:

- **Y (and):** El operador lógico y se utiliza para comprobar si dos valores son verdaderos, como `True and True`, `True and False`, etc.

- **O (or):** El operador lógico o se utiliza para comprobar si al menos uno de los dos valores es verdadero, como `True or True`, `True or False`, etc.

- **No (not):** El operador lógico no se utiliza para comprobar si un valor es falso, como `not True`, `not False`, etc.

## Operadores de asignación

Los operadores de asignación se utilizan para asignar un valor a una variable. Los operadores de asignación más comunes son:

- **Asignación (=):** El operador de asignación se utiliza para asignar un valor a una variable, como `x = 1`, `y = 2`, etc.

- **Suma y asignación (+=):** El operador de suma y asignación se utiliza para sumar un valor a una variable y asignar el resultado a la misma variable, como `x += 1`, `y += 2`, etc.

- **Resta y asignación (-=):** El operador de resta y asignación se utiliza para restar un valor a una variable y asignar el resultado a la misma variable, como `x -= 1`, `y -= 2`, etc.

- **Multiplicación y asignación (*=):** El operador de multiplicación y asignación se utiliza para multiplicar un valor a una variable y asignar el resultado a la misma variable, como `x *= 1`, `y *= 2`, etc.

- **División y asignación (/=):** El operador de división y asignación se utiliza para dividir un valor a una variable y asignar el resultado a la misma variable, como `x /= 1`, `y /= 2`, etc.

- **División entera y asignación (//=):** El operador de división entera y asignación se utiliza para dividir un valor a una variable y asignar el resultado a la misma variable, como `x //= 1`, `y //= 2`, etc.

- **Módulo y asignación (%=):** El operador de módulo y asignación se utiliza para obtener el resto de una división y asignar el resultado a la misma variable, como `x %= 1`, `y %= 2`, etc.

- **Exponente y asignación (**=):** El operador de exponente y asignación se utiliza para elevar un valor a una potencia y asignar el resultado a la misma variable, como `x **= 1`, `y **= 2`, etc.

## Operadores de identidad

Los operadores de identidad se utilizan para comprobar si dos variables son el mismo objeto. Los operadores de identidad más comunes son:

- **Es (is):** El operador de identidad se utiliza para comprobar si dos variables son el mismo objeto, como `x is y`, `y is z`, etc.

- **No es (is not):** El operador de identidad se utiliza para comprobar si dos variables no son el mismo objeto, como `x is not y`, `y is not z`, etc.

## Operadores de pertenencia

Los operadores de pertenencia se utilizan para comprobar si un valor está presente en una secuencia. Los operadores de pertenencia más comunes son:

- **Pertenece (in):** El operador de pertenencia se utiliza para comprobar si un valor está presente en una secuencia, como `1 in [1, 2, 3]`, `2 in [1, 2, 3]`, etc.

- **No pertenece (not in):** El operador de pertenencia se utiliza para comprobar si un valor no está presente en una secuencia, como `1 not in [1, 2, 3]`, `2 not in [1, 2, 3]`, etc.

## Operadores de bits

Los operadores de bits se utilizan para realizar operaciones a nivel de bits en los valores. Los operadores de bits más comunes son:

- **AND (&):** El operador AND se utiliza para realizar una operación AND a nivel de bits en dos valores, como `1 & 2`, `2 & 3`, etc.

- **OR (|):** El operador OR se utiliza para realizar una operación OR a nivel de bits en dos valores, como `1 | 2`, `2 | 3`, etc.

- **XOR (^):** El operador XOR se utiliza para realizar una operación XOR a nivel de bits en dos valores, como `1 ^ 2`, `2 ^ 3`, etc.

- **Desplazamiento a la izquierda (<<):** El operador de desplazamiento a la izquierda se utiliza para desplazar un valor a la izquierda, como `1 << 2`, `2 << 3`, etc.

- **Desplazamiento a la derecha (>>):** El operador de desplazamiento a la derecha se utiliza para desplazar un valor a la derecha, como `1 >> 2`, `2 >> 3`, etc.

- **Inversión (~):** El operador de inversión se utiliza para invertir un valor, como `~1`, `~2`, etc.

## Operadores con asignación

Los operadores con asignación se utilizan para realizar operaciones con asignación en los valores. Los operadores con asignación más comunes son:

- **Suma y asignación (+=):** El operador de suma y asignación se utiliza para sumar un valor a una variable y asignar el resultado a la misma variable, como `x += 1`, es la forma simplificada de `x = x + 1`, `y += 2`, es la forma simplificada de `y = y + 2`, etc.

- **Resta y asignación (-=):** El operador de resta y asignación se utiliza para restar un valor a una variable y asignar el resultado a la misma variable, como `x -= 1`, es la forma simplificada de `x = x - 1`, `y -= 2`, es la forma simplificada de `y = y - 2`, etc.

- **Multiplicación y asignación (*=):** El operador de multiplicación y asignación se utiliza para multiplicar un valor a una variable y asignar el resultado a la misma variable, como `x *= 1`, es la forma simplificada de `x = x * 1`, `y *= 2`, es la forma simplificada de `y = y * 2`, etc.

- **División y asignación (/=):** El operador de división y asignación se utiliza para dividir un valor a una variable y asignar el resultado a la misma variable, como `x /= 1`, es la forma simplificada de `x = x / 1`, `y /= 2`, es la forma simplificada de `y = y / 2`, etc.

- **División entera y asignación (//=):** El operador de división entera y asignación se utiliza para dividir un valor a una variable y asignar el resultado a la misma variable, como `x //= 1`, es la forma simplificada de `x = x // 1`, `y //= 2`, es la forma simplificada de `y = y // 2`, etc.

- **Módulo y asignación (%=):** El operador de módulo y asignación se utiliza para obtener el resto de una división y asignar el resultado a la misma variable, como `x %= 1`, es la forma simplificada de `x = x % 1`, `y %= 2`, es la forma simplificada de `y = y % 2`, etc.

- **Exponente y asignación (**=):** El operador de exponente y asignación se utiliza para elevar un valor a una potencia y asignar el resultado a la misma variable, como `x **= 1`, es la forma simplificada de `x = x ** 1`, `y **= 2`, es la forma simplificada de `y = y ** 2`, etc.
