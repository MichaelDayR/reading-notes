# READ07

## ¿Qué es “Control Flow” (Control de Flujo)?

El codigo se lee de manera lineal a menos de que tengamos alguna función que determine lo contrario. Con el control de flujo vamos a buscar organizar la manera en la que trabajamos el codigo, para asî determinar qué partes de nuestro código queremos ejecutar y en qué momento.


## ¿Qué es una “function” (Función) de JavaScript?

Una función en JavaScript es un bloque de código reutilizable que realiza una tarea específica. Se puede pensar en ella como una receta que define los pasos para lograr un resultado.

## ¿Qué significa “invoke” o “call” en una función?

En JavaScript, los términos "invocar" y "llamar" a una función se usan indistintamente. Ambos significan ejecutar el código definido dentro de la función.

**Aquí te explico la idea:**

- Función: 

*Piensa en una función como una receta con pasos específicos. Define qué se debe hacer para lograr un resultado.*

- Invocar o llamar: 

*Cuando invocas o llamas a una función, es como seguir la receta. Proporcionas los ingredientes necesarios (parámetros) y obtienes el resultado final (valor de retorno, si existe).*

## ¿Para qué sirven los paréntesis () cuando defines una función?

Los paréntesis en las funciones de JavaScript tienen dos usos principales:

1. Agrupar argumentos:

Los paréntesis se utilizan para contener los valores que se pasan a la función como argumentos.
Estos valores se separan por comas dentro de los paréntesis.
Ejemplo:

>JavaScript
function sumar(a, b) {
  return a + b;
}

const resultado = sumar(2, 3); // Se pasan los argumentos 2 y 3 a la función
console.log(resultado); // Salida: 5
Use code with caution.

**2. Indicar el final de la definición de la función:**

En JavaScript, las funciones se definen utilizando la palabra clave function.
Los paréntesis se colocan después del nombre de la función y antes del bloque de código que define su comportamiento.
Ejemplo:

> JavaScript
function saludar() {
  console.log("¡Hola!");
}

saludar(); // Se ejecuta la función
Use code with caution.

En este caso, la función saludar no tiene argumentos, pero los paréntesis siguen siendo necesarios para indicar el final de la definición.
