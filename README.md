# FLEXBOX en CSS "cajas flexibles"

**Propiedad Flex:** Según la *MDN web doc de [Mozilla](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Flexible_Box_Layout/Usando_las_cajas_flexibles_CSS),* la propiedad **Flexible Box**, o **flexbox**, de CSS3 es un modo de diseño que permite colocar los elementos de una página para que se comporten de forma predecible cuando el diseño de la página debe acomodarse a diferentes tamaños de pantalla y diferentes dispositivos. Para muchas aplicaciones, el modelo "caja flexible" produce una mejora sobre el modelo "bloque" porque no utiliza la propiedad float, ni hace que los márgenes del contenedor flexible interfieran con los márgenes de sus contenidos.

Para activar la propiedad de flex, se debe utilizar un contenedor principal y a ese contenedor se le aplica la propiedad "**display: flex**".  Ahora bien, las propiedades derivadas del flex que permiten modificar la apariencia en general de las cajas flexibles son:

* [flex-direction](https://www.w3schools.com/css/css3_flexbox.asp#flex-direction): La propiedad flex-direction define en qué dirección quiere el contenedor apilar los elementos flex.
* [flex-wrap](https://www.w3schools.com/css/css3_flexbox.asp#flex-wrap): La propiedad flex-wrap especifica si los elementos flex deberían ajustarse o no.
* [flex-flow](https://www.w3schools.com/css/css3_flexbox.asp#flex-flow): La propiedad de flujo flexible es una propiedad abreviada para establecer las propiedades de dirección flexible y envoltura flexible.
* [justify-content](https://www.w3schools.com/css/css3_flexbox.asp#justify-content): La propiedad justify-content se usa para alinear los elementos flexibles.
* [align-items](https://www.w3schools.com/css/css3_flexbox.asp#align-items): La propiedad align-items se usa para alinear los elementos flexibles verticalmente.
* [align-content](https://www.w3schools.com/css/css3_flexbox.asp#align-content): La propiedad align-content se usa para alinear las líneas flexibles.


## Child Elements "elementos secundarios" (Items)

Los elementos secundarios directos de un contenedor flexible se convierten automáticamente en elementos flexibles (flex). Siendo estos:

* [order](https://www.w3schools.com/css/css3_flexbox.asp#order): La propiedad order especifica el orden de los elementos flexibles.
* [flex-grow](https://www.w3schools.com/css/css3_flexbox.asp#flex-grow): La propiedad de crecimiento flexible especifica cuánto crecerá un elemento flexible en relación con el resto de los elementos flexibles.
* [flex-shrink](https://www.w3schools.com/css/css3_flexbox.asp#flex-shrink): La propiedad de contracción flexible especifica cuánto se reducirá un elemento flexible en relación con el resto de los elementos flexibles
* [flex-basis](https://www.w3schools.com/css/css3_flexbox.asp#flex-basis): La propiedad de base flexible especifica la longitud inicial de un elemento flexible.
* [flex](https://www.w3schools.com/css/css3_flexbox.asp#flex): La propiedad flex es una propiedad abreviada de las propiedades de crecimiento flexible, contracción flexible y base flexible.
* [align-self](https://www.w3schools.com/css/css3_flexbox.asp#align-self): La propiedad align-self especifica la alineación para el elemento seleccionado dentro del contenedor flexible. Así mismo, esta propiedad anula la alineación predeterminada establecida por la propiedad align-items del contenedor.
