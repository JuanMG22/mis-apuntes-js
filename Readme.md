# <img src="https://media1.giphy.com/media/1ynCEtlgMPAeNAqdnu/giphy.gif?cid=6c09b952yzbm90tqswd3axzd1sg2xawydevos6nzr44imwhs&rid=giphy.gif&ct=s" width="30px"> Mis Apuntes JavaScript


### 1. Closure: 
Es una función autoejecutada que devuelve determinadas variables o funciones, de forma similar a una class y te permite tener variables privadas

### 2. Hoisting: 
<img src="https://c.tenor.com/BRANURS5Lh8AAAAM/balloon-red.gif" width="100px" >


Una estricta definición de hoisting sugiere que las declaraciones de variables y funciones son físicamente movidas al comienzo del código, pero esto no es lo que ocurre en realidad. Lo que sucede es que las declaraciones de variables y funciones son asignadas en memoria durante la fase de compilación, pero quedan exactamente en dónde las has escrito en el código.


|                                                        	   | Hoisting ( se eleva )     |
| ---------------------------------------------------------------- | ------------------------- |
| var			 		          	           | Declaración               |
| function			 		                   | completo    	       |
| import					                   | completo      	       |
| class					                           | No        		       |




	function nombreDelGato(nombre) {
     console.log("El nombre de mi gato es " + nombre);
    }

    nombreDelGato("Maurizzio");
    /*
     El resultado del código es: "El nombre de mi gato es Maurizzio"
    */
