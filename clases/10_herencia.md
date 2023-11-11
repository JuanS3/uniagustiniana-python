# Herencia

La herencia es una forma de crear una clase como una versión especializada de otra clase. Las clases heredadas (a veces llamadas **clases hijas** o **subclases**) pueden hacer uso de atributos y métodos de la clase que las hereda (a veces llamada **clase padre** o **superclase**).

## **Herencia Simple**

Puedes heredar una clase de otra clase utilizando el nombre de la clase padre entre paréntesis después del nombre de la clase hija. Por ejemplo:

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def saludar(self):
        print("Hola, soy una persona")

class Estudiante(Persona):
    pass

estudiante = Estudiante("Juan", 28)
print(estudiante.nombre)
```

## **Sobreescritura de Métodos**

Puedes sobreescribir un método de la clase padre en la clase hija. Por ejemplo:

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def saludar(self):
        print("Hola, soy una persona")

class Estudiante(Persona):
    def saludar(self):
        print("Hola, soy un estudiante")

estudiante = Estudiante("Juan", 28)
estudiante.saludar()
```

## **Métodos de la Clase Padre**

Puedes llamar un método de la clase padre utilizando la función **`super()`**. Por ejemplo:

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def saludar(self):
        print("Hola, soy una persona")

class Estudiante(Persona):
    def saludar(self):
        super().saludar()
        print("Hola, soy un estudiante")

estudiante = Estudiante("Juan", 28)
estudiante.saludar()
```

## **Consideraciones Importantes**

1. **Herencia Simple:** Puedes heredar una clase de otra clase utilizando el nombre de la clase padre entre paréntesis después del nombre de la clase hija.
2. **Sobreescritura de Métodos:** Puedes sobreescribir un método de la clase padre en la clase hija.
3. **Métodos de la Clase Padre:** Puedes llamar un método de la clase padre utilizando la función **`super()`**.

## **Ejercicios**

1. Crea una clase llamada **`Vehiculo`** con los atributos **`color`** y **`ruedas`** y el método **`mostrar_caracteristicas`** que muestre por pantalla el color y el número de ruedas del vehículo.

2. Crea una clase llamada **`Coche`** que herede de la clase **`Vehiculo`** y tenga los atributos **`velocidad`** y **`cilindrada`** y el método **`mostrar_caracteristicas`** que muestre por pantalla el color, el número de ruedas, la velocidad y la cilindrada del coche.

### **Soluciones**

<details><summary>Ver Solución Ejercicio 1</summary><p>

```python
class Vehiculo:
    def __init__(self, color, ruedas):
        self.color = color
        self.ruedas = ruedas

    def mostrar_caracteristicas(self):
        print(f"Color: {self.color}")
        print(f"Ruedas: {self.ruedas}")

vehiculo = Vehiculo("Azul", 4)
vehiculo.mostrar_caracteristicas()
```


</p></details>

<details><summary>Ver Solución Ejercicio 2</summary><p>

```python
class Vehiculo:
    def __init__(self, color, ruedas):
        self.color = color
        self.ruedas = ruedas

    def mostrar_caracteristicas(self):
        print(f"Color: {self.color}")
        print(f"Ruedas: {self.ruedas}")

class Coche(Vehiculo):
    def __init__(self, color, ruedas, velocidad, cilindrada):
        super().__init__(color, ruedas)
        self.velocidad = velocidad
        self.cilindrada = cilindrada

    def mostrar_caracteristicas(self):
        super().mostrar_caracteristicas()
        print(f"Velocidad: {self.velocidad}")
        print(f"Cilindrada: {self.cilindrada}")

coche = Coche("Rojo", 4, 120, 2000)
coche.mostrar_caracteristicas()
```


---

[◀ Anterior: Programación Orientada a Objetos](09_clases.md) | [🔼](#top) | [Siguiente: módulos ▶](11_modulos.md)
