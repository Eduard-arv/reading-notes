# Introducción a Javascript

## ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?

- **Datos primitivos:** son aquellos que no se puede dividir en partes más pequeñas. En ellos podemos encontrar *Booleano* que representa un valor de verdad (´true´ ´false´), *Nulo* que indica la ausencia de cualquier valor, *Number* que se aplica para números enteros y de punto flotante, entre otros.

- **Datos no primitivos:** éstos pueden contener múltiples valores. Por ejemplo *objeto* que representa una colección de propiedades y métodos, permitiendo almacenar múltiples valores y estructuras complejas.
---
## ¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa?

El propósito de éstos condiconales en contralar el flujo y trabajar condiciones múltiples, es decir, permiten tomar decisiones dentro del programa y pueden encadenar múñtiples condiciones usando ´else if´. Ejemplo:


 if (condición) {
    } 
else {
}

---
## ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?

JavaScript utiliza varios tipos de operadores, entre ellos estan:

- Operadores de Asignación
- Operadores de Comparación
- Operadores Lógicos
- Operadores Bit a Bit
- Operadores Aritméticos

Este útlimo, permite efectuar operaciones matemáticas básicas utilizando los siguientes símbolos:

- suma +
- Resto -
- Multiplicación *
- División /
- Módulo %

*Ejemplo:*

let a = 10;

let b = 5;

1. console.log(a + b);  Suma: 15
2. console.log(a - b);  Resta: 5
3. console.log(a * b);  Multiplicación: 50
4. console.log(a / b);  División: 2
5. console.log(a % b);  Módulo: 0

---
## ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?

Para declarar una variable en Javascript se debe untilizar palabras claves, las más comunes son:

- **var:** esta palabra clave es más antigua y su uso no es tan recomendado en JavaScript moderno debido a algunas particularidades en su comportamiento.

- **const:** se utiliza para declarar constantes, es decir, variables cuyo valor no puede cambiar una vez asignado.

- **let:** esta es la forma más moderna y recomendada para declarar variables. Las variables declaradas con let tienen un alcance de bloque, lo que significa que solo son accesibles dentro del bloque de código donde fueron declaradas.
