# Leonel Ale
---
## CoderHouse
### Comision 51885 
#### Profesor: Omar Manias
##### Tutor: Fernando Moyano
---

## Primera entrega:



### Funciones
```javascript
function AdivinarNumero(){
}

AdivinarNumero();
```
---
### Variables
```javascript
const numeroganador = 4
let aciertos = 0 
let numero;
```
### Loops
```javascript
 for (let i = 0; i < 2; i++) {
        numero = parseInt(prompt(`Ingrese un numero (Menos de 10)`));
``` 
### Condicional 1 
```javascript
        if (numero < 1 || numero > 10 || isNaN(numero) ) {
            alert("Numero invalido. Ingrese un numero del 1 al 10");
            i--;
            continue;
```
### Condicional 2
```javascript
if (aciertos === 1) {
        premio = "Ganaste la loteria"
    } else {
        premio = "Segui participando";
    }
---

