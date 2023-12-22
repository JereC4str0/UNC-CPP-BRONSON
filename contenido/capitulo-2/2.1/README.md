# 2.1 Introduccion a C++ 

Los programas cuyas estructuras consisten en segmentos interrelacionados, organizados en un orden logico y facilmente comprensible para formar una unidad integrada y completa, se conocen como **programas modulares**

Los segmentos mas pequeños usados para construir un programa modular se conocen como **modulos**, cada modulo realiza una tarea en específica, es un subprograma pequeño en si mismo
<br>

<div align="center">
  <img src="https://i.postimg.cc/NM565T9b/imagen.png">
</div>

<br>
Los modulos pueden ser clases o funciones, una funcion es como una maquina pequeña que transforma los datos que recibe en un producto terminado.

<br>

<div align="center">
  <img src="https://i.postimg.cc/6QN67N8P/imagen.png">
</div>

<br>

La clase es una unidad que contiene tanto datos como funciones apropiadas para manipular los datos.
una clase encapsula tanto datos como uno o mas conjuntos de operaciones.

puede considerarse como una pequeña fabrica que contiene materia prima(los datos) y maquinas (las funciones)

Los nombres admitidos para funciones y clases se denominan **identificadores**, pueden formase por cualquier combinacion de letras, digitos o subrayados
seleccionado por las siguientes reglas: 

<br>

<div align="center">
  <img src="https://i.postimg.cc/28Yt2PT4/imagen.png">
</div>

<br>

<div align="center">
  <img src="https://i.postimg.cc/nzDHY62y/imagen.png">
</div>

<br>

+ El nombre de la funcion siempre debe ser seguido por parentesis
+ C++ es un lenguaje **sensible al uso de mayusculas y minusculas**

# La funcion main()
Cada programa C++ debe tener una y solo una funcion llamada main() o **funcion controladora**, porque controla, o indica, a los modulos la secuencia en que tienen que ejecutarse

<div align="center">
  <img src="https://i.postimg.cc/dQSGHdqw/imagen.png">
</div>

La primera linea *int main ()*, se conoce como **linea de encabezado de la funcion**.
Una linea de encabezado contiene tres fragmentos de informacion

1. Que tipo de dato, si hay alguno, es devuelto por la funcion
2. El nombre de la funcion
3. Que tipo de dato, si hay alguno, es enviado por la funcion

+ Los datos transmitidos a una funcion al momento de ejecutarla se llaman **argumentos** de la funcion
+ Las llaves {y} determinan el principio y el fin del cuerpo de la funcion y encierran las instrucciones que la componen.
+ Cada instruccion dentro de la funcion debe terminar con un punto y coma (;) !!

<div align="center">
  <img src="https://i.postimg.cc/KzmpcTVR/imagen.png">
</div>
   

# El objeto cout
Console OUTput, es un objeto de salida que envia datos introducidos en el al dispositivo estandar de salida
> el objeto cout se crea de manera formal a partir de la clase ostream

### Programa 2.1
```cpp
#include <iostream>
using namespace std;

int main()
{
  cout << "Hola mundo!";

return 0;
}
```
+ La primera linea del programa ```#include <iostream>``` es un comando preprocesador que utiliza la palabra reservada include.

+ Los comandos preprocesadores comienzan con un signo de numero (#) y ejecutan alguna accion antes que el compilador traduzca el programa.

+ El comando preprocesador ```include ``` causa que el contenido del archivo invocado, sea insertado en donde el comando ``` #include``` aparezca.
``` iostream``` es una parte de la biblioteca estandar que contiene clases nombradas ``` istream``` y ``` ostream``` estas dos clases proporcionan las declaraciones de datos y metodos utilizados para la entrada y salida de datos

+ ```iostream``` se conoce como **archivo de encabezado** debido a que siempre se coloca una referencia a el en la parte superior, o cabeza, de un programa C++

+ Los comandos preprocesadores no terminan con punto y coma (;)

+ La instruccion ```using namespace std;``` le dice al compilador donde buscar para encontrar los archivos de encabezado en ausencia de cualquier designacion explicita adicional

+  Para ```cout ```, la accion es ensamblar datos para mostrar la salida.

### Programa 2.2 
```cpp 
#include <iostream>
using namespace std;
int main()
{
  cout << "Computadoras, computadoras por todos lados";
  cout << "\n tan lejos como pueda llegar C"

return 0;
}
```
+ Los dos caracteres \ y n, cuando se usan juntos, se llaman secuencia de escape para una linea nueva. Le indican a ``` cout ``` que envie instrucciones al dispositivo de salida para iniciar una linea nueva.

### Programa 3
```cpp 
#include <iostream>
using namespace std;
int main()
{
  cout << "Computadoras por todos lados \n tan lejos como \n pueda llegar C";+
return 0;
}
```
