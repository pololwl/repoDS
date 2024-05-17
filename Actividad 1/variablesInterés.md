# Variables de interés por base de datos

## AmesHousing.csv

- `SalePrice` (Precio de venta): Como variable objetivo, el precio de venta es fundamental para cualquier análisis relacionado con el mercado inmobiliario.
- `Neighborhood` (Vecindario): La ubicación y el vecindario pueden tener un impacto significativo en el valor de una propiedad.
- `Overall Qual` (Calidad general): Una medida de la calidad general de la vivienda podría ser un fuerte predictor del precio de venta.
- `Year Built` (Año de construcción) y `Year Remod/Add` (Año de remodelación/adición): La edad de la vivienda y las renovaciones recientes pueden influir en su valor.
- `Gr Liv Area` (Área habitable): El tamaño de la vivienda es otro factor importante que suele afectar el precio.
- `Bsmt SF` (Superficie del sótano) y `Total Bsmt SF` (Superficie total del sótano): Si está terminado y en buenas condiciones, un sótano puede agregar valor a una propiedad.
- `Bedroom AbvGr` (Dormitorios sobre el nivel del suelo) y `Full Bath` (Baños completos): El número de dormitorios y baños son características clave que los compradores suelen buscar.
- `Garage Cars` (Capacidad del garaje en términos de automóviles) y `Garage Area` (Área del garaje): Un garaje, especialmente si es grande, puede ser un punto de venta importante.
- `Lot Area` (Área del lote): El tamaño del lote en el que se encuentra la vivienda también puede afectar su valor.
- `MS Zoning` (Zonificación): La zonificación puede influir en el valor de una propiedad al dictaminar su uso potencial.

## attacks.csv

- `Type` (Tipo de ataque): Esta variable podría brindar información sobre los diferentes tipos de interacciones entre tiburones y humanos, como ataques provocados, no provocados o encuentros sin daños. Analizar esta variable podría ayudar a comprender mejor las circunstancias en las que ocurren los ataques.
- `Activity` (Actividad): Conocer la actividad que estaba realizando la víctima en el momento del ataque (por ejemplo, surfing, buceo, nado, etc.) podría revelar patrones sobre qué actividades tienen un mayor riesgo de encuentros con tiburones. Esta información podría ser útil para la prevención y la concientización.
- `Fatal (Y/N)` (Mortal Sí/No): Analizar la proporción de ataques mortales y no mortales podría brindar una perspectiva sobre la gravedad de estos encuentros. Además, se podría explorar si existe alguna relación entre la fatalidad y otras variables como el tipo de ataque o la actividad realizada.
- `Species` (Especie): Identificar las especies de tiburones involucradas en los ataques podría revelar si algunas especies son más propensas a interactuar con humanos que otras. Esta información podría ser útil para la conservación y el manejo de las poblaciones de tiburones.
- `Location` (Ubicación) y `Area` (Área): Estas variables geográficas podrían ayudar a identificar puntos calientes donde ocurren con mayor frecuencia los ataques de tiburones. Analizar la ubicación y el área también podría revelar si existen factores ambientales o humanos que influyen en la probabilidad de encuentros con tiburones.
- `Time` (Hora) y `Date` (Fecha): Explorar los patrones temporales de los ataques, como la hora del día, la estación o incluso las tendencias a lo largo de los años, podría proporcionar información valiosa sobre los factores que influyen en la frecuencia de los ataques de tiburones.

## suicide_rates_1990-2022.csv

- `SuicideCount` (Recuento de suicidios): Esta variable representa el número total de suicidios y es fundamental para cualquier análisis sobre el tema.
- `DeathRatePer100K` (Tasa de mortalidad por 100,000 habitantes): Esta variable normaliza el recuento de suicidios según la población, permitiendo comparaciones entre diferentes países y regiones.
- `Sex` (Sexo): Analizar las tasas de suicidio por género podría revelar disparidades importantes y ayudar a identificar poblaciones en riesgo.
- `GDPPerCapita` (PIB per cápita) y `GNIPerCapita` (INB per cápita): Estas variables son medidas de la riqueza económica de un país y podrían utilizarse para explorar la relación entre el desarrollo económico y las tasas de suicidio.
- `EmploymentPopulationRatio` (Ratio empleo/población): El desempleo ha sido asociado con un mayor riesgo de suicidio, por lo que esta variable podría ser relevante.
- `InflationRate` (Tasa de inflación): La inestabilidad económica, reflejada en altas tasas de inflación, podría estar relacionada con el estrés mental y potencialmente con las tasas de suicidio.
- `Year` (Año): Analizar las tendencias a lo largo del tiempo podría revelar patrones interesantes y ayudar a identificar eventos o cambios de política que puedan haber influido en las tasas de suicidio.
- `CountryName` (Nombre del país) y `RegionName` (Nombre de la región): Estas variables permitirían un análisis a nivel de país y región, que podría revelar variaciones geográficas en las tasas de suicidio y los factores socioeconómicos.