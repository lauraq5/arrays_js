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

## Accediendo a la información de un array

### Propiedad length
- Devuelve la cantidad de elementos del array 

### Operador [pos]
- Permite acceder para leer o modificar el elemento pos del array 

### Método at(pos)
- Devuelve el elemento de la posición pos. El parámetro admite valores negativos, lo que significa que empiezan a contar por el final del array.

```javascript
const letters = ["A", "B", "C"];
console.log(letters,length);
console.log(letters[2]);
console.log(letters[5]);
```

## Añadir o eliminar elementos 
-push(ele1, ele2): añade uno o varios elementos al final del array. Devuelve el tamaño del array.

```javascript
let miArray = [1, 2, 3,];
miArray.push[4]; // agrego el elemento 4 al final del array 
console.log(miArray);
```

- pop():Devuelve el ultimo elemento del array y lo elimina

```javascript
let miArray = [1, 2, 3,];
miArray.pop(); // Elimina el ultimo elemento del array
console.log(miArray);
```

- unshift(ele1, ele2): añade una o varios elementos al inicio. devolviendo el tamaño del array despues de añadidos.

```javascript
let miArray = [1, 2, 3,];
miArray.pop(); // agrega el elemento 0 al inicio del array
console.log(miArray);
```

-shift(): devuelve el primer elemento del array y lo elimina

```javascript
let miArray = [1, 2, 3,];
miArray.pop(); // elimine el primer elemento del array
console.log(miArray);
```

- concat(ele1, ele2): concatena 2 arrays


```javascript
let miArray = [1, 2, 3,];
miArray.pop(); //agrega el elemento del array
console.log(miArray);
```


- split(separador) : a partir de una cadena, crear un array dividienod dicha cadena en elementos delimitados por separador

```javascript
let miArray = [1, 2, 3,];
miArray.pop(); // elimine el primer elemento del array
console.log(miArray);
```

- join(separador): a partir de un array, crea una cadena separando cada elemento con el separador 


```javascript
let miArray = ["Hola,", "¿cómo", "estás?];
let miString = miArray.join(" ");
console.log(miString);
```

## Busqueda de elementos en un array
- includes(elemento): devueve truo o false si el elemento existe o no dentro del array
- indexOf(elemento): devuelve la poscicion de la primera aparicion del elemento, si no existe devuelve -1.
- lastIndexOf(elemennto): devuelve la posicion de la ultima aparicion del elemento, si no existe devuelve -1.

## modificar el array o crear fragmentos
- slice(inicio, fin): devueve un array con los elementos desde la poscicion inicio hasta la poscicicon fin ambos excluidos.

## ordear elementos de un array
- reverse(): invierte el orden de los elementos del array
- sort(): ordena el array alfabeticamente
- sort(criterio): orde el array con el criterio determinado por la funcion criterio.

## recorrido de un array
1. Recorrer con un bucle clasico pasando por todos los elementos.
```javascript
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domingo"];
for(i=0<dias.ength;i++)
{
    console.log(dias[i]);
}
```

2. Recorrer con un while pasando por todos los elementos.
```javascript
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domingo"];
var i = 0;
while(i<dias.ength)
{
    console.log(dias[i]);
    i++;
}
```

3. usando la sentenca for..in.
```javascript
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domingo"];
for(let index in dias)
{
    console.log(dias[index]);
}
```

## Arrays multidimensionales
```javascript
const matrix = [
    [1,2,3],
    [4,5,6],
    [7,8,9]
];
```

- Recorrer uan matriz utilizando bucles anidados
```javascript
var dias = ["lunes", "martes", "miercoles", "jueves", "viernes", "sabado", "domingo"];
for(let i=0;i<matriz.length; j++)
{
    for(let j=0;matriz[i].length)
{}

```


# Ejercicios

1. dar una lista de numeros separador por coma . calcular la suma, el mayor, el menor, y la media de todos.

2. introducir dos cadenas con elementos separados por coma, y con un botón concatenar las dos cadenas y mostrarlas en pantalla.

3. introducir uno a uno los elementos en un array a través de un boton. con otro botón se va eliminando el ultimo elemento. siempre que se pulse alguna de los botones que debe mostrar el contenido del array.

4. introducir un conjunto de números separados por comas. Cuando se pulsa el boton "pares" cargar uan tabla con los numeros introducidos y luego crear otra que solo incluya los numeros pares y mostrarlas.