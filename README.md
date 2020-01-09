# Tarea_3

ListaDeNumeros <- list(2,5,6,2,1,5,6,10,11,20,15) listaDeNumeros[5]

#EJERCICIO 1# 

Al remplazar el valor 5 por un 0 no arroja ningun valor, ya que no hay un valor asociado a esa posición. 
Al remplazar por un valor mayor a los elementos que estan en la lista, esta arroja "NULL" ya que la lista no posee esa cantidad de elementos.
Al remplazar el valor por un numero negativo, por ejemplo [-7] se elimina el elemento posicionado en el puesto 7.


#EJERCICIO 2# 

Al usar unlist, solo se entrega el valor, no así su posición. 
Ejemplo if(listaDeNumeros[5]+1>0){ print("se cumple") } if(unlist(listaDeNumeros[5])+1>0){ print("se cumple") }
Trajar en modo list, arroja un error, ya que no se pueden realizar operaciones con los numeros de la lista. 
Al trabajar con el modo unlist si me permite trabajar con los numeros de la lista.


#EJERCICIO 3# 

¿Qué pasa cuando realizamos la siguiente acción: listaDeNumeros[5] <- 12 ?
Al insertar esta formula me cambia el valor ubicado en la posicion 5. (cambia el 1 por un 12)


#EJERCICIO 4#

La funcion length arroja la longitud de los datos de la lista.


#EJERCICIO 5#

Al aplicar un valor inicial (20) y final (5) me arroja una lista desde el valor incical seleccionado hasta el valor final seleccionado, es decir desde 20 hasta 5. 
En caso contrario cuando se invierte los valores iniciales y finales, el listado que arroja tambien se invierte, es decir, desde 5 hasta 20.
Al cambiar el valor final por length(listaDeNumeros) me arroja un listado desde el valor incial ya fijado hasta el numero total de datos de la lista, es decir, desde el 5 hasta el 11.
En el caso de que ambos valores sean iguales, la secuencia arroja solo un numero, es decir, el numnero fijado. para este caso el numero 5.


#EJERCICIO 6# 

El comando for lo que establece es una secuencia del 1 al 100: leyendose de la siguiente forma: [1] "cuento 1 misisipis" hasta [1] "cuento 100 misisipis".


#EJERCICIO 7# 

Al cambiar i por listaDeNumeros, se crea una secuencia correspondiente con los valores de la lista.


#EJERCICIO 8#

El insertar los condicionales visto en clases a la formula, ente caso la condicion par e impar a la listaDeNumeros, permite conocer cuales de los valores de la lista son pares y cuales impares.


#EJERCICIO 9#

Para este caso el ganador es SI, ya que el total de votaciones para "Si" es mayor o igual al 30%.


#EJERCICIO 10#

Una función es un grupo de instrucciones que toma valores de entradas para generar un resultado. Por ejemplo, si se crea una función que sume dos elementos, a y b, de la siguiente manera:
Suma<-function(a,b){ a+b }
Para luego ejecutar lo siguiente en R:

Suma(6,4)

¿Qué resultado genera? Pruébelo con operaciones resta,multiplicación, división.
El resultado es [1] 10, la resta da [1] 2, la multiplicacion [1] 24 y la division [1] 1.5.


#Ejercicio 11#

D_areas<-function(Hg,Lg,Hp,Lp){ (HgLg)-(HpLp) } #Datos: Hg=altura del rectangulo grande, Lg=largo del rectangulo grande, Hp=altura del rectangulo pequeño, Lp=largo del rectangulo pequeño
-Circulo- solo cambia la formula
Datos r1= radio del circulo grande, r2= radio del circulo pequeño T_areas<-function(r1,r2,pi){ (pir1^2)-(pir2^2) }
Supongamos r1=8 y r2=3
Obteniendo: [1] 172.788


#Ejercicio optativo#

El loop "for" se utiliza cuando se conoce la iteracion que se va a ocupar. En una lista o un rango nos facilita recabar solo lo que necesitamos, ayuda a llevar un orden al operar con rangos y listas.