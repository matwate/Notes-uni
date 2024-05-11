---
{"dg-publish":true,"permalink":"/induccion/"}
---


# Induccion
Creado: 2024-04-26 11:17
Tema General: [[ZettelKasten/Libros/Matematicas\|Matematicas]]
Tag: #Topic


___

## Axioomas de peano

1. ExistN el $0 \in \mathbb{N}$
2. $\forall n \in \mathbb{N} \text{ existe su sucesor n+ 1}$ el cual es unico
3. $\forall n \in \mathbb{N}, n+1 \neq 0$
4. Si $m,n \in \mathbb{N}$ y $m+1 = n+1$ entonces $m = n$

### 5. Principio de induccion

Sea S un subconjunto de $\mathbb{N}$ tal que:
1. $0 \in S$
2. $n \in S \implies n+1 \in S$
Entonces $S = \mathbb{N}$


## Tarea

Demuestre que para $x \in \mathbb{R} , n \in \mathbb{N} (x \neq 1)$ se tiene que

$$
1 + x + x^2 + \dots + x^{n-1} = \frac{1-x^n}{1-x}
$$
___
## References
1.