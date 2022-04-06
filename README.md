# Lenguajes de programacion compilados e interpretados
- Compilados: 
  Los lenguajes compilados son todos aquellos en los que un compilador, osea un programa extra que lee   nuestro programa que escribimos y lo traduce a un lenguaje que la computadora puede leer, ese           lenguaje es el lenguaje de maquina, binario, o 1s y 0s (por decirlo de varias maneras). La ventaja de   los lenguajes compilados es que tienen mayor accesibilidad al manejo del hardware de la maquina, tal   como la memoria, cpu, discos duros, etc. Si nosotros escribimos codigo nuevo... tenemos que volver a   compilarlo para que nuestra computadora puede tener y leer esas nuevas instrucciones. Algunos           lenguajes son: Java, Go, C, C++, Rust
  
- Interpretados:
  Los lenguajes interpretados son los que se ejecutan linea por linea, esto se le llama JIT o Just in     time. Este tipo de de lenguajes son los que puedes escribir y cuando quieras puede actualizar y el 
  interprete va traduciendo tu codigo a lenguaje de maquina para que se pueda ejecutar.
  Algunos Lenguajes: JavaScript, php, python.
  
# Java es lenguaje compilado o interpretado?
- Java es ambas cosas, compilado por que compila/traduce el programa escrito por nosotros a bytecode, que despues este bytecode es interpretado. esto es gracias a la JVM o la maquina virtual de Java 

# Ejercicio de pseudocodigo

1. pedir la cantidad de dolares a convertir a btc
2. saber el valor del dolares a btc
3. hacer calculo de conversion
4. imprimir el resultado

START
PRINT "Ingrese la cantidad de dolares que desea convertir a btc: "
dolares <-- GET 
// conseguimos el valor actual del bitcoin. le aplique un shortener al link para que no fuera tan largo
valorBTCEnDolares <-- GET parseFloat(https://bit.ly/3j7DZhB)
dolaresConvertido <-- dolares / valorBTCEnDolares
PRINT "Su cantidad ingresada: " + dolares + "$ convertidad a bitcoins es: \n: " + dolaresConvertido + "BTC"
END



  
