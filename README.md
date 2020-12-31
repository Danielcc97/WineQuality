# Wine Quality

Versión definitiva de la práctica 2 (Limpieza y Análisis de datos) de la asignatura Tipología y ciclo de vida de los datos del Máster en Ciencia de Datos en la Universitat Oberta de Catalunya. Se aplican técnicas de limpieza y análisis de datos mediante el lenguaje de programación R para extraer así conclusiones del dataset que se encuentra en el repositorio UCI Machine Learning Repository sobre la [calidad de vinos](https://archive.ics.uci.edu/ml/datasets/Wine+Quality). Esta práctica se centra en utilizar una serie de técnicas para elaborar un clasificador entre vinos rojos y blancos, con el fin de conocer cuáles son las propiedades características de cada uno de los tipos de vinos disponibles. Cabe destacar que esta acciónes muy importante para empresas que elaboran vinos y buscan mejorar su productos.


### Instalación 🔧

Para ejecutar el proyecto se necesita de las siguientes librerías:

```
library(corrplot)
library(caret)
library(pROC)
library(nortest)

pip install requests
pip install time
pip install tqdm
pip install urlparse
```

### Descripción de los ficheros 📋

* **dcervino_PRA2.Rmd**: Desarrollo de cada uno de los apartados de la práctica.
* **dcervino_PRA2.pdf**: Contenido del desarrollo de los apartados de la práctica en formato PDF.
* **dcervino_PRA2_Resumen.pdf**: Resumen del contenido de la práctica.
* **modelC50.pdf**: Se trata del árbol de decisión generado por el algoritmo basado en la función C5.0.

## Despliegue-Ejecución 📦

Descargar el fichero dcervino_PRA2.Rmd y ejecutarlo.

## Build with 🛠️

* [R](https://www.r-project.org/about.html) - R is a language and environment for statistical computing and graphics.

## Authors ✒️

* **Daniel Laureano Cerviño Cortínez** - *-* - [Danielcc97](https://github.com/Danielcc97)

## DOI 📖

Esta práctica ha sido registrado con el DOI: [10.5281/zenodo.4408489](https://doi.org/10.5281/zenodo.4408489)

## Referencias 🖇️

* Joaquín Amat Rodrigo, 2017. Recuperado de https://rpubs.com/Joaquin_AR/287787
* Analytics Vidhya, 2016. Recuperado de https://www.analyticsvidhya.com/blog/2016/03/pca-practical-guide-principal-component-analysis-python/
* Jake VanderPlas, 2016. Recuperado de https://jakevdp.github.io/PythonDataScienceHandbook/05.09-principal-component-analysis.html
* Linh Ngo, 2018. Recuperado de https://blog.bioturing.com/2018/06/18/how-to-read-pca-biplots-and-scree-plots/
* Hatcher & Stepansky, 1994. Recuperado de https://www.researchgate.net/profile/Ehsan_Khedive/post/How_many_components_can_I_retrieve_in_principal_component_analysis/attachment/59d626f2c49f478072e9b1be/AS%3A272185124425729%401441905398541/download/Principal+Component+Analysis+SAS.pdf
* Laia Subirats Maté, Diego Oswaldo Pérez Trenar & Mireia Calvo González, 2019. Recuperado de http://materials.cv.uoc.edu/daisy/Materials/PID_00265704/pdf/PID_00265704.pdf
* Joseph Rickert, 2019. Recuperado de https://rviews.rstudio.com/2019/03/01/some-r-packages-for-roc-curves/
* Paulo Cortez, A.Cerdeira, F.Almeida,T.Matos & J.Reis, 2009. Recuperado de https://archive.ics.uci.edu/ml/datasets/Wine+Quality

## License 📄

Released Under CC0: Public Domain License
