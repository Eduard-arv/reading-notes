# Introducción al DOM

## ¿Qué es el DOM?

El DOM (Document Object Model) es una interfaz de programación que permite a los lenguajes como JavaScript interactuar con documentos HTML y XML. Su función principal es representar la estructura del documento como un árbol de nodos, donde cada nodo corresponde a un elemento, atributo o texto dentro del documento.

---
## Describe brevemente la relación entre el DOM y JavaScript.

El DOM y JavaScript están estrictamente relacionados,  ya que el DOM proporciona la estructura que JavaScript manipula para interactuar con documentos HTML y XML. 

Es decir, el DOM trabajando el conjunto con javascript permite  cambiar dinámicamente el contenido y la estructura de una página, hace que páginas web sean interactivas, también permite a  JavaScript acceder a los nodos de DOM, lo cual propicia a los desarrolladores seleccionar, modificar, crear o eliminar elementos en la página web.

---
## ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?

El método más común y directo para seleccionar un elemento por su ID es `getElementById()`. Este método devuelve una referencia al elemento con el ID especificado.

- Ejemplo en *JavaScript*: 

`let boton = document.getElementById("miBoton");
boton.addEventListener("click", function() {
  alert("¡Has hecho clic en el botón!");
});`

- Ejemplo en *HTML*:

`<button id="miBoton">Haz clic en mí</button>`

---
## ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?getElementById()

Para cambiar el color de fondo de un elemento en el DOM, el método más común y directo es  `getElementById()`. Este método permite seleccionar un elemento específico por su ID y luego modificar sus propiedades, como el color de fondo. 

- Ejemplo *HTML*:

`<div id="miDiv">Este es un div</div>`

- Ejemplo *JavaScript*:

// Seleccionamos el elemento con el ID "miDiv"

`let miDiv = document.getElementById("miDiv");`

// Cambiamos el color de fondo a azul

`miDiv.style.backgroundColor = "blue";` 
# Introducción al DOM

## ¿Qué es el DOM?

El DOM (Document Object Model) es una interfaz de programación que permite a los lenguajes como JavaScript interactuar con documentos HTML y XML. Su función principal es representar la estructura del documento como un árbol de nodos, donde cada nodo corresponde a un elemento, atributo o texto dentro del documento.

---
## Describe brevemente la relación entre el DOM y JavaScript.

El DOM y JavaScript están estrictamente relacionados,  ya que el DOM proporciona la estructura que JavaScript manipula para interactuar con documentos HTML y XML. 

Es decir, el DOM trabajando el conjunto con javascript permite  cambiar dinámicamente el contenido y la estructura de una página, hace que páginas web sean interactivas, también permite a  JavaScript acceder a los nodos de DOM, lo cual propicia a los desarrolladores seleccionar, modificar, crear o eliminar elementos en la página web.

---
## ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?

El método más común y directo para seleccionar un elemento por su ID es `getElementById()`. Este método devuelve una referencia al elemento con el ID especificado.

- Ejemplo en *JavaScript*:

`let boton = document.getElementById("miBoton");
boton.addEventListener("click", function() {
  alert("¡Has hecho clic en el botón!");
});`

- Ejemplo en *HTML*:

`<button id="miBoton">Haz clic en mí</button>`

---
## ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?getElementById()

Para cambiar el color de fondo de un elemento en el DOM, el método más común y directo es  `getElementById()`. Este método permite seleccionar un elemento específico por su ID y luego modificar sus propiedades, como el color de fondo. 

- Ejemplo *HTML*:

`<div id="miDiv">Este es un div</div>`

- Ejemplo *JavaScript*:

// Seleccionamos el elemento con el ID "miDiv"

`let miDiv = document.getElementById("miDiv");`

// Cambiamos el color de fondo a azul

`miDiv.style.backgroundColor = "blue";` 
