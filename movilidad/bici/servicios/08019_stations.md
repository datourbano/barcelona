### [datourbano](https://github.com/datourbano): Estacions de Bicing / Estaciones de Bicing - Barcelona

* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/ubicacion_18.png) Ciudad: [Barcelona](https://datourbano.github.io/barcelona)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/origen_18.png) Origen: [Servicio de datos abiertos del Ayuntamiento de Barcelona (OpenDataBCN)](http://opendata-ajuntament.barcelona.cat/data/es/dataset/bicing)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/calendario_18.png) Fecha: 07-10-2017
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/carpeta_18.png) Repositorio: https://github.com/datourbano/barcelona/tree/master/movilidad/bici/servicios
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/enlace_18.png) LinkedData: [08019_stations.geojson](https://raw.githubusercontent.com/datourbano/barcelona/master/movilidad/bici/servicios/08019_stations.geojson)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/mapa_18.png) Visualización: [Estaciones de Bicing (mecánicas y eléctricas) - Barcelona](https://datourbano.github.io/barcelona/movilidad/bici/servicios/08019_stations)
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/notas_18.png) Notas:

  (Servicio de datos abiertos del Ayuntamiento de Barcelona)
  >Ubicación (coordenadas lat-long) de las estaciones de bicing (transporte en bicicleta). Incluye la dirección (calle y número), listado de las estaciones más próximas, estado de la estación, número de aparcamientos y número de bicis, mecánicas y electricas, disponibles.
* ![](https://raw.githubusercontent.com/datourbano/simbologia/master/_/herramienta_18.png) Tratamiento:

  Los datos originales se han descargado en formato JSON. 

  Para su tratamiento es necesario tener en cuenta que la codificación del texto es conforme UNICODE.

  Se ha convertido el archivo JSON a un fichero GeoJSON, manteniendo la estructura de datos original.

  Los datos finales se ofrecen en coordenadas geográficas OGC CRS:84 (EPSG:4326 lon-lat), con una codificación de caracteres: UTF8

  En la georreferenciación de los puntos se observa una exactitud geográfica variable.
  
  Primera versión: 03-03-2017
  Segunda versión: 07-10-2017
  >Se ha normalizado el contenido de los campos: `streetName` y `streetNumber`, homogeneizando el uso de mayúsculas/minúsculas y sustituyendo el valor original por el nombre oficial de la vía.
  >
  >En la georreferenciación de los puntos se observa una exactitud geográfica variable.
