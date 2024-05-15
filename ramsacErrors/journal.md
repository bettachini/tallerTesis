# Cosa

## 2024-04-15

### Estaciones con problemas
AZUL CAEP MGUE MZAE RWSN

[Nevada Geodetic Laboratory GPS Networks Map](http://geodesy.unr.edu/NGLStationPages/gpsnetmap/GPSNetMap.html)

### Envío datos
Víctor.rar

## 2024-05-14
¿Plan?
- Tendencia histórica hasta una fecha dada
  - ¿Cómo se calcula? ¿Spline cúbico o un ajuste?
    - [SciPy UnivariateSpline](https://docs.scipy.org/doc/scipy/reference/generated/scipy.interpolate.UnivariateSpline.html)
- Identificar si se produce un apartamiento sea en $x, y\, \text{o}\, z$ de la tendencia que exceda los $3 \sigma$
- Si hay más de 3 en el último ciclo de cálculo (semanal) -> comparar con Nevada
  - ¿Qué día marca el inicio de la semana?
    - Lunes... ¿o domingo?
  - Hay que descargar los datos de Nevada
  - Realizar la comparación para indicar que bandera levantar si la de descarte o la de adecuación de los datos


  ### Informe de segunda entrega
Guillermo pide
1. Ilustrar los casos de diferencia o coincidencia entre Nevada y procesamiento CIGA
2. Comentar que método o métodos podrían identificar estos casos