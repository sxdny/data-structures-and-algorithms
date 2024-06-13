# Arrays

Para definir una array en JavaScript, lo haremos de la siguiente manera:

```js
let nombres = ["Sidney", "Emilio", "Gabriela", "Paula"];
```

Para acceder a cada una de las posiciones, podemos hacerlo de varias maneras:

```js
console.log(nombres[0]) // para acceder a la posición 0 (la primera)
console.log(nombres[1]) // para acceder a la posición 1 (la segunda)
// y así...
```
JavaScript nos permite hacer cambios en la array en cualquier momento. Si por ejemplo queremos cambiar el valor de la posicón 1, haremos lo siguiente:

```js
nombres[1] = "Felipe" // Y se cambiaria el valor de la posición 1
```

También podemos añadir una nueva posición si queremos de la siguiente manera:

```js
nombres[3] = "Paula";
```

Y la array quedaria de la siguiente manera:

```js
["Sidney", "Felipe", "Gabriela", "Paula"]
```

## Funciones de array

### Push

La función `.push()` nos permite introducir nuevos valores a la ultima posición disponible de la array. Por ejemplo si la array tiene una longitud de 3 (0, 1 y 2), pasará a tener una longitud de 4 y (0, 1, 2 y 3).

Ejemplo:
```js
let frutas = ["Tomate", "Manzana", "Naranja"];

frutas.push("Pera");

// Ahora la array queda:
["Tomate", "Manzana", "Naranja", "Pera"]
```

### Pop

El método `.pop()` elimina el último elemento de la array disponible. Si usamos este método en la array anterior, quedará como antes (con solo los elementos; "Tomate", "Manzana", "Naranja", "Pera")

### Unshift

El método `.unshift()` añade los elementos que le especifiquemos al principio de la array.

Ejemplo:
```js
let frutas = ["Tomate", "Manzana", "Naranja"];

frutas.unshift("Mango", "Coco")

// Ahora la array queda:
["Mango", "Coco", "Tomate", "Manzana", "Naranja"];
```
### Shift

El método `.shift()` elimina el primer elemento de una array y lo devuelve.

Ejemplo:
```js
let frutas = ["Tomate", "Manzana", "Naranja"];

frutas.shift(); // Esto elimina "Tomate" y lo devuelve.

// Y ahora la array quedaria de la siguiente manera:
```

### Length

El método `.length` nos devuelve la lnogitud de la array.

Ejemplo:
```js
let frutas = ["Tomate", "Manzana", "Naranja"];

console.log(frutas.length) // --> 3
```

### IndexOf

El método `.indexOf()` devuelve el índice de un elemento de la array.

Ejemplo:
```js
let frutas = ["Tomate", "Manzana", "Naranja"];

frutas.indexOf("Manzana") // esto nos devuelve 1
// si el elemento no existe, devuelve un -1
```

Y existen más funciones pero estas son las principales.

