### [datourbano](https://github.com/datourbano): Puntos de acceso Wifi - Barcelona (España)

* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/ubicacion_18.png) Ciudad: [Barcelona (España)](https://datourbano.github.io/barcelona)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/origen_18.png) Origen: [Servicio de datos abiertos del Ayuntamiento de Barcelona (OpenDataBCN)](http://opendata-ajuntament.barcelona.cat/data/es/dataset/punts-wifi)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/calendario_18.png) Fecha: 16-02-2017
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/carpeta_18.png) Repositorio: https://github.com/datourbano/barcelona/tree/master/servicios/comunicaciones/wifi
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/enlace_18.png) LinkedData: [28079_wifi_municipal.geojson](https://raw.githubusercontent.com/datourbano/barcelona/master/servicios/comunicaciones/wifi/08019_punts_wifi.geojson)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/mapa_18.png) Visualización: [Puntos de acceso Wifi - Barcelona (España)](https://datourbano.github.io/barcelona/servicios/comunicaciones/wifi/08019_punts_wifi)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/notas_18.png) Notas:
  
  (Servicio de datos abiertos del Ayuntamiento de Barcelona (OpenDataBCN)
  >Puntos de acceso WiFi ubicados en varios equipamientos municipales y puntos en medio de la vía pública. 
  >
  >|Nombre columna|Descripción
  >|:---|:---
  >|ADRECA|Dirección
  >|BARRI|Número de barrio
  >|CAPA_GENERICA|Nombre de capa genérica a la que pertenece la subcapa
  >|CODI_CAPA|Identificador único de la capa.</br>Es una letra mayúscula, seguida de tres números (A001, A002, B001…)
  >|DISTRICTE|Número de distrito
  >|ED50_COORD_X|Coordenada x de las coordenadas UTM31 en la proyección ED50
  >|ED50_COORD_Y|Coordenada y de les coordenadas UTM31 en la proyección ED50
  >|EQUIPAMENT|Nombre del equipamiento
  >|ETRS89_COORD_X|Coordenada x en la proyección ETRS89
  >|ETRS89_COORD_Y|Coordenada y en la proyección ETRS89
  >|LATITUD|Latitud en coordenadas geográficas
  >|LONGITUD|Longitud en coordenadas geográficas
  >|NOM_BARRI|Nombre de barrio
  >|NOM_CAPA|Texto del nombre de la capa en catalán.</br>Este texto aparece en la leyanda del mapa
  >|NOM_DISTRICTE|Nombre de distrito
  >|TELEFON|Teléfono

* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/herramienta_18.png) Tratamiento:
  
  Los datos originales se encuentran en formato CSV, con indicación de su posición mediante dos pares de coordenadas X,Y en los sistemas geográficos de referencia *UTM European 1950 31N* y *UTM ETRS89 31N*.

  Se han extraído los elementos del fichero CSV, almacenándose todos ellos en un fichero GeoJSON, manteniendo su estructura original (no coincide con lo indicado en el OpenData) y contenido.

  Los datos finales se ofrecen en coordenadas geográficas OGC CRS:84 (EPSG:4326 lon-lat).

  Se ha realizado un muestreo aleatorio de la precisión y exactitud geográfica, no habiéndose detectado problemas de posicionamiento.