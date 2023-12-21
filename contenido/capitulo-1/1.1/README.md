# Introduccion a la programacíon

## Programa de computadora 
Un **programa** de computadora es un conjunto de instrucciones usado para operar una computadora con el fin de producir un resultado en especifico.
Otro termino para programa o conjunto de programas de software

El proceso de escribir un progreso un programa, o un software, se llama programacion mientras al conjunto que puede usarse para construir un programa se llama **lenguaje de programacion**


# Lenguaje de maquina 
los unicos programas que pueden usarse en realidad para operar en una computadora son los **programas en lenguaje de maquina**, los **programas ejecutables** consisten en una secuencia de instrucciones compuestas por numeros binarios como:

<div align="center">
  <img src="https://i.postimg.cc/5t53BLVv/photo-2023-12-19-20-54-52.jpg">
</div>

se conoce como **opcode** (codigo de operacion), es un conjunto de bits en el extremo izquierdo de la instruccion y le indica a la computadora la accion a realizar, mientras los bits en el extremo derecho especifican las direcciones de memoria de los datos que se van a usar.

s
# Lenguajes ensambladores
Los lenguajes de programacion que usan este tipo de notacion en simbolica se conocen como **lenguajes de programacion**. Debido a que las computadoras solo pueden ejecutar programas en lenguaje de maquina,
el conjunto de instrucciones contenido dentro de un programa debe traducirse a un programa de maquina. 
Los programas traductores que realizan esta funcion se conocen como **ensambladores**

<div align="center">
  <img src="https://i.postimg.cc/RVkCfnGv/ensamblador.jpg">
</div>

# Lenguajes de nivel bajo y alto
Los lenguajes como **ensambladores** se clasifican como lenguajes de nivel bajo. Esto se debe a que ambos tipos de lenguaje usan instrucciones que se vinculan en forman directa con un tipo de computadora. 
Un programa en lenguaje ensamblador esta limitado por que solo púede usarse con el tipo de computadora especifica para el cual se escribío 

Un lenguaje de **alto nivel** usa instrucciones que se parecen a los lenguajes ya escritos, como el ingles y pueden ejecutarse en una variedad de tipos de computadora.

Los lenguajes escritos en un lenguaje de computadora (de alto o bajo nivel) se conocen como **programas fuente** o **codigo fuente**. Una vez que se ha escrito un programa en un lenguaje de alto nivel tambien debe traducirse, como un programa ensamblador de bajo nivel, el lenguaje de maquina de la computadora en que se va a ejecutar.

1. Cuando cada declaracíon en un programa fuente de alto nivel es traducida de manera individual y ejecutada inmediatamente despues de la traduccion, el lenguaje de programacion usado se llama **lenguaje interpretado** y el programa que hace la traduccion se llama **interprete**
2. Cuando todas las intrucciones en un programa fuente de alto nivel son traducidas como cualquier declaracion sea ejecutada, el lenguaje de programacion usado se llama **lenguaje compilado** el programa que hace la traduccion se llama **compilador**. Pueden existir tanto versiones compiladas como interpretadas de un lenguaje, aunque de forma tipica solo predomina una.
El programa fuente se introduce usando un progama editor. Este es un programa procesador de palabras que es parte del ambiente de desarrollo proporcionado por el compilador
La traduccion del programa fuente C++ en un programa en lenguaje de maquina comienza con el compilador.
La salida de este producida por este programa se llama **programa objeto** el cual es una version en lenguaje de maquina del codigo fuente.

Un programa C++ grande puede almacenarse en dos dos o mas archivos de programas separados.
este codiugo adicional debe combinarse con el programa objeto antes que el programa pueda ejecutarse.
Es tarea del **ligador** lograr este paso. El resultado del proceso es cargar este programa en lenguaje de maquina en la memoria principal de su computadora para su ejecucion real.

# Orientaciones a procedimientos y a objetos

Los lenguajes de programacion tambien se clasifican por su orientacion a procedimientos u objetos. En un **Lenguaje orientado a procedimientos** las intrucciones disponibles se usan para crear unidades independientes, conocidas como **procedimientos**. El proposito de un procedimiento es aceptar datos como entrada y transformarlos de alguna manera para producir una salida

En la actualidad, la orientacion orientada a objetos, ha tomado el escenario central. Una de las motivaciones para **Lenguajes orientados a objetos** fue el desarrollo de pantallas graficas y soporte para las interfaces graficas de usuario (GUI) capaces de desplegar multiples ventanas que contienen tanto formas graficas como texto. 
Cada ventana en la pantalla puede considerarse un objeto con caracteristicas asociadas, como color, posicion y tamaño.
Un programa debe definir primero los objetos que manipulará incluyendo una descripcion de las caracteristicas generales de los objetos y unidades especificas para manipularlos, como cambiar el tamaño y la posicion y transferir datos entre los objetos

