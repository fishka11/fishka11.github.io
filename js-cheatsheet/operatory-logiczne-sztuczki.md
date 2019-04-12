# Domyślna wartość - sztuczka z operatorami logicznymi || i &&
Operatory logiczne || i && między wartościami o różnych typach konwertują wartość po lewej na typ logiczny, żeby sprawdzic co robić dalej, a potem zwracają orginalną wartość wyrażenia po lewej lub prawej. 
* logiczne "lub" || - jeśli wartość z lewej jest "truly" zwraca orginalną wartość wyrażenia po prawej i nie sprawdza już co jest po prawej, jeśli "falsy" - zwraca orginalną wartość wyrażenia po lewej.
```javascript
console.log("Asia" || "Margo");
// --> "Asia"
console.log(null || "Margo")
// --> "Margo"
```
* logiczne "i" && - jeśli wartość z lewej jest "truly" zwraca orginalną wartość wyrażenia po prawej, jeśli "falsy" - orginalną wartość wyrażenia po lewej i nie sprawdza już co jest po prawej.
```javascript
console.log("Asia" && "Margo");
// --> "Margo"
console.log(null || "Margo")
// --> null
```
