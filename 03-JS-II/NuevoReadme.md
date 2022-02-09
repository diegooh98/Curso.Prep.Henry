**QUE ES UN FOR?**

1. `los "for" son blucles que se recorren dentro de ellos para poder buscar o mostrar algo, un blucle es algo que se repite una y otra vez de manera exactamente igual, hasta que pongamos alguna condicion para que se detenga`

un bluce 'for' se compone de la siguiente manera:
.primero ponemos la palabra for
.luego abrimos y cerramos parentesis ()
.despues dentro de los parentesis necesitaremos iniciar una variable la cual va hacer el recorrido dentro
del bluce for. variable "i"
.por ultimo abrimos y cerramos llaves {}

y quedaria de esta manera:

for(var i = 0; i < 20; i++){

}
como pueden ver la variable "i", inicio en 0, luego se separa por un punto y coma;
despues la variable "i" le vamos a decir que sea menor al numero 20 y separamos con el punto y coma;
por ultimo le vamos a decir que la variable "i" sea incrementable colocando el i++

dicho esto lo que estamos haciendo en este blucle es decirle a la varible "i" que recorra los numeros empezando desde el cero hasta llegar al 19, ya que la varible "i" tiene que ser menor al numero 20     


//////////////////////////////////////////////////////////////////
**QUE SON LOS OPERADORES LOGICOS**  `&&`, `||`, `!`

2. Los operadores logicos sirven para preguntar  o saber si alguna expresion es verdadero o falso o si alguna es diferente.

&& este simbolo significa " y "
|| este simbolo signfica  " o "
!  este simbolo signfica  " " no " O DIFERENTE

**EJEMPLO 1:**

UTILIZAREMOS ESTE &&  simbolo significa " y "

 tengo dos problemas matematicos y necesito saber si son verdaderas

 . el numero 100 es menor a 200

 " y " si el numero 200 es igual a 200

entonces tengo que utilizar una condicion if() para saberlo

if(100 < 200 && 200 === 200){
    return true;
}

**EJEMPLO 2:**

UTILIZAREMOS ESTE || este simbolo signfica  " o "

.necesito saber si es falso que el numero 100 es mayor a 200

" o " si el numero 200 es menor a 100

entonces tengo que utilizar una condicion if() para saberlo

if(100 > 200 || 200 < 100){
    return false;
}

**EJEMPLO 3:**

UTILIZAREMOS ESTE !  este simbolo signfica  " no " O DIFERENTE

.necesitaremos que lo que yo ponga falso sea verdadero
y lo que coleque verdadero sea falso

entonces tengo que utilizar una condicion if() para saberlo

if (!false) {
    console.log('El "!" devolverá  verdadero "true');
}

if (!true) {
    console.log('El "!" devolverá  falso "false');
}