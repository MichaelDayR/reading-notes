# READ06 PREGUNTAS

## ¿Qué son las variables en JavaScript?
En JavaScript, las variables son contenedores que almacenan datos. Son una parte fundamental del lenguaje y se utilizan para:

- *Almacenar valores que cambian durante la ejecución del programa.*
-  *Referirse a esos valores de forma fácil y comprensible.*
- *Organizar el código y hacerlo más legible.*
- *Declarar variables*

Para declarar una variable en JavaScript, se utiliza la palabra clave **var, let o const.** A continuación, se indica el nombre de la variable y, opcionalmente, se le asigna un valor.

Ejemplo:

JavaScript
var nombre = "Juan";
let edad = 25;
const PI = 3.14159;
Use code with caution.

En este ejemplo, se han declarado tres variables:

nombre: una variable de tipo string que almacena el nombre "Juan".
edad: una variable de tipo number que almacena el valor 25.
PI: una variable de tipo number que almacena el valor de la constante pi.

### Tipos de variables

JavaScript tiene varios tipos de variables, que se pueden clasificar en dos categorías:

- Tipos de datos primitivos: son los tipos de datos básicos que no se pueden descomponer en otros tipos. Los tipos de datos primitivos en JavaScript son:

1. number: números decimales o enteros.
2. string: cadenas de texto.
3. boolean: valores true o false.
4. null: un valor especial que indica la ausencia de un valor.
5. undefined: un valor especial que indica que una variable no ha sido inicializada.
6. Tipos de datos compuestos: son tipos de datos que se pueden descomponer en otros tipos. Los tipos de datos compuestos en JavaScript son:
7. array: un conjunto ordenado de valores.
8. object: una colección de propiedades que pueden ser de diferentes tipos.

### Alcance de las variables

*El alcance de una variable determina en qué partes del código es visible y accesible*

Existen tres tipos de alcance:

1. Alcance global: las variables declaradas con la palabra clave var tienen un alcance global, lo que significa que son visibles en todo el código.
2. Alcance de bloque: las variables declaradas con la palabra clave let o const tienen un alcance de bloque, lo que significa que solo son visibles dentro del bloque en el que se declaran.
3. Alcance de función: las variables declaradas como parámetros de una función solo son visibles dentro de la función.

### Buenas prácticas para las variables

*Es importante seguir algunas buenas prácticas al declarar y utilizar variables en JavaScript:*

- Utilizar nombres descriptivos: el nombre de la variable debe indicar claramente el valor que almacena.
- Evitar usar palabras clave como nombres de variables: no se deben usar palabras clave reservadas del lenguaje como nombres de variables.
- Declarar las variables al principio del código: es recomendable declarar las variables al principio del bloque en el que se van a utilizar.
- Utilizar el tipo de dato adecuado: se debe elegir el tipo de dato adecuado para cada variable.
- Documentar las variables: es útil agregar comentarios al código para explicar el significado de las variables.

## ¿Qué significa “declarar” una variable?

Declarar una variable en programación significa **reservar un espacio en la memoria de la computadora para almacenar un valor.** Este espacio se identifica con un nombre único, que es la variable en sí. La declaración también especifica el tipo de dato que se va a almacenar en la variable, como un número, una cadena de texto o un valor booleano.

Al declarar una variable, se indica al compilador o intérprete del lenguaje de programación:

- El nombre de la variable: cómo se va a referir al valor almacenado en la memoria.
- El tipo de dato: qué tipo de información se va a almacenar.
- El tamaño del espacio en memoria: cuánto espacio se necesita para almacenar el valor.

**La declaración de variables es una parte fundamental de la programación, ya que permite:**
- Organizar el código: las variables ayudan a que el código sea más legible y comprensible.
- Almacenar datos: las variables permiten guardar valores que cambian durante la ejecución del programa.
- Reutilizar datos: las variables permiten usar el mismo valor en diferentes partes del código.

Existen diferentes formas de declarar variables, dependiendo del lenguaje de programación que se esté utilizando. En JavaScript, por ejemplo, se pueden usar las palabras clave var, let o const.

## ¿Qué es un operador de “asignación” y qué hace?

Un operador de asignación en programación es un símbolo que se utiliza para asignar un valor a una variable. En otras palabras, se utiliza para decirle a la computadora que guarde un valor en un espacio de memoria específico, que se identifica por el nombre de la variable.

El operador de asignación más común es el símbolo igual (=).

 Por ejemplo:

---
JavaScript

var nombre = "Juan"; // Asigna el valor "Juan" a la variable "nombre".
let edad = 25; // Asigna el valor 25 a la variable "edad".
const PI = 3.14159; // Asigna el valor de la constante pi a la variable "PI".
Use code with caution.

En estos ejemplos, el operador = asigna los valores "Juan", 25 y el valor de pi a las variables nombre, edad y PI, respectivamente.

Además del operador =, existen otros operadores de asignación en JavaScript, como:

- +=: Suma un valor a la variable y luego le asigna el resultado.
- -=: Resta un valor a la variable y luego le asigna el resultado.
- *=: Multiplica la variable por un valor y luego le asigna el resultado.
- /=: Divide la variable por un valor y luego le asigna el resultado.

Estos operadores de asignación compuesta son útiles para realizar operaciones matemáticas sobre variables y luego asignar el resultado a la misma variable. Por ejemplo:

---
JavaScript
var numero = 10;

numero += 5; // Suma 5 a la variable "numero" y luego le asigna el resultado (15).

numero *= 2; // Multiplica la variable "numero" por 2 y luego le asigna el resultado (30).
Use code with caution.

En resumen, los operadores de asignación son una herramienta fundamental en programación para:

Almacenar datos en variables.
Modificar el valor de las variables.
Realizar operaciones matemáticas sobre variables.
## ¿Cómo se llama la información recibida del usuario?

La información recibida del usuario se llama entrada de usuario o datos de entrada.

**Tipos de entrada de usuario:**

- Entrada de texto: El usuario introduce texto a través de un teclado, como al escribir en un campo de texto o un cuadro de diálogo.
- Entrada de selección: El usuario selecciona una opción de una lista, como al elegir un elemento de un menú desplegable o una casilla de verificación.
- Entrada de clic: El usuario hace clic en un botón o en un elemento de la pantalla.
- Entrada de voz: El usuario habla en un micrófono y el dispositivo convierte su voz en texto.
- Entrada táctil: El usuario toca la pantalla de un dispositivo móvil.

**Uso de la entrada de usuario:**

*La entrada de usuario se utiliza para:*

- Controlar el comportamiento de un programa o aplicación.
- Proporcionar información al programa o aplicación.
- Interactuar con el programa o aplicación.
