# Jscript_exercise
// Ejercisio del capitulo 2
//Primer ejercisio:
for(var numero = "#"; numero.length <= 7; numero += "#")
	console.log(numero);
//Segundo ejercisio:
/* Este estuve mas o menos. Busque el resultado, pero
ya lo entendi. Aunque necesito mas practica! */
for( var numero = 1; numero <= 10; numero++) {
  var josuePut=""; 
  if (numero % 1 ==0)
     josuePut += "Bazzi";
  if (numero % 1 ==0)
    josuePut += "nga!!";
  console.log(josuePut || numero);
}
// Tercer ejercisio:
/* Este lo hice pero me salia mal. So, busque el resultado
y trate de entenderlo pero necesito pratica. Help me!. */
var medida = 8;

var tabla = "";
for(x = 0; x < medida; x++) {
  for( y = 0; y < medida; y++) {
    if ((x + y) % 2 ==0)
      tabla +=" ";
    else tabla +=  "#";
  }
  tabla += "\n";
} 
console.log(tabla);
