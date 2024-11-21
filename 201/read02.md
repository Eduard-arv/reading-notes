# HTML5 y CSS

## ¿Cuáles son las ventajas del uso de HTML semántico en comparación con el uso de etiquetas genéricas como <div>?

Hacer uso de un HTML semántico tiene ciertas ventajas, entre ellas tenemos:

- **Mejor estrcutura:** permite crear una estructura lógica del documento, lo cual facilita la navegación y la organización del contenido. Además, facilita la actualización y mantenimiento del sitio web.

- **Mejor SEO:** los motores de búsqueda pueden entender mejor el contenido de la página, mejorando el posicionamiento de la misma en la búsqueda hecha de los usuarios.

- **Código más limpio y legible:** el uso de etiquetas semánticas hace que el código sea más fácil de leer y entender, lo que facilita la colaboración en equipo y la detección de errores.

---
## ¿Qué etiquetas semánticas son esenciales para estructurar correctamente una página web y qué función desempeñan?

- `header`: define la cabecera de una página o sección. Acá suele insertarse el logo, menú de navegación principal, información de contacto y título principal.

- `footer`: define el pie de página de una página o sección.  

- `main`: contiene el contenido principal de la página. En él se desarrolla la temática principal.

- `section`: divide el contenido principal en secciones temáticas. Es útil para organizar grandes bloques de contenido.

-  `h1` a `h6`: se utilizan para definir los encabezados de diferentes niveles de la página. Siendo `h1` el encabezado principal y `h6` el de menor nivel.
---
## ¿Cuál es la función principal de las media queries en CSS y cómo contribuyen al diseño responsivo de una página web?

Las media queries nos permiten aplicar estilos CSS específicos según las características del dispositivo en el que se visualiza la página. Es decir, las memdia queries pueden cambiar el diseño, el layout, el tamaño de las fuentes, las imágenes, entre otras cosas.

Cabe destacar, que su contribución dentro del diseño responsivo permite que el diseño sea mas flexible y pueda observarse en diversos dispositivos (teléfonos, tablets,laptops y desktop), facilitan un mantenimiento más sencillo y garantizan una experiencia de usuario más cómoda y agradable, ya que el contenido se presenta de manera clara y legible.

---
## ¿Cuáles son las diferencias clave entre las unidades absolutas y relativas en CSS, y en qué situaciones es más apropiado utilizar cada tipo?

- **Unidades absolutas:** tienen un tamaño fijo y no se ajustan al contexto de la página. Comúnmente se utilizan cuando se necesita un tamaño exacto para imágenes, iconos o elementos gráficos. También cuando se quiere que un elemento mantenga siempre el mismo tamaño, independientemente del tamaño de la ventana del navegador.
    
    **Ejemplos:**  px (píxeles), cm (centímetros), mm (milímetros), in (pulgadas).

- **Unidades relativas:**  su tamaño se define en relación a otro elemento o a las propiedades de la ventana del navegador. Éstas son utilizadas cuando se quiere que un elemento cambie de tamaño proporcionalmente al tamaño del contenedor o de la ventana del navegador. Además, permiten que el diseño sea responsivo, permitiendo que los diseños se adapten a diferentes tamaños de pantalla. 