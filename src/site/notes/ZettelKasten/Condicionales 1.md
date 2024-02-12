---
{"dg-publish":true,"permalink":"/zettel-kasten/condicionales-1/"}
---


# Condicionales 1
Creado: 2024-02-12 13:04
Tema General: [[Programacion\|Programacion]]
Tag: #Topic


___
## Ejercicio

- Como se realizaria este ejercicio sin usar condicionales.
	- Calcule los años que le faltan a alguien al retirarse, teniendo en cuenta que la edad de retiro es distinta para hombres y mujeres (62,57)
	>[!hint]- Solucion
	>
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




```cpp
#include <iostream>

  

using namespace std;

  

int main(){

    int edad;

    int esMujer;

  

    cout << "Ingrese su edad: ";

    cin >> edad;

  

    cout << "Ingrese 1 si es mujer, 0 si es hombre: ";

    cin >> esMujer;

  

    int anhos_Faltantes = 62 - edad + esMujer * 5;

  

    cout << "Le faltan " << anhos_Faltantes << " años para poder retirarse" << endl;

    return 0;

}
```

</div></div>

## Condicionales

- Son un bloque de codigo el cual dependiendo de la entrada, ejecuta algo, hay varios tipos
1. If 
	Define un bloque de codigo que va a ser ejecutado si la evaluacion de la condicion retorna Verdadero
	- La condicion debe ser una expresion booleana
	>[!example] Ejemplo
	>```py
	>if(edad>=18):
	>	print('usted es mayor de edad')
	>```
1. If-Else
2. Condicionales anidadas
3. Switch-Case

___
## References
1.