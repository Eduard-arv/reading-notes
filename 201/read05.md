# Estructuras de Control y Datos en JavaScript

## ¿Cuáles son los diferentes tipos de estructuras condicionales en JavaScript y en qué situaciones deberías usar cada una?

- **Estructuras Condicionales Simples:** la estructura condicional simple utiliza la instrucción `if` para ejecutar un bloque de código solo si se cumple una condición específica. Si la condición es falsa, no se ejecuta nada.

***Uso:*** se utiliza cuando solo necesitas verificar una condición y realizar una acción si se cumple.

- **Estructuras Condicionales Dobles:** esta estructura utiliza `if` junto con `else`. Permite ejecutar un bloque de código si la condición es verdadera y otro bloque si es falsa.

***Uso:*** Se emplea cuando hay dos caminos posibles a seguir, dependiendo del resultado de una condición.

- **Estructuras Condicionales Múltiples:** utiliza `if`, `else if` y `else` para evaluar múltiples condiciones. Permite manejar más de dos resultados posibles.

***Uso:*** se usa cuando hay varias condiciones a evaluar, y cada una requiere una acción diferente.

- **Estructura Condicional Switch:** la instrucción switch permite seleccionar uno de muchos bloques de código a ejecutar, basado en el valor de una variable.

***Uso:*** es útil cuando se necesita evaluar una variable contra múltiples valores específicos, especialmente cuando hay muchas condiciones que podrían ser evaluadas.

---

## En el contexto de arreglos en JavaScript, ¿cuál es la diferencia entre los métodos push(), unshift() y splice(), y cuándo usarías cada uno?

Los métodos push(), unshift() y splice() se utilizan para modificar arreglos en Javasript. Sin embagro, cada uno tiene un propósito y comportamiento diferente.

**Métodos:**

1. `push()`: agrega uno o más elementos al final de un arreglo.

    **Retorno:** Devuelve la nueva longitud del arreglo.

***Uso:*** se utiliza cuando deseas añadir elementos al final de un arreglo, como al construir una lista o agregar resultados a una colección existente.

2. `unshift()`: agrega uno o más elementos al inicio de un arreglo.

    **Retorno:** también devuelve la nueva longitud del arreglo.

***Uso:*** se usa cuando necesitas insertar elementos al principio del arreglo, como al implementar una cola o cuando el orden de los elementos es importante desde el inicio.

3. `splice()`: cambia el contenido de un arreglo eliminando o reemplazando elementos existentes y/o agregando nuevos elementos en una posición específica.

    **Retorno:** devuelve un nuevo arreglo que contiene los elementos eliminados.

***Uso:*** se utiliza para realizar operaciones más complejas, como eliminar elementos en posiciones específicas o reemplazar elementos existentes.

---

## ¿Qué diferencias existen entre los bucles for, while y do...while? Proporciona un ejemplo práctico de uso para cada uno.

- `for`: se utiliza cuando se conoce de antemano el número de iteraciones. Se define una variable de control, una condición y un incremento/decremento en una sola línea.

***Uso:*** Ideal para iterar sobre arreglos o cuando se necesita un conteo específico.

***Ejemplo:***

for (let i = 0; i < 5; i++) {
    
    console.log(i); // Imprime los números del 0 al 4
}

- `while`: ejecuta un bloque de código mientras una condición sea verdadera. La condición se evalúa antes de cada iteración.

***Uso:*** útil cuando no se sabe cuántas veces se debe iterar y la condición puede cambiar dentro del bucle.

***Ejemplo:***

`let i = 0;
while (i < 5) {
    console.log(i); // Imprime los números del 0 al 4
    
    i++;
}`

- `do...while`: similar al bucle while, pero garantiza que el bloque de código se ejecute al menos una vez, ya que la condición se evalúa después de la ejecución.

***Uso:*** se usa cuando es necesario que el código se ejecute al menos una vez, independientemente de la condición.

***Ejemplo:*** 

`let i = 0;
do {
    console.log(i); // Imprime los números del 0 al 4
    
    i++;
} while (i < 5);`

---

## ¿Cómo se puede recorrer un arreglo en JavaScript utilizando diferentes tipos de bucles y cuál consideras más eficiente según el caso de uso?

1. Método `forEach()`: es un método de los arreglos que ejecuta una función proporcionada una vez por cada elemento del arreglo.

***Uso:*** Muy limpio y legible, ideal para aplicar una función a cada elemento sin preocuparse por el índice.

2. Método `map()`: similar a forEach, pero crea un nuevo arreglo con los resultados de aplicar una función a cada elemento.

***Uso:*** útil cuando necesitas transformar los elementos del arreglo y obtener un nuevo arreglo.

3. Bucle `for`: permite iterar sobre un arreglo utilizando un índice. Es útil cuando se conoce la longitud del arreglo y se necesita un control preciso sobre el índice.

***Uso:*** Ideal para iteraciones donde se requiere acceder a elementos por su índice.

4. Bucle `while`: ejecuta un bloque de código mientras una condición sea verdadera. Se puede usar con un contador que se incrementa dentro del bucle.

***Uso:*** útil cuando no se sabe cuántas iteraciones se realizarán de antemano.

5. Bucle `do...while`: similar al while, pero garantiza que el bloque de código se ejecute al menos una vez, ya que la condición se evalúa después de la ejecución.

***Uso:*** ideal cuando es necesario que el código se ejecute al menos una vez, independientemente de la condición inicial.