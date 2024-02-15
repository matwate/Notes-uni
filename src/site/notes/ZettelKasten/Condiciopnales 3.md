---
{"dg-publish":true,"permalink":"/zettel-kasten/condiciopnales-3/"}
---


# Condiciopnales 3
Creado: 2024-02-15 13:10
Tema General:[[Programacion\|Programacion]]
Tag: #Topic


___
## Ejercicios
1. Identifique si un triangulo es equilatero, escaleno o isoceles
>[!hint]- Solucion
>
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



```cpp
#include <iostream>

using namespace std;

  
  

int main() {

    int a, b, c;

  

    cout << "Ingrese la longitud del primer lado: ";

    cin >> a;

  

    cout << "Ingrese la longitud del segundo lado: ";

    cin >> b;

    cout << "Ingrese la longitud del tercer lado: ";

    cin >> c;

  

    if (a == b && b == c) {

        cout << "Equilátero";

    }else if(a == b || b == c || a == c){

        cout << "Isósceles";

    }else{

        cout << "Escaleno";

    }

    return 0;

}
```

</div></div>


2. Haga un Piedra Papel, Tijeras, Lagarto, Spock
>[!hint]- Solucion
>
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



```cpp
#include <iostream>

#include <cstdlib> // For generating random numbers

  

using namespace std;

  

int main() {

    int userChoice;

    int computerChoice;

    string choices[5] = {"Papel", "Piedra", "Lagarto", "Spock", "Tijeras"};

    srand(time(0));

    computerChoice = rand() % 4;

  

    cout << "Escoja su jugada: 0: Papel 1: Piedra 2: Lagarto: 3: Spock 4: Tijeras: ";

    cin >> userChoice;

    if (userChoice == computerChoice) {

        cout << "Empate";

    } else if ((userChoice + 6) % 5 == computerChoice || (userChoice + 8) % 5 == computerChoice) {

        cout << "Ganaste, la computadora escogio:"<< choices[computerChoice] << " y tu escogiste: " << choices[userChoice] << " " << endl;

    } else {

        cout << "Perdiste, La computadora escogio: " << choices[computerChoice] << " y tu escogiste: " << choices[userChoice] << " " << endl;

    }

    return 0;

}
```

</div></div>



___
## References
1.