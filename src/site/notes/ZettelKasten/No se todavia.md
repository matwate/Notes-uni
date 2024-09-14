---
{"dg-publish":true,"permalink":"/zettel-kasten/no-se-todavia/"}
---


# No se todavia
Creado: 2024-04-25 09:27
Tema General: [[ZettelKasten/Libros/Matematicas\|Matematicas]]
Tag: #Topic


___
## Representacion decimal finita


Un numero real de la forma:

$$
r = a_{0} + \frac{a_{1}}{10}+ \frac{a_{2}}{10^2}+ \dots + \frac{a_{n}}{10^n}
$$
donde $a_{0}$ es un entero no negativo y $a_{1}, a_{2}, a_{3}, a_{n}$ son enteros $0\leq a_{n} \leq 9$ se puede representar como

$$
r =a_{0}a_{1}a_{2}a_{3}..a_{4}
$$
Y se dice que esta es la representacion decumal finita de r

### Nota

Todo numero real de la forma 
$$
r =a_{0}a_{1}a_{2}a_{3}..a_{4}
$$
es un numero racional que puede ser expresado como:

$$
r = \frac{a}{10^n} \text{Para algun } a \in \mathbb{Z}
$$

### Nota 2

Todo numero real x > 0 puede aproximarse como un error tan pequeño  como se desee tomando n suficientemente grande< es decir , existen expresiones decimales finitas $n_{1}$ y $n_{2}$ tales que 

$$
 n_{1} < x < n_{2} \text{ y } n_{2}-n_{1}=\frac{1}{10^n}
$$

## Construccion geometrica

Si x > 0 y x no es un entero existe un entero $a_{0}$ tal que:
$$
a_{0}
< x < a_{0}+1 
$$
EL segmento entre $a_{0}$ y $a_{0}+ 1$ se divide en 10 partes iguales, si x no coincide en ninguno de estos puntos de subdivision, x debe estar comprendido entre dos de ellos:

$$

0
a_{0} + \frac{a_{1}}{10} < x < a_{0}+\frac{a_{1} + 1}{10}, 0 \leq a_{1} \leq pp9
$$
Si despues de un numero finito de subdivisiones, uno de los puntos coincide con x , entonces x admite una representacion decimal finita.

En caso cotntrario, el proceso continua indefinidamente generando un conjunto infinito de enteros $a_{0},a_{1},a_{2},a_{3},\dots$ tales que 
$$
x =a_{0}a_{1}a_2a_3\dots
$$
Entonces x es la representacion decimal finita

## Primera representacion decimal

Dado x > 0 sea $a_{0}$ el mayor entero que satisface
$$
 a_{0}\leq x
$$
Ahora sea a1 el mayor entero que satisface 
5
$$
a_{0} + \frac{a_{1}}{10} \leq x 
$$
Determinados $a_{0}a_{1}a_{2}a_{3}a_{n}$ sea $a_{n}$ el mayor entero que satisface

$$
a_{0} + \frac{a_{1}}{10} + \frac{a_{2}}{10^2} + \dots + \frac{a_{n}}{10^n} \leq x
$$
Sea S el conjunto definido por

$$
 S = \{ a_{0} + \frac{a_{1}}{10} + \frac{a_{2}}{10^2} + \dots + \frac{a_{n}}{10^n}: a_{0} + \frac{a_{1}}{10} + \frac{a_{2}}{10^2} + \dots + \frac{a_{n}}{10^n} \leq x \}
$$
S es no vacio y acotado superiormente entonces tiene Supremo y ese es X

## Segunda representacion decimal

Dado x > 0 sea $b_{0}$ el mayor entero que satisface

$$
 b_{0} < x
$$
Si realizamos el proceso anterior, nos queda otra representacion.

1 = 1 = 0.9999999... 
## References
1.