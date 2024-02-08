---
{"dg-publish":true,"permalink":"/zettel-kasten/ejercicio-tipo-parcial/"}
---


# Ejercicio Tipo Parcial
Creado: 2024-02-07 13:04
Tema General:[[Programacion\|Programacion]]
Tag: #Topic


___
#### Enunciado.

-  [Documento en e-aulas](https://e-aulas.urosario.edu.co/pluginfile.php/3079673/mod_resource/content/1/Ejercicio_Presupuesto.pdf)
>[!hint]- Solucion 
>
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



```cpp
#include <iostream>

using namespace std;

  

float calculateWages(int NumPeople, float valueHour, int monthsWorked, int dedicationWeek)

{

    return NumPeople * valueHour * monthsWorked * dedicationWeek * 4;

}

  

float calculateTravel(int numTrips, int numPeople, float valueTickets, float valueLodging, int numDays)

{

    return numTrips * valueLodging * numDays + (valueTickets * numPeople * numTrips);

}

int main()

{

  

    int numInvestigadores;

  

    cout << "Ingrese el numero de investigadores: ";

    cin >> numInvestigadores;

  

    float valorHoraInvs;

  

    cout << "Ingrese el valor de la hora de los investigadores: ";

    cin >> valorHoraInvs;

  

    int mesesTrabajadosInvs;

  

    cout << "Ingrese el numero de meses trabajados por los investigadores: ";

    cin >> mesesTrabajadosInvs;

  

    int dedicacionSemanalInvs;

  

    cout << "Ingrese la dedicacion semanal de los investigadores: ";

    cin >> dedicacionSemanalInvs;

  

    int numAsistentes;

  

    cout << "Ingrese el numero de asistentes de investigacion: ";

    cin >> numAsistentes;

  

    float valorHoraAsistentes;

  

    cout << "Ingrese el valor de la hora de los asistentes: ";

    cin >> valorHoraAsistentes;

  

    int mesesTrabajadosAsistentes;

  

    cout << "Ingrese el numero de meses trabajados por los asistentes: ";

    cin >> mesesTrabajadosAsistentes;

  

    int dedicacionSemanalAsistentes;

  

    cout << "Ingrese la dedicacion semanal de los asistentes: ";

    cin >> dedicacionSemanalAsistentes;

  

    float valorTotalEquipos;

  

    cout << "Ingrese el valor total de los equipos: ";

    cin >> valorTotalEquipos;

  

    int numViajes;

  

    cout << "Ingrese el numero de viajes: ";

    cin >> numViajes;

  

    int numPersonasViaje = numInvestigadores + numAsistentes;

  

  

    float valorTiquetes;

  

    cout << "Ingrese el valor de los tiquetes: ";

    cin >> valorTiquetes;

  

    int valorHospedaje;

  

    cout << "Ingrese el valor del hospedaje: ";

    cin >> valorHospedaje;

  

    int numDiasViaje;

  

    cout << "Ingrese el numero de dias de viaje: ";

    cin >> numDiasViaje;

  

    int subtotalInvestigadores = calculateWages(numInvestigadores, valorHoraInvs, mesesTrabajadosInvs, dedicacionSemanalInvs);

    int subtotalAsistentes = calculateWages(numAsistentes, valorHoraAsistentes, mesesTrabajadosAsistentes, dedicacionSemanalAsistentes);

    int subtotalViajes = calculateTravel(numViajes, numPersonasViaje, valorTiquetes, valorHospedaje, numDiasViaje);

    int subtotal = subtotalAsistentes + subtotalInvestigadores + valorTotalEquipos + subtotalViajes;

    cout << "El valor de los salarios de los investigadores es: " << subtotalInvestigadores << endl;

    cout << "El valor de los salarios de los asistentes es: " << subtotalAsistentes << endl;

    cout << "El valor de los equipos es: " << valorTotalEquipos << endl;

    cout << "El valor de los viajes es: " << subtotalViajes << endl;

    cout << "Subtotal:" << subtotal << endl;

  

    int totalGastosAdministrativos = subtotal * 0.3;

    cout << "El valor de los gastos administrativos es: " << totalGastosAdministrativos << endl;

    int valorTotalSinIva = subtotal + totalGastosAdministrativos;

    cout << "El valor total sin IVA es: " << valorTotalSinIva << endl;

  

    int valorFinalProyecto =  valorTotalSinIva * 1.19;

    cout << "El valor final del proyecto es: " << valorFinalProyecto << endl;

  

    return 0;

}
```

</div></div>


___
## References
1.