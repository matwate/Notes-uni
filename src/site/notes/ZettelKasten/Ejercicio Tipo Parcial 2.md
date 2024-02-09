---
{"dg-publish":true,"permalink":"/zettel-kasten/ejercicio-tipo-parcial-2/"}
---


# Ejercicio Tipo Parcial 2
Creado: 2024-02-08 13:06
Tema General:[[Programacion\|Programacion]]
Tag: #Topic


___
## Solucion Problema Transmillar

> [!hint]- Solucion
>
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



```cpp
#include <iostream>

  

using namespace std;

  

float calculateFullTicketPrice(float precioNormal, float numTiquetesNormal, float numTiquetesValle, float numTiquetesPico)

{

    float precioValle = precioNormal * 0.7;

    float precioPico = precioNormal * 1.15;

    return precioNormal * numTiquetesNormal + precioValle * numTiquetesValle + precioPico * numTiquetesPico;

}

  

float sumOfArrays(float arr1[], float  arr2[], float arr3[], float arr4[])

{

    int sum = 0;

    for (int i = 0; i < 3; i++)

    {

        sum += arr1[i] + arr2[i] + arr3[i] + arr4[i];

    }

    return sum;

}

  

int main()

{

    // Your code here

    float distancia;

    float numOrdinarios[3];

    float numTerceraEdad[3];

    float numEstudiantes[3];

    float numFuerzaPublica[3];

  

    cout << "Ingrese la distancia a recorrer: ";

    cin >> distancia;

  

    cout << "Ingrese el numero de tiquetes ordinarios en hora normal: ";

    cin >> numOrdinarios[0];

  

    cout << "Ingrese el numero de tiquetes ordinarios en hora valle: ";

    cin >> numOrdinarios[1];

  

    cout << "Ingrese el numero de tiquetes ordinarios en hora pico: ";

    cin >> numOrdinarios[2];

  

    float totalOrdinarios = calculateFullTicketPrice(3000, numOrdinarios[0], numOrdinarios[1], numOrdinarios[2]);

  

    cout << "Ingrese el numero de tiquetes de tercera edad en hora normal: ";

    cin >> numTerceraEdad[0];

  

    cout << "Ingrese el numero de tiquetes de tercera edad en hora valle: ";

    cin >> numTerceraEdad[1];

  

    cout << "Ingrese el numero de tiquetes de tercera edad en hora pico: ";

    cin >> numTerceraEdad[2];

  

    float totalTerceraEdad = calculateFullTicketPrice(2000, numTerceraEdad[0], numTerceraEdad[1], numTerceraEdad[2]);

  

    cout << "Ingrese el numero de tiquetes de estudiantes en hora normal: ";

    cin >> numEstudiantes[0];

  

    cout << "Ingrese el numero de tiquetes de estudiantes en hora valle: ";

    cin >> numEstudiantes[1];

  

    cout << "Ingrese el numero de tiquetes de estudiantes en hora pico: ";

    cin >> numEstudiantes[2];

  

    float totalEstudiantes = calculateFullTicketPrice(2100, numEstudiantes[0], numEstudiantes[1], numEstudiantes[2]);

  

    cout << "Ingrese el numero de tiquetes de la fuerza publica en hora normal: ";

    cin >> numFuerzaPublica[0];

  

    cout << "Ingrese el numero de tiquetes de la fuerza publica en hora valle: ";

    cin >> numFuerzaPublica[1];

  

    cout << "Ingrese el numero de tiquetes de la fuerza publica en hora pico: ";

    cin >> numFuerzaPublica[2];

    float totalFuerzaPublica = calculateFullTicketPrice(1500, numFuerzaPublica[0], numFuerzaPublica[1], numFuerzaPublica[2]);

    int galonesPorKm = 10;

  

    int precioPorGalon = 10000;

  

    float salarioChofer = 100000 + 500 * distancia;

  

    float costoViaje = (galonesPorKm * distancia * precioPorGalon) + salarioChofer;

  

    cout << "El costo total del viaje es: " << costoViaje << endl;

  

    cout << "El ingreso por tiquetes ordinarios fue: " << totalOrdinarios << endl;

  

    cout << "El ingreso por tiquetes de tercera edad fue: " << totalTerceraEdad << endl;

  

    cout << "El ingreso por tiquetes de estudiantes fue: " << totalEstudiantes << endl;

  

    cout << "El ingreso por tiquetes de la fuerza publica fue: " << totalFuerzaPublica << endl;

  

    float porcentajeGanancia = (totalOrdinarios + totalTerceraEdad + totalEstudiantes + totalFuerzaPublica - costoViaje) / sumOfArrays(numOrdinarios, numTerceraEdad, numEstudiantes, numFuerzaPublica) * 100;

    cout << "El porcentaje de ganancia fue: " << porcentajeGanancia << "%" << endl;

    return 0;

}
```

</div></div>

___
## References
1.