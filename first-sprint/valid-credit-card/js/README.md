#validCreditCard
Crea una web que pida, por medio de un prompt(), el número de una tarjeta de crédito y confirme su validez según el algoritmo de Luhn.
Nota:
Tu código debe estar compuesto por una función llamada isValidCard
El usuario no debe poder ingresar un campo vacío


##PSEUDOCODIGO
1. Preguntar el número de la tarjeta por medio de un prompt ()
2. pasar los digitos recibidos a un array en orden inverso por medio de un split()
3. Agregar una función llamada isValidCard
4. Por medio de un for separar los números pocisionados como impares y multiplicarlos por 1
5. Por medio de un segundo for multiplicar por 2 los números en posiciones pares contando del número 1 al 4 y si el doble de éste número es mayor a 10 debemos sumar los digitos entre sí.
6. Por medio de un tercer for multiplicar por 2 los números en posiciones pares contando del número 5 al 9 y si el doble de éste número es mayor a 10 debemos sumar los digitos entre sí.
