# Parcial Paradigmas 📝

Este documento describe dos ejercicios realizados durante el parcial, uno de programación estructurada y otro de programación orientada a objetos.

---

## 1. Estructural.py 🧮

El programa tiene como objetivo contar la cantidad de números pares dentro de una lista, función útil para análisis de datos como el conteo de eventos o el filtrado de registros.

Al depurar el código usando el debugger de Python 🐍, se detectó un error en la línea 7: la instrucción `if n % 2 = 0:` utiliza el operador de asignación (`=`) en lugar del operador de comparación (`==`). Este error causa que el programa falle, ya que la condición debe verificar si el resto de la división de `n` entre 2 es igual a cero. La corrección consiste en cambiar la línea a `if n % 2 == 0:`, de modo que el contador aumente correctamente cuando el número sea par ✅.

---

## 2. oop.py 📐

Este ejercicio modela figuras geométricas, con aplicaciones en diseño asistido por computadora o en el cálculo de áreas.

En el método que calcula el área, originalmente se tenía la instrucción `return base * altura`. Sin embargo, las variables `base` y `altura` no estaban definidas dentro del método, por lo que el cálculo debía referirse a los atributos del objeto usando `self`. La línea corregida es `return self.base * self.altura` 🔧.

Adicionalmente, para clarificar la unidad de medida del resultado, se agregó la indicación de centímetros en la impresión final, mostrando el área como `Área: <valor> cm²` 📏.

---

Si deseas más detalles o ayuda adicional con el código, estoy a tu disposición 🙌.
