# Ejercicio Algoritmos

## 1. Hola Mundo
Algoritmo hola_mundo
	Escribir "Hola mundo"
FinAlgoritmo

Prueba de escritorio: 

"Hola mundo"

## 2. A partir de un número ingresado diga si es mayor, menor o igual a 9.

Algoritmo MayoresIgualesMenoresA9 (INICIO)
	N<-0
	Escribir "Escribir el numero"
	Leer N
	Si N Es Igual A 9 Entonces
		Escribir "El numero es igual a 9"
	Si no
		Si N Es Mayor Que 9 Entonces
			Escribir "El numero es mayor a 9"
		Si no
			Escribir "El numero es menor a 9"
		Fin Si
	Fin Si
FinAlgoritmo (FIN)

Entrada: N
Salidas: 3, Escribir..
El paso 2 sirve para inicializar la variable N

Comprobación N: 0
Escribir: "Escribir el numero" (entonces escribimos un numero que elegimos, p.ej. el 6)
N: 6
saltamos paso 5 porque no cumple la condición
pasamos al paso 7
pasamos al paso 8
como no cumple la condicion, pasamos al 10. cumple la condicion y se escribe "El numero es menor a 9"
el paso 12 pone fin a lo que empieza en 8
el paso 13 pone fin a lo que empieza en 5
paso 14 pone fin al algoritmo completo

## 3. A partir de un número ingresado diga si el mismo es par o impar.

Algoritmo ParidadNumeros
	Leer nro
	Si (nro mod 2) = 0 entonces
		Escribir "es par"
	Sino
		Escribir "es impar"
	Fin Si
FinAlgoritmo

las palabras reservadas del algortimo son: Leer, si, sino, Escribir, Fin Si, entonces, FinAlgoritmo, =

Comprobación:
nro: 7
mod: es el resto de la división. como el resto no es 0, no cumple la condicion y salta a la linea 5. pasa a la 6 y escribe 'es impar'
linea 7 pone fin a lo que empieza en la linea3
linea 8 pone fin al algoritmo

## 4. ingresar dos números y devuelva el resultado de la suma entre ambos.

```
Algoritmo SumaDosNumeros
    Num1<-0
    Num2<-0
    Escribir "Escribir el numero 1"
    	Leer Num1
    Escribir "Escribir el numero 2"
    	Leer Num2
    	Rta<-Num1+Num2
    Escribir "El resultado es:" Rta
FinAlgoritmo
```
```
Comprobacion num1: 0
num2: 0
aparece en pantalla: "Escribir el numero 1"
linea 5-> num1: 7
aparece en pantalla: "Escribir el numero 2"
linea 7-> num2: 3
linea 8-> se asigna a la variable Rta, la suma entre num1 y num2
Rta: 10
linea 9-> escribe: El resultado es 10
linea 10 finaliza el algoritmo
```

## 5. Sumar todos los números pares entre 2 y 100.


Algoritmo SumaDePares
	suma <- 0
	nro <- 2
	Mientras nro<=100 hacer
		si nro mod 2 = 0 Entonces
			suma= suma+nro			
		FinSi
		nro=nro+1
	FinMientras
	Escribir "la suma de los pares entre 2 y 100 es " suma
FinAlgoritmo

 Prueba de escritorio
linea 2-> sum:0
linea 3-> nro: 2
linea 4-> condicion, se repite el bucle mientras que nro sea menor o igual a 100
linea 5-> si el resto de dividir el nro en 2 es 0 (es decir, si el numero es par)
linea 6-> se suma el numero a la suma global. sum: 2
linea 7-> fin de lo que empieza en 5
linea 8 -> nro: 3
linea 9-> como se sigue cumpliendo la condicion, vuelve a 4. se repite hasta que nro = 100. entonces se acaba el bucle y pasa a 10
linea 10 -> escribe 'la suma de los pares entre 2 y 100 es ...'

Algoritmo mejorado