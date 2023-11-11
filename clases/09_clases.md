# Programación Orientada a Objetos

## **Clases**

Las clases son una forma de organizar y producir objetos con características similares. Las clases se definen utilizando la palabra clave **`class`**. Por ejemplo:

```python
class Persona:
    pass
```

## **Objetos**

Los objetos son instancias de una clase. Puedes crear un objeto utilizando el nombre de la clase seguido de paréntesis. Por ejemplo:

```python
class Persona:
    pass

persona = Persona()
```

## **Atributos**

Los atributos son características de un objeto. Puedes crear atributos utilizando la notación de punto. Por ejemplo:

```python
class Persona:
    pass

persona = Persona()
persona.nombre = "Juan"
persona.edad = 28
```

## **Métodos**

Los métodos son funciones que pertenecen a una clase. Puedes crear métodos utilizando la notación de punto. Por ejemplo:

```python
class Persona:
    def saludar(self):
        print("Hola, soy una persona")

persona = Persona()
persona.saludar()
```

## **Constructor**

El constructor es un método especial que se ejecuta cuando se crea un objeto. El constructor se llama **`__init__`** y recibe como primer parámetro **`self`**. Por ejemplo:

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def saludar(self):
        print("Hola, soy una persona")

persona = Persona("Juan", 28)
print(persona.nombre)
print(persona.edad)
```

## **Consideraciones Importantes**

1. **Clases:** Las clases son una forma de organizar y producir objetos con características similares. Las clases se definen utilizando la palabra clave **`class`**.
2. **Objetos:** Los objetos son instancias de una clase. Puedes crear un objeto utilizando el nombre de la clase seguido de paréntesis.
3. **Atributos:** Los atributos son características de un objeto. Puedes crear atributos utilizando la notación de punto.
4. **Métodos:** Los métodos son funciones que pertenecen a una clase. Puedes crear métodos utilizando la notación de punto.
5. **Constructor:** El constructor es un método especial que se ejecuta cuando se crea un objeto. El constructor se llama **`__init__`** y recibe como primer parámetro **`self`**.


---

[◀ Anterior: Excepciones](08_excepciones.md) | [🔼](#top) | [Siguiente: Herencia ▶](10_herencia.md)
