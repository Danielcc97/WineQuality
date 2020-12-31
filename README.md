# WineQuality

Versión definitiva de la práctica 2 (Limpieza y Análisis de datos) de la asignatura Tipología y ciclo de vida de los datos del Máster en Ciencia de Datos en la Universitat Oberta de Catalunya. Se aplican técnicas de limpieza y análisis de datos mediante el lenguaje de programación R para extraer así conclusiones del dataset que se encuentra en el repositorio UCI Machine Learning Repository sobre la [calidad de vinos](https://archive.ics.uci.edu/ml/datasets/Wine+Quality). Esta práctica se centra en utilizar una serie de técnicas para elaborar un clasificador entre vinos rojos y blancos, con el fin de conocer cuáles son las propiedades características de cada uno de los tipos de vinos disponibles. Cabe destacar que esta acciónes muy importante para empresas que elaboran vinos y buscan mejorar su productos.


### Instalación 🔧

Para ejecutar el proyecto se necesita de las siguientes librerías:

```
pip install BeautifulSoup
pip install os
pip install pandas
pip install random
pip install requests
pip install time
pip install tqdm
pip install urlparse
```

### Descripción de los ficheros 📋

* **jupyter/WebScraping.ipynb**: versión preliminar de la práctica realizada con Jupyter Notebook.
* **pyProject/main.py**: clase principal para el iniciar el scraping.
* **pyProject/scraper.py**: contiene la implementación de la clase _BooksScraper_ cuyos métodos extraen el conjunto de datos de la web [Books to Scrape](https://books.toscrape.com).
* **pyProject/book.py**: clase con las estructura de datos de un libro, y el método para convertir los datos a un formato CSV.
* **pyProject/output.png**: captura de pantalla de una ejecución del programa, con comentarios y tiempo que ha tardado.
* **pyProject/csv/dataset.csv**: dataset en CSV.
* **pyProject/html**: directorio dataset en HTML.

## Despliegue-Ejecución 📦

_Accedemos a la ruta del proyecto pyProject, y ejecutamos la clase main:_
```
python main.py
```

## Build with 🛠️

* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup) - A Python library designed for quick turnaround projects like screen-scraping.
* [Jupyter Notebook](https://jupyter.org) - An open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.
* [PyCharm](https://www.jetbrains.com/pycharm) - The Python IDE for Professional Developers.
* [Sourcetree](https://www.sourcetreeapp.com) - Simplicity and power in a beautiful Git GUI.

## Authors ✒️

* **Daniel Laureano Cerviño Cortínez** - *-* - [Danielcc97](https://github.com/Danielcc97)

## DOI 📖

El dataset ha sido subido a Zenodo y registrado con el DOI: [10.5281/zenodo.4263215](https://doi.org/10.5281/ZENODO.4263215)

## Referencias 🖇️

* Hong Khai, T. (2019, December 18). Extract Transform Load (ETL) for Books to Scrape. https://medium.com/analytics-vidhya/extract-transform-load-etl-for-books-to-scrape-b0ff5f83095d
* Lawson, R. (2015). Web Scraping with Python. Packt Publishing Ltd.
* Oheix, J. (2018, December 11). An introduction to web scraping with Python. https://towardsdatascience.com/an-introduction-to-web-scraping-with-python-a2601e8619e5 
* Subirats Maté, L., & Calvo González, M. (2019). Web scraping. Editorial UOC.
* Toscrape.com. (n.d.). Books to Scrape. Retrieved 7 November 2020, from https://books.toscrape.com/

## License 📄

Released Under CC0: Public Domain License
