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

- START
- PRINT "Ingrese la cantidad de dolares que desea convertir a btc: "
- dolares <-- GET 
- // conseguimos el valor actual del bitcoin. le aplique un shortener al link para que no fuera tan largo
- valorBTCEnDolares <-- GET parseFloat(FROM(https://bit.ly/3j7DZhB))
- dolaresConvertido <-- dolares / valorBTCEnDolares
- PRINT "Su cantidad ingresada: " + dolares + "$ convertidad a bitcoins es: \n: " + dolaresConvertido + "BTC"
- END


# THURSDAY
- Solucion con for loop


`for(var i = 0; i < 101; i++) {
    if(i % 2 == 0) {
      console.log(i);
    }
 }`
  
- Solucion con while loop


` let contador = 0;
  while (contador < 101) {
    contador++;
    if(contador % 2 == 0)
      console.log(contador);
  }`
  
- Solucion con do while


` let contador = 0;
  do {
    contador++;
    if(contador % 2 == 0)
      console.log(contador);
  } while(contador < 101);`
  
# Bad Code 1

`var cond = false;

if ((cond = true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}`
- Posible solucion


`cond = false;
  if(cond) {
    console.log('The cond variable is true');
  } else {
    console.log('The cond variable is false');
  }`
  
# Bad Code 2
- Solucion para este codigo

` 
  var n = 100;
  if (n == 100) {
    console.log('This is a special number!');
  } else if (n < 1000 && (n % 10 == 0) && n != 100) {
    console.log('This number is almost special');
  } else {
    console.log('Just a regular number');
  }
  `
  
  # Solution to multiply en CODE WARS
  	![ Solution to multiply ]>
(<img width="1250" alt="multiply" src="https://user-images.githubusercontent.com/81724986/164128979-47bf3fd0-9948-4e4e-988e-388cb3fb96f9.png")
