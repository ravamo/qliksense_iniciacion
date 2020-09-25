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
Modelado avanzado :
* Referencia Circular
* NoConcatenate
* 3Qualify y Unqualify

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

### Set configuration
```
SET ThousandSep='.';
SET DecimalSep=',';
SET MoneyThousandSep='.';
SET MoneyDecimalSep=',';
SET MoneyFormat='#.##0,00 €;-#.##0,00 €';
SET TimeFormat='h:mm:ss';
SET DateFormat='D/M/YYYY';
SET TimestampFormat='D/M/YYYY h:mm:ss[.fff]';
SET FirstWeekDay=0;
SET BrokenWeeks=0;
SET ReferenceDay=4;
SET FirstMonthOfYear=1;
SET CollationLocale='es-ES';
SET MonthNames='ene.;feb.;mar.;abr.;may.;jun.;jul.;ago.;sept.;oct.;nov.;dic.';
SET LongMonthNames='enero;febrero;marzo;abril;mayo;junio;julio;agosto;septiembre;octubre;noviembre;diciembre';

```

### Demos
Aqui os pongo un link a los cuadros de mando mas complejos que nos brinda [Qlik](http://demo.qlik.com/) , todas las hojas se pueden duplicar y editar , para el resto de acciones o efectos tienes que programar en js y css 

### Seguridad 
Os adjunto unos videos donde se explica muy muy bien todo lo relacionado con la seguridad.
[![Video Seguridad I](http://i3.ytimg.com/vi/vkCh_t1nd40/maxresdefault.jpg)](https://www.youtube.com/watch?v=vkCh_t1nd40&ab)
[![Video Seguridad II](http://i3.ytimg.com/vi/_GYC2l8e0FE/maxresdefault.jpg)](https://www.youtube.com/watch?v=_GYC2l8e0FE&t)

