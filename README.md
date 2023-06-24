# Programa-1-Maximum-Draws

## Descripción 
Una persona se esta preparando para irse y necesita un par de calcetines a juego. Si existen varios colores de calcetines en el cajon cuantos calcetines deben quitarse para estar seguros de tener un par a juego?

_Tenemos una variable n que representa el color de cada par de calcetines._

## Solución
Suponemos que tenemos 3 pares de calcetines, sabiendo que cada par contiene dos calcetines, para asegurar que al menos uno tenfa par, debemos sacr un calcetin de cada par de calcetines y uno mas para que ese haga par con alguno de los antes ya obtenidos, es por eso que la funcion que hace falta es return n + 1 para poder completar el codigo a esto se tiene que modificar la linea de

FILE* fptr = fopen(getenv("OUTPUT_PATH"), "w");

Ya que el código trabaja con entradas que le proporciona la página misma por lo que debemos reemplazar con las siguientes líneas y adjuntar un archivo txt. con las entradas para poder recibir las salidas correspondientes.

El archivo txt contiene las salidas que se dan de ejemplo en la pagina hackerranks

## Instrucciones de ejecución
1. Compilar el programa como "gcc MaximumDraws.c"
2. El archivo de los datos de entrada (input1) deberan estar en la misma carpeta o dirección en donde se encuentre el programa en C.
3. Al terminar la ejecución se creará un archivo txt llamado "output1" dentro de la misma dirección del programa en C, el cuál deberá contener la salida esperada del programa.
