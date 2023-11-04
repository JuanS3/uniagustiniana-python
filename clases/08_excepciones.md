
# Excepciones

Las excepciones son errores que ocurren durante la ejecución de un programa. Las excepciones pueden ser manejadas para evitar que el programa se detenga abruptamente. En Python, las excepciones se manejan utilizando las palabras clave **`try`**, **`except`**, **`else`** y **`finally`**.

## **Manejo de Excepciones**

Puedes manejar las excepciones utilizando un bloque **`try`**-**`except`**. Por ejemplo:

```python
try:
    # Código que puede generar una excepción
except:
    # Código que se ejecuta cuando se genera una excepción
```

## **Tipos de Excepciones**

Puedes especificar el tipo de excepción que quieres manejar. Por ejemplo:

```python
try:
    # Código que puede generar una excepción
except ValueError:
    # Código que se ejecuta cuando se genera una excepción ValueError
```

## **Else y Finally**

Puedes utilizar un bloque **`else`** para especificar el código que se ejecutará cuando no se genere una excepción. Puedes utilizar un bloque **`finally`** para especificar el código que se ejecutará sin importar si se genera una excepción o no. Por ejemplo:

```python
try:
    # Código que puede generar una excepción
except ValueError:
    # Código que se ejecuta cuando se genera una excepción ValueError
else:
    # Código que se ejecuta cuando no se genera una excepción
finally:
    # Código que se ejecuta sin importar si se genera una excepción o no
```

## **Levantamiento de Excepciones**

Puedes utilizar la palabra clave **`raise`** para levantar una excepción. Por ejemplo:

```python
raise ValueError("El valor debe ser positivo")
```

## **Consideraciones Importantes**

1. **Manejo de Excepciones:** Las excepciones son errores que ocurren durante la ejecución de un programa. Las excepciones pueden ser manejadas para evitar que el programa se detenga abruptamente.

2. **Tipos de Excepciones:** Puedes especificar el tipo de excepción que quieres manejar.

3. **Else y Finally:** Puedes utilizar un bloque **`else`** para especificar el código que se ejecutará cuando no se genere una excepción. Puedes utilizar un bloque **`finally`** para especificar el código que se ejecutará sin importar si se genera una excepción o no.

4. **Levantamiento de Excepciones:** Puedes utilizar la palabra clave **`raise`** para levantar una excepción.

---

[◀ Anterior: archivos](07_archivos.md) | [🔼](#top) | [Siguiente: Clases ▶](09_clases.md)