# Curso de iniciacion de QlikSense
Recursos para el curso de QlikSense, dentro de las carpetas de cada app vamos a encontrar:
* Fuentes dentro de la carpta **source** que seran CSV, Excel o QVD.
* Mockup del cuadro de mando que vamos realizar.
* El fichero final con los datos incluidos (fichero qvf).
* Otros recursos o Ejemplos

## Mi primera App 
En esta primera App vamos a realizar una app muy sencilla mediante los menus y las guias automaticas que nos da QlikSense. Y veremos la interfaz que nos propociona el cloud.

![Mi primera App](https://github.com/ravamo/qliksense_iniciacion/blob/master/PrimeraApp/App_1.png?raw=true)


## Mi segunda App 
En esta segunda App tendremos componentes mas complejos como mapas , asi como personalizar la app con colores , etc..

![Mi segunda App](https://github.com/ravamo/qliksense_iniciacion/blob/master/SegundaApp/App_2.png?raw=true)


## Mi tercera App 
En la tercera App vamos a ver algunos graficos interesantes y como personalizar.

![Mi tercera App Hoja 1](https://github.com/ravamo/qliksense_iniciacion/blob/master/TerceraApp/App_3_Hoja_1.png?raw=true)
![Mi tercera App Hoja 2](https://github.com/ravamo/qliksense_iniciacion/blob/master/TerceraApp/App_3_Hoja_2.png?raw=true)

## Mi cuarta App 
En este app vamos a realizar Optimizaciòn de modelo y Set Analysis, Identificadores de Conjunto,Operaciones de Conjunto y  la función Aggr.

## Mi quinta App 
Modelado avanzado 54. Referencia Circular, NoConcatenate, Qualify y Unqualify

## Ejemplos
Ejemlo de comtenedor, calculo de columnas (tabla simple o pivot table), Base para el setAnalysis y Operaciones de conjunto, ademas de la manera de programar una carga. 

![Ejemplos](https://github.com/ravamo/qliksense_iniciacion/blob/master/Ejemplos/QlikSenseScheduler.gif?raw=true)

### Video de como generar un TOP10 o similar en QlikSense
![Ejemplos](https://github.com/ravamo/qliksense_iniciacion/blob/master/Ejemplos/Top10.gif?raw=true)

## Video de como sacar el Id de una cantidad Maxima usando aggr function (Gracias a Carmelo Santana)

![Ejemplos](https://github.com/ravamo/qliksense_iniciacion/blob/master/Ejemplos/getEmpleadoIdForMax.gif?raw=true)

```
=Max(if(Aggr(sum(Cantidad),EmpleadoId) >= max(total aggr(sum(Cantidad),EmpleadoId)), EmpleadoId, 0))

```
