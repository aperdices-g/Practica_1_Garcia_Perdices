# Practica_1_Garcia_Perdices
# 
WebScraping_Practica_1

En el contexto de la práctica propuesta, y motivadas sobre todo por las ventajas y beneficios que el estudio de datos procedentes de enfermedades y de desastres naturales puede aportar a la comunidad científica, no solo para la prevención, sino para establecer protocolos, hemos decidido estudiar y hacer web scraping de los siguientes recursos:

https://data.europa.eu/euodp/es/data/publisher/ecdc   
https://reliefweb.int/disasters  

Aún estamos trabajando en ambas páginas y datasets.

**Caso enfermedades. Proceso:**


De este modo, y con el fin, de descargar, analizar y organizar estos datos de interés, hemos completado el proceso de web scraping de la siguiente forma:

•	Se ha evaluado el mapa de los sitios web para localizar el contenido del recurso, poniendo el foco en la estructura de la página, y así poder averiguar dónde y cómo descargar los datos que necesitamos para el estudio.

•	Se ha convertido la página en HTML a estructura anidada.

•	A continuación, se ha descargado la página web mediante las librerías Requests y BeautifulSoup en Python.

•	Tras examinar las etiquetas, tags, clases de la página, hemos navegado por la estructura hasta el enlace que contiene los datos para posteriormente descargarlos y analizarlos. 

Nota: las enfermedades escogidas son Zika, Dengue y Chikunbunya (elegidas por ser enfermedades provocadas por picadura de mosquito)

**Caso desastres. Proceso:**

En este caso se puede realizar webscraping a través de una api existente. Así, siguiendo las indicaciones de la API se realizan llamadas para obtener información de los desastres.

La documentación de la API la podéis consultar en: https://apidoc.rwlabs.org/#doc-use

En la documentación se pueden consultar diferentes formas de llamar, al igual que los parámetros, campos de tabla, etc


**Publicación del Dataset en Zenodo:**

Nos hemos decantado por el dataset de enfermedades:

Publicación en Zenodo: https://zenodo.org/record/3743475#.XozOxXJS8dU

DOI: 10.5281/zenodo.3743475
