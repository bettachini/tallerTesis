# Taller de tesis 1

## Enlaces
[Frontispicio](https://tallerdetesis1-2024.netlify.app/)
[Cronograma](https://tallerdetesis1-2024.netlify.app/cronograma)
Martes de 19 a 22hs. https://exactas-uba.zoom.us/j/86457673848 [exactas-uba.zoom.us] ID de reunión: 864 5767 3848 Código de acceso: tti24-sur

## Docentes
Guillermo Solovey - gsolovey@gmail.com
Ian Bounos - bounosian@gmail.com
Daniela Parada - dparada@dm.uba.ar


## Terremotos
https://daniellaparada.github.io/IC-datasets-docencia/04_visualizacion.html

### 2024-06-18 Entrega III
Date: Tue, 18 Jun 2024 23:59:09 -0300 (-03)
From: Victor A. Bettachini <bettachini@gmail.com>
To: gsolovey@gmail.com, bounosian@gmail.com, dparada@dm.uba.ar
Subject: Taller de tesis | Entrega III (debo la II)

Hola Daniela, Ian, Guillermo.

Estoy en el grupo 3 y hoy hice mi envío para la entrega III correspondiente a "Introducción y resultados".

Tras no haber realizado la entrega II "Metodología y análisis exploratorio de datos" hice la III incluyendo esos puntos, pero debo reconocer casi carente de resultados.No hice ni la mitad de lo que puede hacerse con una de las
técnicas con que me propuse trabajar y ni comencé con la segunda.

Si algo estoy entregado es gracias al trabajo de Daniela en compilar el dataset de sismos y por la sugerencias que ella me dió de ideas para trabajar con él durante la última clase (nuevamente, ¡gracias!).

De más está decir que no hay excusa para mi desempeño este cuatrimestre, pero aún así les agradeceré cualquier instrucción de como seguir, aunque sea para tener una mejor base al recursar. En particular, ¿empaqueto lo que escribí en
el pdf de la entrega III sobre "Metodología y EDA" en una entrega II tardía? Esto es, si es que aún pudieran darme sugerencias sobre estas temáticas.

Hasta pronto.




### 2024-06-04
Opciones
1.Clasificar si fueron percibidos
	- cercanía zona urbana (distancia a ciudad más próximo)
	- intensidad
	- profundidad
1. Correlación
- coordenadas con intensidad (e.g. si más al oeste, cerca de la cordillera son más presentes)
1. Tiempo de ocurrencia entre eventos por sobre cierta intensidad



A un mes -> todo
dos semanas -> ¿Qué se va a responder? ¿Con que dos técnicas voy a atacarle?




## Rios
9 promedios de revisitas cada 16 min -> 144 min (1/10 día)
Genera nuevas dif_REFGPS de 16 min por (modelo lineal) promedio ponderado con REF_GPS y las otras observaciones que tienen información ionosférica y de parámetros internos GNSS para las dos observaciones.
Previo a eso hace una limpieza de estos parámetros.
Parámetros: 



## Dataset
Registros CGGTS y RINEX INTI, IGN, AGGO que se almacena en aggo-conicet.gov.ar/rnt


## Pregunta 
¿Se puede extender a tiempo de "revisita" de 16 minutos entre centros dispersos?
Pero no tan dispersos, la predicción ionosférica debiera valer para todos.
¿Podemos evidenciar cambias troposféricos.





## Objetivo
Aplicar lo que se hizo para dos receptores cercanos con los separados.


## 2024-03-26
- Probar otros modelos de regresión. E.g. logísticos. O probar modificaciones al modelo lineal, e.g. regularizaciones varias.
- Usar más datos (otras constelaciones, múltiples bandas, algo que expanda el espacio de parámetros)



## NEU

### Dataset
Nos interesan los rms
Que son las de la RAMSAC


- azul en las tres coordenadas están dentro de los tres \sigma
- celeste alguna se salió de 3 \sigma

### Pregunta
Contrastar diferencias  series de tiempo procesamiento con órbitas transmitidas (CIGA) y postprocesamiento Nevada con órbitas corregidas.

¿Algún desacuerdo parte de los datos o el procesamiento CIGA?

- Problema físico antena
- 

Contralor contra un procesamiento externo, el del centro de Nevada
-> Definir origen del problema

#### Que se hace ahora
1. se calcula la serie de tiempo
2. verifica rango de fechas el número de outliers (consulta SQL) -> lista de estaciones en ofensa
3. luego se visualizan los gráfico del procesamiento local y se compara visualmente con la de Nevada
4. si "coinciden" problema en los datos, si no una diferencia atribuible al procesamiento 
 

### 

