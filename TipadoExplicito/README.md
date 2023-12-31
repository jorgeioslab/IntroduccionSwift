# Importancia del Tipado Explícito en Swift

En Swift, el "tipado explícito" se refiere a la práctica de especificar claramente el tipo de datos de una variable o constante cuando se declara. Aunque Swift es un lenguaje con inferencia de tipos, lo que significa que el compilador puede deducir el tipo de datos en función del valor asignado, el tipado explícito sigue siendo una práctica valiosa por varias razones.

## Razones para el Tipado Explícito


1. **La seguridad de tipo:** te obliga a ser explícito sobre el “tipo” de cada objeto que creas, manipulas y asignas, y solo te permite escribir un código que el objeto dado pueda manejar.
2. **Prevención de Errores**: Es posible cometer errores al asignar valores a variables sin especificar el tipo de datos. Con el tipado explícito, se pueden detectar errores tempranamente, ya que el compilador verificará que los tipos coincidan correctamente.
3. **Velocidad:** La inferencia de tipo le permite al compilador inferir el tipo de un objeto, lo que ahorra tiempo y garantiza que el compilador pueda hacer cumplir las reglas adecuadas con respecto a las operaciones y funciones que se pueden realizar con cada tipo.

## Sintaxis del Tipado Explícito

La sintaxis para declarar una variable o constante con tipado explícito en Swift es la siguiente:

```swift
var variable: TipoDeDato
let constante: TipoDeDato
```
Ejemplos: 

```swift
var edad: Int = 22
let nombre: String = "Alberto"
var altura: Double = 1.80
```
[<< Anterior](../TiposDeDatos) | [Siguiente >>](../Operadores)
