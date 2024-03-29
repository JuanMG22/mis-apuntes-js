# <img src="https://media1.giphy.com/media/1ynCEtlgMPAeNAqdnu/giphy.gif?cid=6c09b952yzbm90tqswd3axzd1sg2xawydevos6nzr44imwhs&rid=giphy.gif&ct=s" width="30"> Mis Apuntes JavaScript


## 1. Closure: 
Es una función autoejecutada que devuelve determinadas variables o funciones, de forma similar a una class y te permite tener variables privadas

Ejemplo de Closure:

	function iniciar() {
	  var nombre = "Mozilla";  // La variable nombre es una variable local creada por iniciar.
	  function mostrarNombre() {  // La función mostrarNombre es una función interna, una clausura.
	    alert(nombre);  // Usa una variable declarada en la función externa.
	  }
	  mostrarNombre();
	}
	iniciar();  


## 2. Hoisting: 
<img src="https://c.tenor.com/BRANURS5Lh8AAAAM/balloon-red.gif" width="100px" >


Una estricta definición de hoisting sugiere que las declaraciones de variables y funciones son físicamente movidas al comienzo del código, pero esto no es lo que ocurre en realidad. Lo que sucede es que las declaraciones de variables y funciones son asignadas en memoria durante la fase de compilación, pero quedan exactamente en dónde las has escrito en el código.



Ejemplo de cómo actua el Hoisting con una función del tipo function:

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

	let foo = 42;    // foo ahora es un número
	foo     = 'bar'; // foo ahora es un string
	foo     = true;  // foo ahora es un booleano


### Estructuras y tipos de datos
El último estándar ECMAScript define nueve tipos:

|                    		                                   | Tipo de dato   	       |
| ---------------------------------------------------------------- | ------------------------- |
| Undefined			 		                   | Primitivo                 |
| Boolean			 		                   | Primitivo    	       |
| Number					                   | Primitivo      	       |
| String				                           | Primitivo        	       |
| Bigint				                           | Primitivo        	       |
| Symbol				                           | Primitivo        	       |
| Null				                                   | Primitivo        	       |
| Object				                           | Objeto        	       |
| Function				                           | Objeto        	       |
