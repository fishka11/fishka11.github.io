# Funkcje
Funkcja to wartość opakowana w program. Każda funkcja coś zwraca (jesli nie zawiera słowa "return" - zwraca wartość typu undefined). Może mieć też "efekty uboczne".

Funkcje można zapisać na trzy sposoby:
* Jako przypisanie do zmiennej (na końcu musi być średnik!!!)
```javascript
const a = function(params) {
  // blok instrukcji;
};
```
* Deklaracja funkcji (always hoisted to the top of scope - można deklarować w dowlnym miejscu kodu)
```javascript
function a(params) {
  // blok instrukcji;
}
```
* Funkcja strzałkowa
```javascript
const a = (params) => {
  // blok instrukcji;
};
let b = param => instrukcja;
const c = () => instrukcja;
```
