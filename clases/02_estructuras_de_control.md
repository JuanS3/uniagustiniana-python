# Estructuras de Control en Python

Las estructuras de control son bloques de código que permiten controlar el flujo de ejecución de un programa. En Python, existen tres estructuras de control principales: `if`, `for` y `while`.

## Estructura de control `if`

La estructura de control `if` permite ejecutar un bloque de código si se cumple una condición. La sintaxis de la estructura de control `if` es la siguiente:

```python
if condicion:
    # Bloque de código
```

En el ejemplo anterior, el bloque de código se ejecutará si la condición es verdadera. Si la condición es falsa, el bloque de código no se ejecutará.

La estructura de control `if` también puede tener un bloque de código alternativo que se ejecutará si la condición es falsa. La sintaxis de la estructura de control `if` con un bloque de código alternativo es la siguiente:

```python
if condicion:
    # Bloque de código
else:
    # Bloque de código alternativo
```

En el ejemplo anterior, el bloque de código alternativo se ejecutará si la condición es falsa. Si la condición es verdadera, el bloque de código alternativo no se ejecutará.

La estructura de control `if` también puede tener múltiples bloques de código alternativos que se ejecutarán si la condición es falsa. La sintaxis de la estructura de control `if` con múltiples bloques de código alternativos es la siguiente:

```python
if condicion1:
    # Bloque de código 1
elif condicion2:
    # Bloque de código 2
elif condicion3:
    # Bloque de código 3
else:
    # Bloque de código alternativo
```

En el ejemplo anterior, el bloque de código 1 se ejecutará si la condición 1 es verdadera. Si la condición 1 es falsa, el bloque de código 2 se ejecutará si la condición 2 es verdadera. Si la condición 2 es falsa, el bloque de código 3 se ejecutará si la condición 3 es verdadera. Si la condición 3 es falsa, el bloque de código alternativo se ejecutará.

## Estructura de control `for`

La estructura de control `for` permite ejecutar un bloque de código varias veces. La sintaxis de la estructura de control `for` es la siguiente:

```python
for variable in secuencia:
    # Bloque de código
```

En el ejemplo anterior, el bloque de código se ejecutará una vez para cada elemento de la secuencia. La variable tomará el valor de cada elemento de la secuencia en cada iteración.

La estructura de control `for` también puede tener un bloque de código alternativo que se ejecutará cuando se termine de iterar sobre la secuencia. La sintaxis de la estructura de control `for` con un bloque de código alternativo es la siguiente:

```python
for variable in secuencia:
    # Bloque de código
else:
    # Bloque de código alternativo
```

En el ejemplo anterior, el bloque de código alternativo se ejecutará cuando se termine de iterar sobre la secuencia. Si la secuencia está vacía, el bloque de código alternativo se ejecutará inmediatamente.

## Estructura de control `while`

La estructura de control `while` permite ejecutar un bloque de código mientras se cumpla una condición. La sintaxis de la estructura de control `while` es la siguiente:

```python
while condicion:
    # Bloque de código
```

En el ejemplo anterior, el bloque de código se ejecutará mientras la condición sea verdadera. Si la condición es falsa, el bloque de código no se ejecutará.

La estructura de control `while` también puede tener un bloque de código alternativo que se ejecutará cuando la condición sea falsa. La sintaxis de la estructura de control `while` con un bloque de código alternativo es la siguiente:

```python
while condicion:
    # Bloque de código
else:
    # Bloque de código alternativo
```

En el ejemplo anterior, el bloque de código alternativo se ejecutará cuando la condición sea falsa. Si la condición es verdadera, el bloque de código alternativo no se ejecutará.

## Estrucutra de control `match`

La estructura de control `match` permite ejecutar un bloque de código dependiendo del valor de una variable. La sintaxis de la estructura de control `match` es la siguiente:

```python
match variable:
    case valor1:
        # Bloque de código 1
    case valor2:
        # Bloque de código 2
    case valor3:
        # Bloque de código 3
    case _:
        # Bloque de código alternativo
```

En el ejemplo anterior, el bloque de código 1 se ejecutará si el valor de la variable es igual a `valor1`. Si el valor de la variable es igual a `valor2`, el bloque de código 2 se ejecutará. Si el valor de la variable es igual a `valor3`, el bloque de código 3 se ejecutará. Si el valor de la variable no es igual a ninguno de los valores anteriores, el bloque de código alternativo se ejecutará.

*NOTA: La estructura de control `match` está disponible a partir de Python 3.10.*

