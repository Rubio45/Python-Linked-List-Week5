# Lista Enlazada - Operaciones Básicas en Python

Este repositorio contiene una implementación de una **lista enlazada simple** en Python. Se han realizado varias mejoras respecto a la versión inicial para manejar inserciones, cálculos y operaciones sobre la estructura de datos.

---

## 🚀 Funcionalidades implementadas

- ✅ Lectura de datos para insertar en la lista
- ✅ Inserción de nodos **al inicio** de la lista con el método `insertar_al_inicio()`
- ✅ Método `cantidad_nodos()` que devuelve el número total de nodos
- ✅ Método `sumar_valores_nodos()` que suma todos los valores enteros de los nodos
- ✅ Método `primer_valor()` que muestra el primer valor de la lista

---

## 🧪 Ejemplo de uso

```python
lista = ListaEnlazada()

# Insertar datos
lista.insertarInicio(5)
lista.insertarInicio(10)
lista.insertarInicio(15)

# Cantidad de nodos
print("Cantidad de nodos:", lista.cantidadNodos())  # Output: 3

# Suma de los valores
print("Suma total:", lista.sumarValores())  # Output: 30

# Primer valor de la lista
lista.imprimirPrimero()  # Output: 15