# Solucion de problemas y desarrollo de software
El metodo usado por los profesionales que desarrollan software es llamado **procedimiento de desarrollo de software** y consta de 3 fases.

* Diseño y desarrollo
* Documentacion
* Mantenimiento

<div align="center">
  <img src="https://i.postimg.cc/mgRKyNrP/pds.jpg">
</div>

<br>

# Fase I. Desarrollo y diseño 

Comienza con el planteamiento de un problema o con una solicitud específica de un programa, lo cual se conoce como **requerimiento de programa** 
Una vez planteado un problema o se ha hecho una solicitud especifica para un programa, comienza la fase de diseño y desarrollo.
Consiste de cuatro pasos:

<div align="center">
  <img src="https://i.postimg.cc/j25CVXDS/pdss.jpg">
</div>


## Paso 1. Analizar el problema 
Asegurar que el problema esta definido y se entiende con claridad.
Sino se está seguro de como obtener la salida requerida o exactamente cuáles entradas se necesitan, se requiere un analisis mas profundo.
Este es el primer paso en la creacion de un programa y el mas importante
Sin tener en cuenta cómo se hizo el analisis, o por quíen, al concluirlo deberá haber una compresion clara de:

<br>

* Que debe hacer el sistema o programa
* Que salidas debe producir
* Que entradas se requieren para crear las salidas deseadass

## Paso 2. Desarrollar una solucíon 
Se selecciona un numero exacto de pasos, llamado **algoritmo**, que se usará para resolver un problema.
El diseñador podría organizar al principio los requerimientos para el programa en **diagrama de estructura de primer nivel** porque representa la primera estructura general del programa seleccionado por el

<br>

<div align="center">
  <img src="https://i.postimg.cc/LsXr7tZN/imagen.png">
</div>

  __subdivisiones de segundo nivel__

<div align="center">
  <img src="https://i.postimg.cc/GhMNDM2z/imagen.png">
</div>

refinar una solucion hasta que el requerimiento más pequeño se ha incluido dentro de la solucion.

## Paso 3. Codificar la solucíon 
Escribir el programa y poner en practica la solucíon, consiste en traducir la solucíon de diseño elegida en un programa de computadora.
En un programa bien diseñado, los planteamientos que forman el programa se conformarán con ciertos patrones o estructuras bien definidos en el paso de la solucíon. Estas estructuras controlan la forma en que el programa se ejecuta y consiste en los siguientes tipos:

1. Secuencia
2. Seleccion
3. Iteracion
4. Invocacion

La **secuencia** define el orden en que son ejecutadas las intrucciones por el programa. Cual instruccion entra primero, cuál en segundo lugar, etc.,

<br>

La **seleccion** proporciona la capacidad de hacer una eleccion entre diferentes operaciones, dependiendo del resultado de alguna condición. Por ejemplo, el valor de un numero puede comprobarse antes que una division sea realizada.

<br>

La **invocacion** implica invocar, o solicitar, un conjunto de instrucciones cuando sea necesario. Por ejemplo, el calculo del pago neto de una persona implica las tareas de obtener las tarifas de salario y las horas trabajadas, calcular el pago neto y proporcionar un reporte o cheque por la cantidad requerida, Por lo general una de estas tareas individuales se codificarían como unidades separadas que son llamadas a ejecución, o invocadas, según se necesiten.

## Paso 4. Probar y corregir el programa
verificar que el programa funciona en forma correcta y en  realidad cumple con sus requerimientos. En teoría, las pruebas revearían todos los errores del programa (En terminologia de computacion un error de programa se conoce como **bug**)

Si la prueba revela un error(bug), puede iniciarse el proceso de depurar, el cual incluye localizar, corregir y verificar correccion. aunque la prueba puede revelar la presencia de un error, no necesariamente indica la ausencia de uno.
el hecho de que una prueba revele un error no indica que otro no esté al acecho en alguno otro lado del programa.

Para detectar y corregir errores en un programa es importante desarrollar un conjunto de datos de prueba por medio de los cuales determinar si el rpgorama proporciona respuestas correctas.
El programa deberá probarse con datos en un rango razonable, al igual que dentro de los limites y en areas donde el programa debería indicar al usuario que los datos son invalidos.

> "Es imposible escribir un programa exitoso para un problema o aplicacion que no se ha comprendido por completo"

> "Entre mas pronto se comienza a codificar un programa, por lo general tomara mas tiempo para completarlo"

<br> 

| Paso | Esfuerzo |
| --------- | --------- |
| Analizar el problema    | 10 % |
| Desarrollar una solucion    | 20 % |
| Codificar la solucion    | 20 % |
| Probar el programa    | 50 % |

## Fase II. Documentacion
Existen cinco documentos para toda solucion de problemas:
1. Descripcion del programa
2. Desarrollo y cambios al algoritmo
3. Listado del programa bien comentado
4. Muestras de las pruebas efectuadas
5. Manual del usuario

<br>

La fase de documentacion comienza de manera formal en la fase de desarrollo y diseño y continua hasta la fase de mantenimiento.

## Fase III. Mantenimiento
La correccion continua de problemas, reviciones para satisfacer necesitades cambiantes y la adicion de caracteristicas nuevas es el esfuerzo mayor, la fuente principal de ingresos y la mas duradera de las fases de ingenieria.
Entre mas completa es la documentacion, el mantenimiento podrá efectuarse de manera mas eficiente y el cliente y el usuario serán mas felices 😄

## Respaldo 

Aunque no es parte del proceso de diseño formal, es esencial hacer y conservar copias de respaldo del programa en cada paso del proceso de programacion y depuracion
Las copias de respaldo permiten la recuperacion de la ultima etapa de trabajo con un esfuerzo minimo.

> "El respaldo no es importante si no le importa empezar todo de nuevo"
