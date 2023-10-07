NOTA: El notebook de esta clase está disponible como [03_funciones.ipynb](03_funciones.ipynb) en este repositorio.

---

# Funciones en Python

Una función es un bloque de código que se puede ejecutar varias veces. Una función puede tener parámetros y puede devolver un valor.

## Definición de funciones

La sintaxis para definir una función en Python es la siguiente:

```python
def nombre_funcion(parametro1, parametro2, ...):
    # Bloque de código
    return valor
```

En el ejemplo anterior, `nombre_funcion` es el nombre de la función, `parametro1`, `parametro2`, etc. son los parámetros de la función y `valor` es el valor que devuelve la función.

## Llamada a funciones

La sintaxis para llamar a una función en Python es la siguiente:

```python
nombre_funcion(argumento1, argumento2, ...)
```

En el ejemplo anterior, `nombre_funcion` es el nombre de la función y `argumento1`, `argumento2`, etc. son los argumentos de la función.

## Ejemplo de función

El siguiente ejemplo muestra una función que suma dos números:

```python
def sumar(a, b):
    return a + b

print(sumar(2, 3))
```

En el ejemplo anterior, la función `sumar` toma dos parámetros, `a` y `b`, y devuelve la suma de los dos parámetros. La función se llama con los argumentos `2` y `3`, por lo que devuelve `5`.

## Ejemplo de función con parámetros opcionales

El siguiente ejemplo muestra una función que suma dos números y un parámetro opcional:

```python
def sumar(a, b, c=None):
    if c is None:
        return a + b
    else:
        return a + b + c

print(sumar(2, 3))
print(sumar(2, 3, 4))
```

En el ejemplo anterior, la función `sumar` toma dos parámetros, `a` y `b`, y un parámetro opcional, `c`. Si el parámetro `c` no se especifica, la función devuelve la suma de los dos parámetros. Si el parámetro `c` se especifica, la función devuelve la suma de los tres parámetros. La función se llama con los argumentos `2` y `3`, por lo que devuelve `5`. La función también se llama con los argumentos `2`, `3` y `4`, por lo que devuelve `9`.

## Ejemplo de función con parámetros opcionales con valores por defecto

El siguiente ejemplo muestra una función que suma dos números y un parámetro opcional con un valor por defecto:

```python
def sumar(a, b, c=0):
    return a + b + c

print(sumar(2, 3))
print(sumar(2, 3, 4))
```

En el ejemplo anterior, la función `sumar` toma dos parámetros, `a` y `b`, y un parámetro opcional, `c`, con un valor por defecto de `0`. Si el parámetro `c` no se especifica, la función devuelve la suma de los dos parámetros. Si el parámetro `c` se especifica, la función devuelve la suma de los tres parámetros. La función se llama con los argumentos `2` y `3`, por lo que devuelve `5`. La función también se llama con los argumentos `2`, `3` y `4`, por lo que devuelve `9`.

## Ejemplo de función con argumentos con nombre

El siguiente ejemplo muestra una función que suma dos números y un parámetro opcional con un valor por defecto y argumentos con nombre:

```python
def resta(a, b):
    return a - b

print(resta(2, 3))
print(resta(2, b=3))
print(resta(a=2, b=3))
print(resta(b=3, a=2))
```

En el ejemplo anterior, la función `resta` toma dos parámetros, `a` y `b`, y devuelve la resta de los dos parámetros. La función se llama con los argumentos `a=2` y `b=3`, por lo que devuelve `-1`. La función también se llama con los argumentos `b=3` y `a=2`, por lo que devuelve `-1`.


## Ejemplo de función con argumentos con nombre y argumentos con nombre

El siguiente ejemplo muestra una función que suma dos números y un parámetro opcional con un valor por defecto y argumentos con nombre y argumentos con nombre:

```python
def resta(a, b):
    return a - b

print(sumar(a=2, b=3))
print(sumar(b=3, a=2))
```

En el ejemplo anterior, la función `resta` toma dos parámetros, `a` y `b`, y devuelve la resta de los dos parámetros. La función se llama con los argumentos `a=2` y `b=3`, por lo que devuelve `-1`. La función también se llama con los argumentos `b=3` y `a=2`, por lo que devuelve `-1`.

# Ejercicios

## Ejercicio 1

Escribir una función que tome como parámetro un número entero y devuelva `True` si el número es par y `False` si el número es impar.

## Ejercicio 2

Escribir una función que tome como parámetro un número entero y devuelva `True` si el número es primo y `False` si el número no es primo.

## Ejercicio 3

Escribir una función que tome como parámetro un número entero y devuelva una lista con todos los números primos menores o iguales que el número pasado como parámetro.

## Ejercicio 4

Escribir una función que tome como parámetro un número entero y devuelva una lista con todos los números primos menores o iguales que el número pasado como parámetro.

## Ejercicio 5

Escribir una función que tome como parámetro un número entero y devuelva una lista con todos los números primos menores o iguales que el número pasado como parámetro.

---


[◀ Anterior: Variables y Tipos de Datos](01_variables_en_python.md) | [🔼](#top) | [Siguiente: Recursividad ▶](04_recursividad.md)
