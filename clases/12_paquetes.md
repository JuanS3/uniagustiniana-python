# **Paquetes**

Los paquetes son directorios que contienen módulos. Para crear un paquete, debes crear un directorio y agregar un archivo **`__init__.py`**. Por ejemplo:

```bash
paquete/
├── __init__.py
├── modulo1.py
└── modulo2.py
```

Puedes importar un módulo de un paquete utilizando la notación de punto. Por ejemplo:

```python
import paquete.modulo1
```

## **Importación de Módulos de un Paquete**

Puedes importar un módulo de un paquete utilizando la notación de punto. Por ejemplo:

```python
import paquete.modulo1
```

## **Importación de Módulos de un Paquete con Alias**

Puedes importar un módulo de un paquete con un alias utilizando la palabra reservada **`as`**. Por ejemplo:

```python
import paquete.modulo1 as md
```

## **Importación de Todas las Funciones de un Módulo de un Paquete**

Puedes importar todas las funciones de un módulo de un paquete utilizando el carácter **`*`**. Por ejemplo:

```python
from paquete.modulo1 import *
```

## **Importación de Módulos de un Paquete con Alias**

Puedes importar un módulo de un paquete con un alias utilizando la palabra reservada **`as`**. Por ejemplo:

```python
from paquete.modulo1 import funcion1 as fn1
```

## **Consideraciones Importantes**

1. **Importación de Módulos de un Paquete:** Puedes importar un módulo de un paquete utilizando la notación de punto.

2. **Importación de Módulos de un Paquete con Alias:** Puedes importar un módulo de un paquete con un alias utilizando la palabra reservada **`as`**.

3. **Importación de Todas las Funciones de un Módulo de un Paquete:** Puedes importar todas las funciones de un módulo de un paquete utilizando el carácter **`*`**.

4. **Importación de Módulos de un Paquete con Alias:** Puedes importar un módulo de un paquete con un alias utilizando la palabra reservada **`as`**.

---

[◀ Anterior: Módulos](11_modulos.md) | [🔼](#top) | [Siguiente: atributos ▶](13_atributos.md)