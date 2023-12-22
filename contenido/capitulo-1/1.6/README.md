# Hardware de computacion y conceptos de almacenamiento

Todas las computadoras deben realizar un conjunto minimo de funciones y proporcionar la capacidad para:

1. Aceptar entradas
2. Mostrar salidas
3. Almacenar informacion en un formato logico consciente(binario)
4. Ejecutar operaciones arimeticas y logicas en los datos de entrada o en los almacenados
5. Supervisar, controlar, y dirigir la operacion y secuencia general del sistema

Los componentes de la computadora que respaldan estas capacidades forman el hardware de la computadora.

La **unidad de almacenamiento y logica(ALU)** ejecuta todas las funciones arimeticas y logicas como adicion y sustraccion, y las proporcionadas por la computadora.

La **unidad de control** dirige y supervisa la operacion general de la computadora. Rastrea el lugar de la memoria donde reside la siguiente instruccion, emite las señales necesarias para leer y escribir datos en otras unidades en el sistema y controla la ejecucion de todas las instrucciones.

La **unidad de memoria** almacena informacion en un formato logico consistente, tanto instrucciones como datos se almacenan en la memoria, por lo general en areas separadas y distintas.

La **unidad de entrada y salida(I/O o E/S)** proporciona la interfaz a la que se conectan dispositivos perisfericos como teclados, monitores, impresoras y lectores de tarjeta.

**Almacenamiento Secundario:** La memoria principal en cantidades muy grandes aun es relativamente cara y volatil(la informacion se pierde cuando se suspende la energia), se usan dispositivos de almacenamiento secundario o auxiliar

<div align="center">
  <img src="https://i.postimg.cc/Jzh7ssT9/imagen.png">
</div>

En la decada de los años 60 con la introduccion de los transistores, se redujeron tanto el tamaño como el costo del hardware de la computadora.
El tamaño pequeño del transistor permitío a los fabricantes combinar la unidad arimetica y la logica con la unidad de control en una sola unidad.
Esta unidad combinada se llama **unidad central de procesamiento(CPU)**

A mediados de la decada de los años 60 se implemento la introduccion de circuitos integrados(IC), lo cual significo en una reduccion significatifva en el espacio requerido para producir una CPU.
Al principio, los circuitos integrados se fabricaban hasta con 100 transistores en un solo chip de silicio de 10cm2. Tales dispositivos se conocen como circuitos integrados de pequeña escala (SSI).
Las versiones actuales de estos chips contienen cientos de miles a mas de un millon de transistores y se conocen como integrados a gran escala(VLSI)

La tecnologia de chips VLSI ha proporcionado los medios para transformar las computadoras gigantes de la decada de los 50 en las computadoras personales de escritorio y portatiles de la actualidad.
Cada unidad individual requerida para formar una computadora(CPU, memoria e I/O) se fabrica ahora en un chip VLSI individual, y la CPU de un solo chip se denomina microprocesador.



<div align="center">
  <img src="https://i.postimg.cc/WpdqYb0m/imagen.png">
</div>

Las velocidades de computo de las maquinas actuales midiendose en millones de instrucciones por segundo(MIPS) y miles de millones de instrucciones por segundo(BIPS)

# Almacenamiento de computadora

La pieza mas pequeña y basica de datos en una computadora se llama **bit**, un bit en realidad es un interruptor que puede abrirse o cerrarse.
las posiciones abierto y cerrado de cada interruptor se representan como 0 y un 1, respectivamente.
Un solo bit tiene utilidad limitada.
Todas las computadoras agrupan un numero establecido de bits, tanto para su almacenamiento como para su transmision.
El agrupamiento de ocho bits para formar una unidad mas grande es un estandar casi universal en la computacion, Tales grupos se conocen como bytes. 
Un solo byte son 8 bits, donde cada bit es 0 o 1, puede representar cualquier de 256 patrones distintos.
Estos consisten del patron 0000000(los ocho interruptores abiertos) al patron 11111111(los ocho interruptores cerrados) y todas las combinaciones intermedias posibles de 0 y 1, cada uno de estos patrones puede usarse para representar ya sea una letra del alfabeto, otros caracteres individuales, un digito o numeros que contienen mas de un digito.
La coleccion de patrones consistentes en 0 y 1 que se usan para representar letras, digitos, individuales y otros caracteres individuales se llama **codigo de caracteres**(Uno de estos codigos, llamado codigo ASCII)

# Numero de complemento a dos

El codigo de numeros mas comun para almacenar valores enteros dentro de una computadora es la representacion de **complemento a dos**, cada valor en la caja ilustrada representa un aumento en una potencia de dos.
<div align="center">
  
| Decimal | Binario | Complemento a Dos |
|:-------:|:-------:|:------------------:|
|    0    |   0000  |        0000        |
|    1    |   0001  |        0001        |
|   -1    |   1111  |        1111        |
|    2    |   0010  |        1110        |
|   -2    |   1101  |        1110        |
|    3    |   0011  |        1101        |
|   -3    |   1100  |        1101        |
|    4    |   0100  |        1100        |
|   -4    |   1011  |        1100        |

</div>

cualquier numero binario en complemento a dos con un 1 inicial representa un numero negativo y cualquier patron de bits con un 0 inicial representa un numero positivo

# Palabras y direcciones
Uno o mas bytes pueden agruparse en unidades mas grandes, las llamadas palabras, lo cual facilita un acceso mas rapido y extenso a los datos.

<div align="center">
  
  | Tamaño de Palabra | Valor Máximo | Valor Mínimo |
|:------------------:|:------------:|:------------:|
|       1 byte       |    127       |    -128      |
|       2 bytes      |   32,767      |   -32,768    |
|       4 bytes      | 2,147,483,647 | -2,147,483,648|

</div>
