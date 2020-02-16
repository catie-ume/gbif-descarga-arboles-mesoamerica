# Descarga del portal de GBIF de los registros de presencia de especies de árboles de Mesoamérica
Este repositorio contiene el procedimiento para la descarga, del portal de la [Infraestructura Mundial de Información en Biodiversidad (GBIF)](https://www.gbif.org/), de los registros de presencia de especies de árboles presentes en Mesoamérica. El procesamiento se realiza a través de un [Jupyter Notebook](https://jupyter.org/), desarrollado en el lenguaje de programación [Python](https://www.python.org/).

El _notebook_ recibe como entrada una lista de nombres científicos de especies en formato CSV y genera una consulta en el portal de GBIF que permite descargar los registros de presencia correspondientes. Además, se genera para cada especie un archivo CSV separado.

Para ejecutar el _notebook_, se recomienda utilizar versión de Jupyter incluida en la plataforma [Anaconda](https://www.anaconda.com/) para ciencia de datos.

**1. Clonación del repositorio**
```terminal
$ git clone https://github.com/gbif-descarga-arboles-mesoamerica.git
$ cd gbif-descarga-arboles-mesoamerica
```

**2. Ejecución del _notebook_**
Luego, debe abrirse y ejecutarse, con la interfaz de Jupyter, el _notebook_ llamado [descarga-registros-presencia-gbif.ipynb](https://github.com/catie-ume/gbif-descarga-arboles-mesoamerica/blob/master/descarga-registros-presencia-gbif.ipynb). Siga las instrucciones contenidas en el _notebook_.
