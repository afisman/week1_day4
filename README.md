# week1_day4


## Contenidos

> JS | Data types: strings, numbers, boolens, arrays, objects
>
> JS | Conditionals & loops
>
> JS | Functions

 
## Main points: functions
  
A nivel de estructura, existen: 
- **Function statement**: disponen de al palabra reservada `function`, de paréntesis para sus parámetros y de bloque:
  ````javascript
  function getTotals(subtotal, tax){
    return subtotal + tax
  }
  ````
- **Arrow function**: carecen de la palabra reservada `function`, el paréntesis en sus parámetros es omitible frente a un único parámetro, y disponen una flecha previo a la apertura de su bloque (bloque omitible en funciones de una única instrucción).
  ````javascript
  const getTotals = (subtotal, tax) => subtotal + tax
  ````
Las funciones pueden recibir argumentos en forma de parámetros, y retornar datos. A efectos del retorno:
- Sólo pueden retornar un único valor, o `undefined` si carecen de retorno.
- Un retorno en una función supone detener su ejecución.
- Las _arrow function_ carentes de bloque disponen de retorno por defecto.

A efecto del alcance de variables:
- Las variables declaradas dentro de un bloque o función se denominan **locales** o **privadas**, accesibles únicamente dentro de ese contexto.
- Las variables declaradas fuera de cualquier bloque o función se denominan **globales** o **públicas**, accesibles desde cualquier parte del script.


## Main points: objects

- Los objetos de notación literal están compuestos por pares `key: value`.
  
- El acceso a una `key` (propiedad) para hacer un uso _setter_ (obtener) o _getter_ (modificar) de la misma, se realiza:
  - Mediante la notación del punto.
  - Mediante el acceso nominal (corchetes).
  
- Los operadores aplicables a objetos son:
  - El operador `in` permite conocer la existencia de una propiedad en un objeto.
  - El operador `delete` permite eliminar una propiedad de un objeto.
  
- Las iteraciones aplicables a objetos son:
  - El bucle `for...in` permite recorrer las _keys_ de un objeto.
  - `Object.keys(obj)` permite iterar sobre las _keys_ de un objeto.
  - `Object.values(obj)` permite iterar sobre los valores de un objeto.
  
 
 
