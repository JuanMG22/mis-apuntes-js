# <img src="https://media1.giphy.com/media/1ynCEtlgMPAeNAqdnu/giphy.gif?cid=6c09b952yzbm90tqswd3axzd1sg2xawydevos6nzr44imwhs&rid=giphy.gif&ct=s" width="30px"> Mis Apuntes JavaScript


## 1. Closure: 
Es una función autoejecutada que devuelve determinadas variables o funciones, de forma similar a una class y te permite tener variables privadas

## 2. Hoisting: 
<img src="https://c.tenor.com/BRANURS5Lh8AAAAM/balloon-red.gif" width="100px" >


Una estricta definición de hoisting sugiere que las declaraciones de variables y funciones son físicamente movidas al comienzo del código, pero esto no es lo que ocurre en realidad. Lo que sucede es que las declaraciones de variables y funciones son asignadas en memoria durante la fase de compilación, pero quedan exactamente en dónde las has escrito en el código.



Ej:

	function nombreDelGato(nombre) {
     console.log("El nombre de mi gato es " + nombre);
    }

    nombreDelGato("Maurizzio");
    /*
     El resultado del código es: "El nombre de mi gato es Maurizzio"
    */


En la siguiente tabla se muestra como actua el hoisting en cada caso, y qué es lo que "se eleva" en cada uno

|                                                        	   | Hoisting (se eleva)       |
| ---------------------------------------------------------------- | ------------------------- |
| var			 		          	           | declaración               |
| function			 		                   | completo    	       |
| import					                   | completo      	       |
| class					                           | No        		       |


## 3. Tipos de datos y estructuras en JavaScript
Todos los lenguajes de programación tienen estructuras de datos integradas, pero estas a menudo difieren de un lenguaje a otro. Este artículo intenta enumerar las estructuras de datos integradas disponibles en JavaScript y las propiedades que tienen. Estas se pueden utilizar para construir otras estructuras de datos. Siempre que es posible, se hacen comparaciones con otros lenguajes.

### Tipado dinámico
JavaScript es un lenguaje débilmente tipado y dinámico. Las variables en JavaScript no están asociadas directamente con ningún tipo de valor en particular, y a cualquier variable se le puede asignar (y reasignar) valores de todos los tipos
