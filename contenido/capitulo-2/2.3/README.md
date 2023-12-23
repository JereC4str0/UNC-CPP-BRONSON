# 2.3 Tipos de datos 

+ Un tipo de dato se define como un conjunto de valores y un conjunto de operaciones que pueden aplicarse a estos valores.
+ Un **tipo de dato de clase**, al cual se le hace referencia como una clase, para abreviar, es un tipo de dato creado por el programador.
+ El conjunto de valores y operaciones admitidas es definido por un programador


Un tipo de dato integrado es proporcionado como una parte integral del compilador C++ y no requiere codigo C++ externo, puede usarse sin recurrir a adiciones de lenguaje complementarias, como las proporcionadas por el archivo de encabezado ```iostream``` necesario para el objeto ```cout```
tambien se conocen como tipos **primitivos**, consisten en los tipos numericos basicos mostrados en la figura 2.7 y las operaciones enumeradas en la tabla 2.2

<p align="center">
  <img src="https://i.postimg.cc/QxSmgJVL/imagen.png">
</p>


<p align="center">
  <img src="https://i.postimg.cc/154nTGJ1/imagen.png">
</p>

+ Al introducir tipos de dato integrados de C++, usaremos literales, una **literal** es un valor aceptable para un mismo tipo de dato.
+ Literal refleja que dicho valor se identifica de manera explicita para si mismo es **valor literal o constante**

## Tipo de datos enteros

<p align="center">
  <img src="https://i.postimg.cc/FFpCG4nn/imagen.png">
</p>


## El tipo de dato int
+ Numeros enteros
+ Solo de digito
+ cero o cualquier valor numerico positivo o negativo sin un punto decimal.

## El tipo de dato char
+ Se usa para almacenar caracteres individuales las letras del alfabeto(mayusculas o minusculas, los diez digitos 0 a 9 y simbolos especiales)
+ Encerrado entre comillas sencillas
> Los limites impuestos por el compilador pueden encontrarse en el archivo de encabezado ```limits``` y se definen como las constantes hexadecimales ```int_min``` e ```int_max```
+ Se almacenan usando los codigos ASCII o Unicode
+ El codigo ASCII proporciona codigos para un conjunto de caracteres basado en el idioma ingles, mas codigos para control de impresion y de despliegue
+ proporciona 256 codigos distintos
+ Unicode puede representar 65536 caracteres.
+ Este codigo se usa para aplicaciones internacionales al proporcionar conjuntos de caracteres en otros idiomas ademas del ingles

  <p align="center">
  <img src="https://i.postimg.cc/3rz1txF1/imagen.png">
</p>

## El caracter escape 
+ Es la diagonal inversa \
+ Se conoce como **caracter de escape**
+ Cuando se coloca este caracter directamente frente a un grupo selecto de caracteres, esto indica al compilador que escape de la forma en que estos caracteres se interpretarian en forma normal
+ La combinacion de una diagonal inversa y estos caracteres especificos se llama **secuencia de escape**

<p align="center">
  <img src="https://i.postimg.cc/gj5GZ6Cf/imagen.png">
</p>

## El tipo de dato bool

+ datos booleanos(logicos)
+ verdadero o falso

## Determinacion del tamaño de almacenamiento
+ C++ permite ver donde y como se almacenan los valores
+ ```sizeof()``` que proporciona  el numero de bytes usados para almacenar valores para cualquier nombre de tipo de datos incluidos dentro de los parentesis del operador
+ operador integrado que no usa un simbolo arimetico para ejecutar su operacion

  ```cpp

  #include <iostream>
  using namespace std;
  int main ()
  {
    cout << "\n Tipo de datos Bytes"
         << "\n ---------------    ------" 
         << "\nint                 " << sizeof(int)
         << "\nchar                " << sizeof(char)
         << "\nbool                " << sizeof(bool)
         << '\n';

  return 0;   
  }

  ```



+ El caracter '\n' como la "\n" como el caracter linea nueva
+ '\n' es un caracter literal mientras que "\n" es una cadena literal, desde un punto de vista practico, ambos hacen lo mismo
+ La buena practica de programacion requiere que se termine el ultimo despliegue de salida con una secuencia de escape de linea nueva

### Tipos de datos con signo y sin signo
+ Un tipo de datos con signo proporciona un rango de valores positivos que es, para todos los propositos practicos, el doble del rango provisto por su contraparte los enteros con signo
+ Un tipo de dato sin signo es uno que prevé solo valores no negativos (es decir, cero, positivos)
+ Todos los tipos enteros sin signo, proporcionan un rango de valores positivos que es, para todos los propocitos practicos, el doble de rango provisto por su contraparte los enteros con signo

<p align="center">
  <img src="https://i.postimg.cc/QdCnzyWk/imagen.png">
</p>


### Tipos de punto flotante
+ Un **numero de punto flotante**, el cual se llama **numero real**, puede ser el numero cero o cualquier numero positivo o negativo que contenga un punto decimal.
+ tres tipos de datos de punto flotante
  - float
  - double
  - long double
> la diferencia es la cantidad de almacenamiento para cada tipo, para dobles que para flotantes

+ float (precision simple)
+ double(precision doble)
