---
{"dg-publish":true,"permalink":"/zettel-kasten/algebra-booleana/"}
---


# Algebra Booleana
Creado: 2024-02-28 11:07
Tema General:[[ZettelKasten/Libros/Matematicas\|Matematicas]]
Tag: #Topic


___
## Que es?
*Def.* UN algebra de Boole es un conjunto A con dos $(A, +, \cdot)$ tales que $(+:= \vee, \cdot := \wedge)$

1. Existen dos elementos $1,0 \in A$ 1 Siendo True, 0 es False
2. Propiedad Conmutativa
	-  Para $x,y \in A$ se tiene que 
	$x+ y = y + x, x \cdot y = y \cdot x$
3. Propiedad Idempotente
	- Para $x \in A$ se tiene que 
	$x + x = x , x \cdot x = x$
4. Propiedad Asociativa
	- Para $x,y,z \in A$ se tiene
	$x+(y+z) = (x+y) + z$
	$x \cdot (y \cdot z) = (x \cdot y) \cdot z$
5. Propiedad Distributiva
	- Para $x,y,z \in A$ se tiene que
	$x \cdot (y + z) = x \cdot y + x \cdot z$
	$x + (y \cdot z) = (x + y)(x + z)$
6. Complemento
	($x$, su complemento es $x\prime$: $p, \neg p$)
7. Propiedad Universal
	$1+ x = 1$
	$0 \cdot x = 0$
8. Neutros.
	$0 + x = x$
	$1 \cdot x = x$

### Ejemplo

>[!example]- .
>Si  $A =\{Proposiciones\}, +:=\vee, \cdot:=\wedge$ entonces $(A,\vee, \wedge, \neg)$ forma un Algebra de Boole

*Def.* Decimos que $\alpha$ y $\beta$ que son Formulas Bien Formadas, son logica mente equivalentes Si y Solo Si la Formula Bien Formada $(\alpha)\iff (\beta)$ es una tautologia en tal caso escribimos $\alpha = \beta$

*Propiedad:* $\alpha = \beta$ Si y solo si sus tablas de verdad son identicas.

>[!example]- Ejemplo
>![EjemploAlgebraBooleana1.excalidraw.png](/img/user/Excalidraw/EjemploAlgebraBooleana1.excalidraw.png)
___
## References
1.