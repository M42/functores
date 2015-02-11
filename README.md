# functores
Functores y mónadas en Haskell y en teoría de categorías.

## Índice de contenidos

1. Bases de Haskell.
  2. Evaluación perezosa.
  3. Recursividad y referencia transparencial.
1. Sistema de tipos.
  2. Variables y clases de tipos.
  1. Definición de tipos algebraicos.
  2. Constructores de tipos: Listas y Maybe.
2. Definición de funciones.
  3. Currificación.
  3. Funciones de orden superior.
4. Funtores.
  5. Definición de funtor: `fmap`
  5. Leyes de los funtores.
  5. Definición de funtor aplicativo: `pure`, `<*>`, `<$>`.
  6. Leyes de los funtores aplicativos.
7. Ejemplos de funtores.
  8. `Maybe`
  9. `ZipList` **(?)**
  10. `((->) r)`
5. Mónadas.
  6. Definición de mónada: `>>=` y `return`.
  7. Leyes de las mónadas.
  8. Notación `do`.
  9. `Control.Monad`
  7. Mónadas de una sóla dirección. **(?)**
  8. Transformadores de mónadas. **(?)**
6. Ejemplos de Mónadas
  7. `Identity` **(?)**
  7. `List`.
  8. `Maybe`.
  9. `Writer` **(?)**
  10. `State` y `IO` **(?)**
  
**(?)**: No sé si es suficientemente relevante.
