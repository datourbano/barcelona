### [datourbano](https://github.com/datourbano): Puntos de Recarga de vehículos eléctricos - Barcelona (España)

* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/ubicacion_18.png) Ciudad: [Barcelona (España)](https://datourbano.github.io/barcelona)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/origen_18.png) Origen: [Servicio de datos abiertos del Ayuntamiento de Barcelona (OpenDataBCN)](http://opendata-ajuntament.barcelona.cat/data/es/dataset/punts-recarrega-vehicles-electrics)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/calendario_18.png) Fecha: 01-03-2017
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/carpeta_18.png) Repositorio: https://github.com/datourbano/barcelona/tree/master/servicios/recarga/vehiculos
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/enlace_18.png) LinkedData: [08019_punts_recarrega_vehicles_electrics_bcn_ciutat.geojson](https://raw.githubusercontent.com/datourbano/barcelona/master/servicios/recarga/vehiculos/08019_punts_recarrega_vehicles_electrics_bcn_ciutat.geojson)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/mapa_18.png) Visualización: [Puntos de Recarga de vehículos eléctricos - Barcelona (España)](https://datourbano.github.io/barcelona/servicios/recarga/vehiculos/08019_punts_recarrega_vehicles_electrics_bcn_ciutat)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/notas_18.png) Notas:

  (Portal de datos abiertos del Ayuntamiento de Madrid)
  >"Geolocalización de estaciones de recarga de vehiculo eléctrico. Mantenimiento asegurado sólo de los puntos de recarga de propiedad pública. No se proporciona información referente al estado del servicio."
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/herramienta_18.png) Tratamiento:

  Los datos originales se encuentran en formato CSV.

  El fichero cuenta con dos atributos para la georreferenciación de las instalaciones: *"COORDENADA_X"* y *"COORDENADA_Y"*, que almacenan el valor de las coordenadas geográficas WGS84 del punto, si bien se observa que el orden está invertido, ya que se registra en el atributo *COORDENADA_X* el valor de la *latitud* y en el atributo *COORDENADA_Y* el valor de la *longitud* (1).

  Se ha convertido el archivo shapefile a un fichero GeoJSON, manteniendo la estructura de datos original y su contenido.

  Los datos finales se ofrecen en coordenadas geográficas OGC CRS:84 (EPSG:4326 lon-lat).

  Codificación de caracteres: UTF8

  Se observa en la georreferenciación de los puntos, una exactitud geográfica variable.

  (1) Posiblemente el error de orden se deba a que al expresar la ubicación de un punto mediante coordenadas geográficas, suele ser práctica habitual indicar primero el valor de la *latitud* y después el de la *longitud*.  

