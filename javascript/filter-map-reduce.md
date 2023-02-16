# Filter, Map e Reduce
Queste tre funzioni servono per gestire rapidamente dati all'interno di liste. Sono l'equivalente in Javascript del LINQ
## Filter
La funzione __filter__ consente di estrarre determinati elementi dell'array in base ad una funzione
``` javascript
const numbers = [1, 4, 5, 6, 4, 2, 5, 6, 3, 1]
const even = numbers.filter(x => x % 2 === 0)
console.log('Numeri pari: ', even)
```
## Map
La funzione __map__ consente di applicare una funzione ad ogni elemento della lista
``` javascript
const numbers = [1, 4, 5, 6, 4, 2, 5, 6, 3, 1]
const quadrati = numbers.map(x => x * x)
console.log('Quadrati: ', quadrati)
```
## Reduce
La funzione __reduce__ di effettuare una funzione su ogni elemento della lista e restituire un risultato "accumulato"
``` javascript
const numbers = [1, 4, 5, 6, 4, 2, 5, 6, 3, 1]
const somma = numbers.reduce((accumulatore, valore) => { return accumulatore + valore }, 0)
console.log('Somma: ', somma)
```
