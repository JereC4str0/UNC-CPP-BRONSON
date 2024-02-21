# Operaciones arimeticas 

| Operacion    | Operador |
|-----------|------|
| Adiccion| +   |
| Sustraccion| -   |
| Mutiplicacion| *   |
| Divicion| /   |
| Divicion de modulo| %   |


Estos operadores se conocen como operadores binarios
El operador requiere dos operandos para producor un resultado. Un operando púede ser un valor literal o un identificador que tiene un valor asociado con el.
Una expresion arimetica binaria simple consta de un operador arimetico binario que conecta dos valores literales en la forma


```cpp
  ValorLiteral  operador = ValorLiteral
```

## Programa 2.6

```cpp
  #include <iostream>
  using namespace std;

  int main()
{
  cout << "15.0 mas 2.0 es igual a "              << (15.0 + 2.0) << endl
  cout  << "15.0 menos 2.0 es igual a "              << (15.0 - 2.0) << endl
  cout << "15.0 por 2.0 es igual a "              << (15.0 * 2.0) << endl
  cout << "15.0 dividido 2.0 es igual a "              << (15.0 / 2.0) << endl;

  return 0;
}
```
#### endl es un manipulador

Un manipulador es un elemento usado para manipular como se despliega el flujo de salida de caracteres.
endl provoca que primero se inserte un caracter de linea nueva ('\n') en el despliegue y obliga a que todas las inserciones actuales se desplieguen de imediato, en lugar de esperar por mas datos

## Tipos de expresion
Una expresion es cualquier combinacion de operadores y operandos que pueden ser evaluados para producrir un valor, Una expresion que contiene solo valores enteros como operandos se llama expresion entera y el resultado de la expresion es un valor entero

una expresion que contiene valores de punto flotantes se llama expresion de punto flotante y el resultado es una expresion real.
Una expresion que contiene valores enteros y de punto flotante se llama expresion en modo mixto.

es mejor no mezclar valores enteros y de punto flotante en una operacion arimetica

1. Si ambos operandos son enteros, el resultado de la operacion es un entero
2. Si un operando es un valor real, el resultado de la operacion es un valor de precision doble.


