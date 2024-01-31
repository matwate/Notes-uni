---
{"dg-publish":true,"permalink":"/grafica-de-funciones-trigometricas-seno-y-coseno/"}
---


# Grafica de funciones trigometricas seno y coseno
Creado: 2024-01-31 15:00
Tema General:[[ZettelKasten/Libros/Matematicas\|Matematicas]]
Tag: #Topic 

Nota: *Las expresiones matematicas y graficos no estan permitidos en DIgitalGarden, para verlos abra [Desmos](https://www.desmos.com/calculator?lang=es) y copie y pegue la expresion *

___
### Graficas de seno y coseno
- La grafica de una funcion nos da una mejor idea de su comportamiento
- Para las graficas del senoy coseno, se tiene que, se repiten sus valores de manera regular
- Para ver este comportamiento podemos tomar la circunferencia unitaria de radio $1$

-  Para un valor real $t$ se tiene un Punto terminal $P(x,y)$, el punto $t +2\pi$ tendra el mismo punto terminal $P(x,y)$ por lo tanto, los valores no cambian con la adicion de cualquier multiplo de $2\pi$
	 Lo cual hace que se cumplan estas 2 funciones 
	 $\sin(t+2\pi) = \sin(t)$ 
	 $\cos(t+2\pi) = \cos(t)$
-  Lo cual seno y coseno son funciones **Periodicas**
>[!note] 
>Una funcion $f$ es **periodica** si hay un numero positivo $p$ tal que $f(t + p)=f(t)$ para toda $t$
>El minimo de tal numero positivo es el periodo $P$
>Si $f$ tiene periodo $p$ m la grafica de f en cualquier inteervalo de longitud $p$ se denomina periodo completo

### Propiedades periodicas de seno y coseno
- Las funciones seno y coseno tienen perido $2\pi$
	 $\sin(t+2\pi) = \sin(t)$ 
	 $\cos(t+2\pi) = \cos(t)$
- Para graficar seno y coseno primero lo observamos en un periodo de $0 \leq t \leq 2\pi$
```desmos-graph
y =\sin(x)
```
### Transformaciones de las funciones seno y coseno

- Grafica de la funcion siguiente:
	$f(x) = 2+\cos(x)$
> [!hint]- Grafico
> ```desmos-graph
> y = 2 + \cos(x)
>```
- Grafica de la funcion siguiente:
	$y = -\cos(x)$
>[!hint]- Grafico
>```desmos-graph
>y = -\cos(x)
>``` 
- Grafica la siguiente funcion:
	$y = 2sen(x)$
>[!hint]- Grafico
>```desmos-graph
>top=3; bottom=-3;
>---
>y = 2\sin(x)
>```

**Por lo general en las funciones $y = a\sin(x)$  y $y=a\cos(x)$ el numero $|a|$ es el valor mas grande que alcanza la funcion y por ende su amplitud**

- Hallar Amplitud y Grafica de $y = -3\cos(x)$
>[!hint]- Grafico
>```desmos-graph
>y = -3\cos(x)
>```

Para una funcion $y = a\sin(kx)$ o $y=a \cos(kx)$ completa un periodo cuando $kx$ va de $0 \to 2\pi$  es decir 
>[!hint] ‎‎.
> $0 \leq kx \leq 2\pi$
>$0 \leq x \leq \frac{2\pi}{k}$
### Desfase de curvas seno y coseno

Tomando $y=a\sin k(x-b)$ y $y = a\cos k(x-b)$ para $k > 0$
- Tienen amplitud $|a|$ y periodo $\frac{2\pi}{k}$ 
- Tienen desfase $b$
- un intervalo apropiado sobre el cual graficar un periodo completo es $[b, b+(\frac{2\pi}{k})]$
## References
1.[]