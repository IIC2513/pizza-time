# Pizza time - Actividad propuesta sobre JS

## Código

Puedes utilizar [este pen](https://codepen.io/aaossa/pen/MWRmWXK) y guardarlo en tu perfil haciendo un "fork". Alternativamente, el mismo código fuente está disponible en este repositorio.

## Actividad

### Parte 1 - Calcular precio con `calculatePrice`

Escribir una función `calculatePrice` que recibe los parámetros `nPepperonis`, `nBasils`, `nMushrooms`, `hasSauce` y `hasCheese` (los primeros tres son números, los últimos dos booleans). La función deberá retornar el precio total de la pizza considerando que:

1. El precio base de la pizza es 5
2. Cada pepperoni vale 0.5, cada albahaca vale 0.3 y cada champiñon vale 0.1
3. Si lleva salsa se suma 1, si lleva queso se suma 1.5

La salida de esta función aparecerá en la consola, para debuggear más fácilmente. Tendrán que usar control de flujo y operaciones matemáticas para llegar al resultado. La función debe retornar solo un número.

### Parte 2 - Mostrar boleta y precio con `displayInvoice`

Escribir una funcion `displayInvoice` para mostrar un resumen de los ingredientes elegidos y que incluya el precio total (utilizar función `calculatePrice`). Se recomienda agregar elementos HTML apropiados en el DIV con id "order-summary". Por ejemplo, se pueden usar tags LI dentro de un tag UL para cada ingrediente junto con su cantidad, y mostrar un tag P que contenga el precio.

En esta función se deberán usar métodos como `document.getElementById`, `document.createElement`, `document.createTextNode` y `elem.appendChild`. Esta función no debe retornar ningún tipo de valor.
