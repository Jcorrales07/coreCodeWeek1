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
  
  # Solution to multiply on CODE WARS
  	![ Solution to multiply ]>
(<img width="1250" alt="multiply" src="https://user-images.githubusercontent.com/81724986/164128979-47bf3fd0-9948-4e4e-988e-388cb3fb96f9.png")
      
 # Solution to ASCII on CODE WARS
    ![Solution to ASCII]
(<img width="1253" alt="ASCIIExercise" src="https://user-images.githubusercontent.com/81724986/164129783-3a192c0b-1bd6-40d9-a3c4-8e493594ee2c.png">)
      
 # Solution to ASCII value to String on CODE WARS
    ![Solution to ASCII value to String]
(<img width="1253" alt="ASCII2" src="https://user-images.githubusercontent.com/81724986/164131088-f6594d0e-0f86-466f-8025-6aea2bab0667.png">)   

 # Solution of number to binary on CODE WARS
    ![Solution of number to binary]
(<img width="1246" alt="NumeroABinario" src="https://user-images.githubusercontent.com/81724986/164133155-8f47b7fe-ec10-4853-9569-f3f6ba795ff4.png">)   

 # Solution to student final grade on CODE WARS
    ![Solution to student final grade]
(<img width="1250" alt="studentFinalGrade" src="https://user-images.githubusercontent.com/81724986/164134456-e70c463d-de0d-4029-9416-b24c5645ba47.png">)   

# Solution Holiday VIII - Duty Free
    ![Solution Holiday VIII - Duty Free]
(<img width="1250" alt="duty" src="https://user-images.githubusercontent.com/81724986/164576220-59769409-9eeb-4de2-aac9-e2d7ff46cbcb.png">)
 
 # Solution Twice as old
    ![Solution Twice as old]
(<img width="1253" alt="TwiceAsOld" src="https://user-images.githubusercontent.com/81724986/164576798-1b612a4d-e8d0-4b5b-bb43-43e58402111c.png">)
  
  # Solution Valid Spacing
    ![Solution Valid Spacing]
(<img width="1253" alt="TwiceAsOld" src="https://user-images.githubusercontent.com/81724986/164579876-146accbf-3882-40ae-b473-2338b4f971bf.png">)
  
  # Solution Fake Binary
    ![Solution Fake Binary]
(<img width="1250" alt="FakeBinary" src="https://user-images.githubusercontent.com/81724986/164582004-7b895bcd-cb3e-403c-a13d-de49caca81bb.png">)

  # Solution Remove all exclamation marks from the end of the sentence
    ![Solution Remove all exclamation marks from the end of the sentence]
(<img width="1253" alt="removing !" src="https://user-images.githubusercontent.com/81724986/165176764-52da6c43-e417-4d7e-8172-960643acb09d.png">)

  # Solution Vowel remover
    ![Solution Vowel remover]
(<img width="1253" alt="removing !" src="https://user-images.githubusercontent.com/81724986/165180648-04ce62d3-85ed-4fd1-bfa8-27352ccc7c6d.png">)

# Solution Rock Paper Scissors!
    ![Solution Rock Paper Scissors!]
(<img width="1252" alt="Rock Paper Scissors!" src="https://user-images.githubusercontent.com/81724986/165183096-37698b64-ca3c-4140-a9f5-b69f0182b77e.png">)

# Solution Persistent Bugger
# I wanted to implement the array functions but i got stucked :c 
    ![Solution Persistent Bugger]
(<img width="1251" alt="PersistentBugger" src="https://user-images.githubusercontent.com/81724986/165188170-cc62b0a5-0470-40d0-b57f-df7ac84f2021.png">)



