### [datourbano](https://github.com/datourbano): Punts d'ancoratge de bicicletes / Puntos de anclaje de bicicletas - Barcelona

* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/ubicacion_18.png) Ciudad: [Barcelona](https://datourbano.github.io/barcelona)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/origen_18.png) Origen: [Servicio de datos abiertos del Ayuntamiento de Barcelona (OpenDataBCN)](http://opendata-ajuntament.barcelona.cat/data/es/dataset/punts-ancoratge-bicicletes)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/calendario_18.png) Fecha: 12-10-2017
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/carpeta_18.png) Repositorio: https://github.com/datourbano/barcelona/tree/master/movilidad/bici/vialidad
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/enlace_18.png) LinkedData: [08019_punts_ancoratge_bicicletes.geojson](https://raw.githubusercontent.com/datourbano/barcelona/master/movilidad/bici/vialidad/08019_punts_ancoratge_bicicletes.geojson)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/mapa_18.png) Visualización: [Puntos de anclaje de bicicletas - Barcelona](https://datourbano.github.io/barcelona/movilidad/bici/vialidad/08019_punts_ancoratge_bicicletes)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/notas_18.png) Notas:

  (Servicio de datos abiertos del Ayuntamiento de Barcelona)
  >Puntos de anclaje de bicicletas de la ciudad de Barcelona.
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/herramienta_18.png) Tratamiento:

  Los datos originales se han descargado en un formato XML que internamente incluye información específica de *Google Maps*. 

    Se han completado los atributos los relativos a *urls* con la cadena del dominio, con el fin de poderlos reutilizar como enlaces directos.

  Se ha convertido el archivo XML a un fichero GeoJSON, intentando conservar al máximo la estructura de datos original y su contenido.

  Los datos finales se ofrecen en formato GeoJSON, en el sistema de coordenadas geográficas OGC CRS:84 (EPSG:4326 lon-lat), con una precisión de seis decimales de grado y una codificación de caracteres UTF8, manteniéndose todo el conjunto de atributos asociados.

  Primera versión: 05-03-2017  
  >La tabla que se ofrece en el fichero, presenta una disrupción en el número 897, al incorporar un registro *fantasma* que duplica, sin datos de coordenadas, el punto ubicado en C Ramon Trias Fargas 24, lo que puede suponer una dificultad para el tratamiento automatizado de los datos.  
  >Se han eliminado atributos que ofrecen información redundante.

  Segunda versión: 12-10-2017  
  >Se ha estandarizado la precisión geométrica, expresando las coordenadas con seis decimales de grado. 
  >Importante incremento del número de puntos, que en muchos casos se ubican junto a puntos existentes en la versión anterior.  
  >En todos los puntos se aprecia una modificación de posición respecto a los puntos de la versión anterior, siendo significativa en algunos casos.  
  >Se conserva el conjunto completo de atributos del fichero origen.  

