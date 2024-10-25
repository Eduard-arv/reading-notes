# INTRO A CSS

## ¿Cuál es el propósito de CSS?

El propósito principal de CSS es agregar diseño y vistocidad a una página web. A través de este lenguaje se pueden incluir caracterísitcas como el color de los enunciados o párrafos, crear columnas dinámicas, animaciones, entre otros.

---

## ¿Qué analogía NO técnica usarías para explicar la responsabilidad de HTML vs. CSS?

Imaginemos lo siguiente, supongamos que que desea construir una casa, para construirla se necesitan crear las bases, las estructuras y la forma de dicha casa, como el tamaño, la cantidad de pisos, baños, etc. A todo este proceso le denominameros el HTML, ya que este lenguaje de marcado permite dar toda la estructura y forma necesaria al inmueble que estamos construyendo (página web). Por otra parte, ya teniendo la estructura, forma y tamaño de dicha casa, ahora queremos personalizarla al gusto del cliente, en este caso seria la forma y color de la fachada, el tipo de construcción que el cliente desee (sea minimalista, gótica, futurista, etc) y por último, los detalles estéticos y detallados de la casa, como el color interior de los espacios, el porcelatano preferido, la distribución de los espacios internos, los muebles, entre otros. Este proceso sería el CSS, ya que éste es el encargado de como se visualiza estéticamente la la página web, en este caso sería la casa.

---
## ¿Cuáles son las tres formas de insertar CSS en tu proyecto?

CSS externo: se utiliza dentro del elemento ***link*** dentro del encabezado y este permite cambiar la apariencia de un sitio web. Cabe destacar, que no debe contener ninguna etiqueta de HTML.
CSS interno: este se incluye dentro del ***head*** utilizando el elemento ***style***. Este permite ir modificando la apariencia de cada uno de los elementos de la página web, agregando detalles como el color, tamaño de la letra, el fondo, entre otros.
CSS en línea: este permite agregar diseño a un elemento utilizando el atributo "style" en un elemento en específico dentro del ***body>***. 

**Ejemplo:**

***h2 style="color: black;*** "párrafo de la página web" ***h2***

---
## Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos ***"p"***.

Utilizando la regla de CSS interno se puede modificar el color de un párrafo de la siguiente manera:

***p{***

- color: red
- text-align: justify;
- font-size: 18px;

***}***

En este caso, además de modificar el texto a color rojo, se le dió un tamaño específico a la letra y se alineó de forma justificada.