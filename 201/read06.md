# Paradigmas de la programación 1

## ¿Qué es la programación funcional y cuáles son sus principales características que la diferencian de otros paradigmas de programación?

La programación funcional es un paradigma de programación que se centra en el uso de funciones matemáticas puras para resolver problemas, evitando el uso de estado mutable y efectos secundarios. 

- Características principales: 

1. **Funciones puras:** Las funciones siempre devuelven el mismo resultado para los mismos argumentos y no tienen efectos secundarios, lo que significa que no alteran el estado del programa ni dependen de él.

2. **Inmutabilidad:** los datos son inmutables, lo que implica que una vez creados no pueden ser modificados.

3. **Funciones de orden superior:** permiten tratar funciones como valores, pudiendo ser pasadas como argumentos o retornadas desde otras funciones. Esto favorece la creación de código modular y reutilizable.

4. **Recursividad:** en lugar de usar bucles tradicionales, se emplea la recursión para realizar iteraciones, permitiendo un estilo de programación más declarativo.

A diferencia de la *programación imperativa*, la *programación funcional* enfatiza la declaración de lo que se quiere lograr sin preocuparse por cómo se logra, lo que da como resultado un código más limpio y fácil de entender.

---

## ¿Cómo aplicarías el principio DRY en un proyecto de JavaScript? Proporciona un ejemplo práctico de código antes y después de aplicar este princ.ipio.

El principio DRY (Don't Repeat Yourself, o "No te repitas") se basa en la idea de que cada pieza de conocimiento o lógica en un programa debe tener una única representación. Esto implica que debemos evitar duplicaciones innecesarias en el código, lo que facilita su mantenimiento, mejora la legibilidad y reduce el riesgo de errores.

Para aplicar el principio DRY en un proyecto de JavaScript, se pueden aplicar las siguientes prácticas:

- **Identificar duplicaciones:** revisar el código para encontrar patrones repetitivos.

- **Crear funciones reutilizables:** encapsular lógica común en funciones que se puedan llamar desde diferentes partes del código.

- **Utilizar componentes:** en aplicaciones más grandes, como las basadas en frameworks (React, Vue), crear componentes reutilizables.

- **Centralizar configuraciones:** usar variables o constantes para valores que se repiten.

---

## ¿Cuáles son las ventajas de utilizar métodos funcionales como map(), filter() y reduce() en lugar de bucles tradicionales?

Los métodos funcionales como map(), filter() y reduce() ofrecen una forma más legible y concisa de trabajar con arreglos en JavaScript en comparación con los bucles tradicionales. Fomentan la inmutabilidad y reducen la posibilidad de errores comunes asociados con el manejo del estado mutable. Esto no solo mejora la calidad del código sino también su mantenibilidad a largo plazo.

Dentro de sus ventajas principales se encuentran:

1. **Concisión:** estos métodos suelen requerir menos líneas de código en comparación con los bucles tradicionales, lo que reduce la cantidad de código necesario para realizar operaciones comunes en arreglos.

2. **Legibilidad:** ya que permiten escribir código más declarativo, lo que facilita la comprensión de lo que se está intentando lograr sin tener que desglosar la lógica de control de flujo, como en un bucle tradicional. 

3. **Inmutabilidad:** Los métodos funcionales fomentan el uso de datos inmutables, lo que significa que no modifican el arreglo original, sino que devuelven un nuevo arreglo. Esto ayuda a prevenir efectos secundarios y errores relacionados con el estado mutable

4. **Composición:** permiten componer funciones fácilmente, lo que facilita la creación de soluciones más complejas a partir de funciones simples y reutilizables.

---

## ¿De qué manera el principio DRY y la programación funcional se complementan entre sí para escribir código más mantenible y escalable?

El principio DRY y la programación funcional se complementan al fomentar la creación de código más limpio, mantenible y escalable. Al aplicar DRY, se evita la duplicación de lógica mediante la reutilización de funciones y componentes, lo que reduce errores y facilita el mantenimiento. La programación funcional, al centrarse en funciones puras e inmutabilidad, promueve la creación de pequeñas unidades de código que pueden ser fácilmente reutilizadas y combinadas. Juntas, estas prácticas permiten desarrollar aplicaciones más coherentes y modulares, mejorando la legibilidad y la capacidad de adaptación a cambios futuros en el software.
