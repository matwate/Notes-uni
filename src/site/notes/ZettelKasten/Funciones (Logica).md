---
{"dg-publish":true,"permalink":"/zettel-kasten/funciones-logica/"}
---


# Funciones (Logica
Creado: 2024-05-10 12:05
Tema General:[[ZettelKasten/Libros/Matematicas\|Matematicas]]
Tag: #Topic


___
## Funciones

Una funcion es una relacion f tal que  si $$
 (x,y_{0}) \in f \land (x,y_{2}) \in f \implies y_{0} = y_{1}
$$
>[!example] Ejemplo:
>$f: \{ a,b,c \} \to \{ 1,2,3 \}$
>$f={(a,1 ), (b,1), (c,1)}$

*Def. Sea $f: A \to B$ una funcion*
- Si $(a,b) \in f$ decimos que $f(a) =b$ se dice que b es imagen de a bajo f
**Conjunto de salida: A**
**Conjunt de llegada: B**

### Dominio y rango

$$Dom(f) = \{x \in A: (x,y) \in f \text{ para algun } y \in B \} $$
$$Rango(f) = \{y \in B: (x,y) \in f \text{ para algun x} \in A\ \} $$
### Tipos de funciones

1. **Funcion Inyectiva** 
	Una funcion $f: A\to B$ es inyectiva si y solo si para:
	$$
(x_{0},y) \in f \land (x_{1},y) \in f \implies x_{0}=x_{1}
$$
$$
\text{Si } x_{0} \neq x_{1} \implies f(x_{0}) \neq f(x_{1}) 
$$
2. **Funcion Sobreyectiva**
	Una funcion $f: A \to B$ es sobreyectiva si y solo si $Im(f = B)$ 

3. **Funcion Biyectiva**
	UNa funcion $f: A \to B$ es biyectiva si y solo si es inyectiva y sobreyectiva

## Numero de funciones en conjuntos finitos

El numero de funciones de A en B esta dado por 
$$
{|A|}^{|B|}
$$

>[!note] Extras
>1. Dos conjuntos tienen la misma cardinalidad si existen funciones biyectivas entre los dos conjuntos

>[!important] Tarea
>Demostrar que $|\mathbb{Q}| = |\mathbb{Z}|$

## Propiedades

1.  Sea f una funcion sobreyectiva de A en B entonces $$
 A_{0} \subseteq F^{-1}[F[A]]
$$


## References
1.