Antes que nada, quiero aclarar que sé varias cosas de Javascript. 

Operadores de comparación (==, <=, >=, <, >, ===,!=) 

Operadores aritméticos (+, -, *, /, %, --, ++) 

Operadores lógicos (and: &&, or: ||, not: !) 

Condicional If, else If, else (si se cumple la condición, entonces se aplica lo indicado) 

Ejemplo:  

<P id=”parrafo”> </P> 

<Script>  

let a=20; 

If (a < 40) {  

document.getElementById(“parrafo”).innerHTML = “Si es menor  40”; 

}; 

else If (a==40) {  

document.getElementById(“parrafo”).innerHTML = “Si es igual que 40”; 

}; 

else {  

document.getElementById(“parrafo”).innerHTML = “No es menor que 40”; 

}; 

</Script> 

parseInt (numero) --- te cuenta los números como números reales, que se pueden sumar. 

Estructuras repetitivas while y for (te cuentan todos los elementos que cumplan la condición, hasta que haya alguno que no la cumpla) 

Ejemplo while: 

<ul id=”lista”> 

</ul> 

<script> 

var b=0; 

while (b < 5) {  

document.getElementById(“lista”).innerHTML = “<li>” + b “</li>”; 

b++; 

};  

</script> 

Esto me lo escribiría: 

0 1 2 3 4 

Ejemplo for: 

<ul id=”lista”> 

</ul> 

<script> 

for (var b=0; b < 5; b++) {  

document.getElementById(“lista”).innerHTML = “<li>” + b “</li>”; 

b++; 

};  

</script> 

Funciones ----- nombreDeLaFuncion(parametros) {código a ejecutar}; 

Eventos : onclick, onload, ondblclick, onmousemove, onchange, etc. (al colocar estos eventos, se produce lo que indican, por ejemplo, al utilizar onclick, cuando uno aprieta algo se activa la función correspondiente 

Ejemplo: 

<Input type=”text” value= “Escribir marca” id=”input”>  

<button onclick=”eleccion()”> Elegir </button> 

<script> 

function eleccion() { , 

var marca= document.getElementById(“input”).value; 

alert( “Elegiste la marca ” + marca); 

}; 

 </script> 

Vanilla.js 

querySelector(“#id”) -- reemplaza el getElementById 

AddEventListener() ---- en vez de colocar onclick en html, se utiliza el addeventlistener para directamente en javascript escuchar el evento (ejemplo escuchar el click) y ahí realizar la función 

Flexbox y mediaquery 

JQuery 

$(a).b(“c”) --- a es el elemento que quiero trabajar (ejemplo un input), b es el método que voy a utilizar (ejemplo html) y c es lo que quiero que haga (ejemplo, escribirme “hola”) 

html(), text(), val(), attr(), append(), prepend(), after(), before(), remove(), empty(), addclass(), removeclass(), toggleclass(), css(), each(), show(), hide(), toggle(), fadein(), , slidedown(), animate(). 

Principio el documento escribir $(document).ready(function() {  todo el código jquery}; 

Cuando todo esté listo, ahí recién me va a comenzar a renderizar. 

Array, objetos y Json (tomar datos de un lugar externo) 

Array:  

Nombre= [ '01', '02', '03',... ]; 

Objeto: 

Nombre = [ { 'parametro 1': 'elemento 1 ', 'parametro 2': 'item 1 ' }, { 'parametro 1': 'elemento 2 ', 'parametro 2': 'item 2 ' }, ... ]; 

Json:  

Fetch(“pagina”) 

then(response =>response.json()) 

.then(json=>{ 

Lo que quiero realizar con la información 

}) 

Sé node.js y React, pero es muy precario 
