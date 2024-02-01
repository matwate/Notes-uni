---
{"dg-publish":true,"permalink":"/zettel-kasten/axiomas-de-cuerpo/"}
---


# Axiomas de Cuerpo
Creado: 2024-02-01 09:30
Tema General: [[ZettelKasten/Libros/Matematicas\|Matematicas]]
Tag: #Topic


___
## Que es un sistema axiomatico?

Es un conjunto de conceptos no definidos, los cuales requieren de un concepto de entendimiento universal, es decir, que no haga falta saber la definicion de este para poder aplicarlo.

>[!example] Ejemplo: Que es un numero?
>Es dificil definir que es un numero, pero todos sabemos aplicarlos y realizar operaciones con estos, esto es porque **No hay definicion matematica formal de un numero**
>Por lo tanto los numeros hacen parte de un sistema axiomatico,
> 

Y a partir de esos conceptos basicos no definidos, se empiezan a formar definiciones a partir de ellos
>[!example] Ejemplo
>A pesar de no poder definir que es un numero, podemos categorizarlos en naturales, enteros, estamos creando definiciones a partir de estos

Y despues de las definiciones  se forman las propiedades a partir de de estos.

### Axiomas

Son verdades evidentes por naturaleza que surgen de las definiciones y conceptos anteriores, no se niegan ni se refutan.

>[!example] Suma de 2 numeros.
> Todos sabemos que a la hora de sumar 2 numeros, $x + y = y+x$ y nunca se nego ni se refuto

**Estos son los unicos postulados los cuales no se tienen que demostrar**

### Teoremas

Son postulados derivados de los axiomas. los cuales para ser correctos tienen que ser **Demostrados**


# Definiciones

Junto con el conjunto de los numeros reales se supone la existencia de dos operaciones llamadas *adicion* y *multiplicacion* tales que 
- Para cada par de numeros reales $x, y$ se puede formar la suma de $x, y$ que es otro numero real designado por $x+y$
- Para cada par de numeros reales $x, y$ se puede formar el producto de $x, y$ que es otro numero real designado por $x \cdot y$

$$
+:\mathbb{R} \times \mathbb{R} \to \mathbb{R} \newline 
$$
$$
\times:\mathbb{R} \times \mathbb{R} \to \mathbb{R} \newline 
$$

### Axiomas de cuerpo

1. Axioma Conmutativo.
	Si $x,y$ son numeros reales, entonces $$x+y =y+x \hspace{40px} xy=yx$$
2. Axioma Asociativo
	 Si $x,y,z$ son numeros reales, entonces
	 $$x+(y+z) =(x+y)+z \hspace{40px} x(yz)= (xy)z$$
3. Propiedad Distributiva
	Si $x,y,z$ son numeros reales, entonces
	$$x(y+z) =xy+xz$$
4. Axioma de existencia de elementos neutros
	Existen dos numeros reales distintos notados $0$ y $1$ tales que para cada numero real $x$
	$$x+0 = 0+x = x \hspace{40px} 1 \cdot x = x \cdot 1 = x$$
5. Axioma de existencia de negrativos
	 Para cada numero real $x$ existe un numero real $y$ tal que 
	 $$x+y = y+x = 0$$
6. Axioma de existencia del reciproco
	 Para cada numero real $x$ existe un numero real $y$ tal que 
	 $$xy=yx=1$$
___
## References
1.