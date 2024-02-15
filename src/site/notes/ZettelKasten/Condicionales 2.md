---
{"dg-publish":true,"permalink":"/zettel-kasten/condicionales-2/"}
---


# Condicionales 2
Creado: 2024-02-14 12:58
Tema General:[[Programacion\|Programacion]]
Tag: #Topic


___
## Ejercicios en C++

1. .
 >[!hint]- Ejercicio 1
 >
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



```cpp
#include <iostream>

  

using namespace std;

  

int main(){

    float precio;

    cout << "Ingrese el precio del producto: ";

    cin >> precio;

  

    cout << "El precio con descuento es: " << precio * (precio >=100 ? 0.9 : 1)  << endl;

    return 0;

  

}
```

</div></div>

 2. .
2. .
>[!hint]- Ejercicio 2
>
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



```cpp
#include <iostream>

using namespace std;

  

int main()

{

    // Your code goes here

    float peso, altura, imc;

  

    cout << "Ingrese su peso en kg: ";

    cin >> peso;

  

    cout << "Ingrese su altura en metros: ";

    cin >> altura;

  

    imc = peso / (altura * altura);

  

    if (imc < 18.5)

    {

        cout << "Bajo peso";

    }

    if (imc >= 18.5 && imc < 25)

    {

        cout << "Normal";

    }

    if (imc >= 25 && imc < 30)

    {

        cout << "Sobrepeso";

    }

    if (imc >= 30){

        cout << "Obesidad";

    }

    return 0;

}
```

</div></div>

3. .
>[!hint]- Ejercicio 3
>
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



```cpp
#include <iostream>

  

using namespace std;

  

int main() {

    // Your code here

    long n;

    cout << "Ingrese un número: ";

    cin >> n;

  

    if (n % 2 == 0) {

        cout << "El número es par";

    }

    if(n % 2 != 0) {

        cout << "El número es impar";

    }

    return 0;

}
```

</div></div>

4. .
>[!hint]- Ejercicio 4
>
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



```cpp
#include <iostream>

  

using namespace std;

  

int main() {

    float temp;

  

    string units;

  

    cout << "Ingrese la temperatura: ";

    cin >> temp;

  

    cout << "Ingrese la unidad de la temperatura (C o F): ";

  

    cin >> units;

  

    if(units == "C"){

        cout << "La temperatura en F es: " << (temp * 9/5) + 32 << " F";

  

    }

  

    if (units == "F"){

        cout << "La temperatura en C es: " << (temp - 32) * 5/9 << " C";

    }

    return 0;

}
```

</div></div>


## Segundo tipo de condicionales

Bloque Si - Sino - Fin Si (If-Else)
- Se compone de 2 bloques de codigo, uno si  la condicion es verdadera, y uno si es falsa
>[!example] Ejemplo
>```py
>if x > 10:
>	print('El numero es mayor de 10')
>else:
>	print('El numero es menor de 10')
>```
___
## References
1.