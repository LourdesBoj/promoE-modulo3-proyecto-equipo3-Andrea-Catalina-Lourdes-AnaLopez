# promoE-modulo3-proyecto-equipo3-Andrea-Catalina-Lourdes-AnaLopez

## Integrantes
Ana Isabel López Navarro, Andrea Cabrera , Lourdes Boj y Catalina Tomas Jaume Miquel
Estudiantes en Adalab, Bootcamp: Data Analytics, Promoción E (Evelyn)

## Descripción del proyecto
GoGreen Bikesharing es una empresa de Whashington D.C. dedicada al alquiler de bicicletas.

El dataset sobre el que trabajamos posee datos tales como la cantidad de bicis alquiladas por usuarios registrados, la cantidad de alquileres realizados por usuarios puntuales, y la cantidad total. A estos datos se les añadió información meteorológica, y el calendario de festivos.

En este proyecto se van a analizar cuáles son los aspectos que más influyen en la cantidad de bicis que se van a alquilar en un día.

También se harán varios modelos de Machine Learning que nos permitan realizar predicciones de cuántas bicicletas se van a alquilar en un día. 

## Características del dataset:
=========================================	
Las variables originales del dataset son:
	
	- instant: record index
	- dteday : date
	- season : season (spring, summer, autumn, winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered

## Estructura de las carpetas 

En este repositorio se encuentran tres carpetas: una llamada 'data', otra 'graficas' y otra "notebooks", además de este README. Dentro de la carpeta 'data' se encuentran todos los archivos generados. Por otro lado, la carpeta de 'graficas' está compuesta por todas las imágenes correspondientes a las gráficas establecidas.
Por último, la carpeta "notebooks" contiene los archivos jupyter donde se ha realizado el EDA, los modelos de predicción y las predicciones.

## Lenguajes utilizados
* Python 3.10.11

## Librerias utilizadas
* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Requests](https://matplotlib.org/3.5.3/api/_as_gen/matplotlib.pyplot.html)
* [Matplotlib](https://matplotlib.org/stable/users/index.html/)
* [Seaborn](https://seaborn.pydata.org/tutorial.html/)
* [Statsmodels](https://www.statsmodels.org/devel/user-guide.html/)
* [Math](https://docs.python.org/3/library/math.html/)
* [SciPy](https://docs.scipy.org/doc/scipy/)
* [Scikit-learn](https://scikit-learn.org/stable/user_guide.html/)
* [Itertools](https://docs.python.org/3/library/itertools.html/)
* [Warnings](https://docs.python.org/es/3/library/warnings.html/)
* [Imblearn](https://pypi.org/project/imblearn/)
* [Datetime](https://docs.python.org/es/3.10/library/datetime.html)

## Herramienta utilizada
* [Tableau](https://www.tableau.com/es-es/community/public)