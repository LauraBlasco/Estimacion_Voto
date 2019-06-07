ESTIMACIÓN DE VOTO ELECCIONES GENERALES 28 ABRIL

Os presento mi proyecto final del máster de Data Science en Kschool. El objetivo inicial del proyecto era descargar datos de Twitter que hablaran de las elecciones generales del 28 de abril, y con ellos hacer un modelo de predicción de voto, pero a la hora de descargar los datos desde la API no di con las palabras claves para buscar los tweets, y acabé haciendo una predicción de voto con datos de los últimos sondeos que la empresa había hecho para El Periódico.

ESTRUCTURA DEL PROYECTO:
El proyecto consta de 4 Scripts:
-	00_Intento_descarga_Twitter.ipynb”: Éste era el notebook con el que intenté descargar los datos de Twitter, pero no me acabó de funcionar.
-	01_Tratamiento_datos.ipynb: A partir de ahí empecé a trabajar con los datos de la empresa, como he comentado antes y en este notebook exploro y trato los datos para posteriormente poder hacer el modelo. Abriendo el Script se puede ver detallada la explicación de lo que voy haciendo.
-	02_Prediccion_voto.ipynb: Una vez tratados los datos y juntados los dos datasets, me dispongo a hacer el modelo correspondiente. Los modelos que probé son Random Forest y Gradient Boosting, funcionándome mejor el primero, con un accuracy de 0,51.
-	03_Presentación_datos.twb: La presentación de los datos la he hecho con Tableau Desktop. 

CONCLUSIONES:
-	En los últimos sondeos antes de las elecciones generales del 28 de abril, más de la mitad de los españoles considera que estas elecciones son muy importantes, y ocho de cada diez aseguran que iran a votar.
-	En cuanto a los candidatos, Pedro Sánchez se mantiene como el mejor valorado, por delante de Albert Rivera. Todos han mejorado su nota de febrero a abril.
-	En preferencias a presidente, Sánchez continua por delante, mejorando su registro de febrero a abril. Albert Rivera i Pablo Iglesias, segundo y tercero, también mejoran sus datos en este indicador, al contrario que Pablo Casado i Santiago Abascal.
-	Y centrándonos en la intención de voto, la estimación dibuja un escenario muy favorable para el PSOE que, según los sondeos, ganaría las elecciones con un 30% de los votos. En segunda posición quedaría el PP. C's mejoraría ligeramente sus resultados de 2016, quedando en tercera posición. Vox entraría en el congreso gracias a los votos provenientes del PP, C's y la abstención, pero pierde fuerza de febrero a abril.

AGRADECIMIENTOS:
Quería agradecer a todos mis compañeros de clase que me han aclarado todas las dudas que he ido teniendo, y en especial a Antonio Martínez, que me ha 
