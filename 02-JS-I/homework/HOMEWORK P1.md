 * Variables
 Una variable es un elemento que se emplea para almacenar y hacer referencia a otro valor, por ejemplo var a = 1, con lo que a va a valer
 1, desde aca en adelante. 
 Para declarar una variable se usa var; 
 var a = 1 
 a 
 1
 

 * Strings
 Es un dato de texto. siempre que algo este entre comillas simples o 
 dobles hace referencia a un bloque string.
 var colordepc = 'negra'
 con esto estariamos dicendole a la variable color de pc que es negra.

 * Funciones (argumentos, `return`)
 Una funcion son objetos invocables, es decir objetos que al ser llamados responden a un conjunto de procedimientos dictaminados por 
 variables. para invocar una funcion, primero se debe escribir la palabra function, esto le indica al ejecutador que lo que sigue es una funcion, seguido ira el nombre de esa funcion; 
 function SumarDosNumeros() {}
 Dentro de los parentesis iran los argumentos, y dentro de los corchetes iran los codigos para realizar dicha funcion.
 la funcion siempe debera retornar un valor. para ello se usa la sentencia return, la cual finaliza la ejecucion de la funcion y especifica un valor para ser resuelto.
 function SumarDosNumeros(a, b) {
    var suma = a + b
    return suma
 }
SumarDosNumeros(1, 5)
6

 * Declaraciones `if`
 Los statements son instrucciones que le damos al interprete para que realice una accion. 
 if es una conditional estatement:
 Especifica un bloque de codigo que se ejecuta tras una condicion en este caso if se refiere a si es cierto, entonces si una variable es 8 y decimos si la nota es mayor o igual a 5 devuelvenos una alerta que diga has aprovado;

 var nota = 8
 if (nota >=5) {
      alert ("has aprovado")
 } 
 esto nos devolveria en la pagina un alerta con un carte que dice has aprovado. por que la variable nota es mayor que 5 y en el codigo estamos indicando que si es mayor o igual a 5 nos devuelva esta alerta.

 * Valores booleanos (`true`, `false`)
 Los valores booleanos son unos tipos de datos que devuelven valores binarios, en este caso true o false. entonces 1 + 1 = 2 es true 1 + 1 = 3 es false.