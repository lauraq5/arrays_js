# Arrays 

- Una array es una zona de almacenamiento continuo, donde se puede introducir varios valore cada uno de ellos ubicado por la oposicion que ocupa en el array.
- Tambien son denominados arreglos o vectores y cuando son de dos dimensiones son llamados matrices. 
- Los arrays nos brinda capacidad d posicion array e almacenar una coleccion de elementos y acceder a ellos de manera individual
- Cada elemento se identifica mediante su posicion en el array denominada **indice** y estos indices son sienpre secunciales 
- En javascript son alta mente flexibe en terminos de los diferenetes tipos de datos que podemos almacenar en cada 

## crear un array 

1. Declarando  un array con elementos en linea 

```javascript
let miArray = [1, 2, 3,];
console.log(miArray);
```

2. Declarando un array con la sintaxis **new Array()**

```javascript
let miArray = new Array (1, 2, 3,);
console.log(miArray);
```

3. Declarando un array con un tamaño especifico utilizando la sintaxis **new Array** y asignando valores despues.

```javascript
let miArray = new Array(3);
miArray[0] = 1;
miArray[1] = 2;
miArray[2] = 3; 
console.log(miArray3);
```

4. Declarando un array con el elemento de diferentes tipos de datos

```javascript
let miArray4 = [1, "dos" , true, {nombre: "Juan", edad: 30}new Array(3)];
console.log(miArray4);
```
