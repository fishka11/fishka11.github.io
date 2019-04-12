# Obiekty
1. "nazwa_właściwości" in object - sprawdza czy obiekt ma właściwość o takiej nazwie, wynik: true lub false
```javascript
"nazwa_właściwości" in object
```
2. delete object.property - usuwa właściwość obiektu
```javascript
delete object.property
```
3. Listowanie wszystkich właściwosci i metod obiektu. Zwraca tablicę z nazwami wszystkich własciwości i metod.
```javascript
Object.keys(jakiś_obiekt);
```
4. Kopiowanie wszystkich właściwości z jednego obiektu do drugiego.
```javascript
let objectA = {a: 1, b: 2};
Object.assign(objectA, {b: 3, c: 4});
console.log(objectA);
// --> {a: 1, b: 3, c: 4}
```
