---
{"dg-publish":true,"permalink":"/zettel-kasten/logica-002/"}
---


# Logica 002
Creado: 2024-02-02 11:01
Tema General: [[ZettelKasten/Libros/Matematicas\|Matematicas]]
Tag: #Topic


___

## Estructura Si -> Entonces

Un teorema se estructura de la forma Si , entonces, ($A\implies B$)

A: Antecendente, Hipotesis, o Condicion Suficiente
B: Conclusion, Tesis, o Condicion Necesaria

## Tablas de verdad

###### Operadores Logicos:

Binarios: Operan sobre 2 elementos ($\implies, \leftrightarrow, \vee, \wedge,$)
Unarios: Opera en un solo elemento ($\neg$)

SI $P$ es una proposicion simple, es decir tiene un valor de verdad

#### Tabla de verdad de operador $\implies$, (Entonces)

| p | q | $p \implies q$ |
| ---- | ---- | ---- |
| V | V | V |
| V | F | F |
| F | V | V |
| F | F | V |
#### Tabla de verdad de operador $\wedge$, (Y)

| p   | q   | $p \wedge q$ |
| --- | --- | ------------ |
| V   | V   | V            |     
| V   | F   | F            |     
| F   | V   | F            |     
| F   | F   | F            |     

#### Tabla de verdad de operador $\vee$ (o)

| p | q | $p \vee q$ |
| ---- | ---- | ---- |
| V | V | V |
| V | F | V |
| F | V | V |
| F | F | F |

#### Tabla de verdad de operador $\neg$ (No)

| p | $\neg p$ |
| ---- | ---- |
| V | F |  
| F | V |  
#### Tabla de verdad de operador $\iff$ (Si y solo si)

| p   | q   | $p \iff q$ |
| --- | --- | ---------- |
| V   | V   | V          |
| V   | F   | F          |
| F   | V   | F          |
| F    | F    | V           |



### Alfabeto de logica

$l = [p,q,r,s,t, \implies, \iff, \vee, \wedge, \neg, ( ,)]$

1. Letras Proposicionales
	: p, q , r, s, t
2. Operadores
	: $\implies, \leftrightarrow, \vee, \wedge, \neg,$

3. Si $\alpha, \beta, \gamma$ son formulas bien formadas:
	$(\alpha) \vee (\beta), (\alpha) \wedge(\beta), (\alpha)\implies(\beta),(\alpha) \iff(\beta)$ y $\neg(\alpha)$ tambien estan bien formadas
	
4. El numero de parentesis derechos debe ser igual al numero de parentesis izquierdos
>[!example] Ejemplo
>$((p) \implies (q)) \vee ((p)\iff(\neg(r)))$

###### La tabla de verdad del ejercicio anterior

| p | q | r | $(p)\implies(q)$ | $\neg(r)$ | $(p)\iff(\neg(r))$ | $(\alpha) \vee (\beta)$ |  |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| v | v | v | V | f | f | V |  |
| v | v | f | V | v | v | V |  |
| v | f | v | F | f | f | F |  |
| v | f | f | F | v | v | V |  |
| f | v | v | V | f | v | V |  |
| f | v | f | V | v | f | V |  |
| f | f | v | V | f | v | V |  |
| f | f | f | V | v | f | V |  |
##### Clasificaion de tablas de verdad

Tautologia: si todos los resultados son V
Contradiccion: si todos los resultados son F
Contingencia: si hay tanto V como F


Ejercicios:

$((p)\implies(q))\iff((\neg(q)) \implies(\neg(p)))$

| p | q | $(p)\implies(q)$ *$\alpha$* | $\neg(q)$ *$\beta$* | $\neg(p)$ *$\theta$* | $\beta \implies \theta$ *$\gamma$* | $\alpha \iff$$\gamma$ |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| v | v | V | F | F | V | V |
| v | f | F | v | F | F | V |
| f | v | V | F | V | V | V |
| f | f | V | v | V | V | V |
Es una Tautologia


Traer un ejemplo de un enunciado  verdadero por vacuidad$
___
## References
1.