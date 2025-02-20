# Modelo-Poblacion-por-condiciones-de-vivienda
En este proyect utilicé una versión modificada de una base de datos del INEGI (Instituto Nacional de Estadística y Geografía) para entrenar un modelo que busca predecir la población de una localidad en base a la proporción de viviendas con determinadas características.

Este proyecto fue originalmente destinado como proyecto parcial de la asignatura Inteligencia Artificial I del semestre Primavera 25 en la Universidad de Monterrey. 
Este proyecto se apoya del material del curso elaborado por el Doctor Antonio Martinez Torteya tanto para el fundamento teórico como para el código. Además, se apoyó de Inteligencia Artificial como apoyo para facilitar la programación. 

La base de datos se llama **"Principales resultados por localidad (ITER) del Censo de Población y Vivienda 2020. Datos oportunos"** se puede encontrar en [la sección datos abiertos de la página web del INEGI.](https://www.inegi.org.mx/datosabiertos/)
Información demográfica y social-> Censos y Conteos -> Censos y conteos de población y vivienda -> Principales resultados por localidad (ITER) -> Nuevo León.

La base de datos incluye al rededor de 277 variables que cuentan con datos demográficos como población total, población total por género, por grupos de edad, grupos étnicos, etc. Sin embargo, para este proyecto solo se considerarán las variables que contaban viviendas particulares y sus características. En la base de datos que se subirá a este repositorio solo hay 64 variables. Aunque, entre estas variables todavía se incluyen algunas que no van a usarse  como el nombre del municipio y sus coordenadas. Se incluyen más detalles en el reporte. 
Todos los detalles del verdadero significado de las variables se encuentran en el diccionario de datos que se incluye adjunto, solo se incluyen las variables utilizadas en el proyeco. Es el mismo diccionario elavorado por el INEGI pero cortando todas las variables que no se utilizaron para entrenar los modelos. Lo mismo sucede para la base de datos. 

**Modificaciones a la base de datos antes de iniciar con el proyecto:** 
Al observar la base de datos, había una observación que en lugar de datos vacíos se llenó por completo de un string "N/D" para todas sus variables. 
Se decidió borrar esa observación.  
La base de datos original en lugar de tener un espacio vacío en las observaciones sin datos tenía un "*" de place holder. Esto causaba problemas, y se optó por removerlos utilizando Excel. 


[Diccionario de Datos](https://github.com/Ethan-R-R/Modelo-Poblacion-por-condiciones-de-vivienda/blob/ba0de9464cb4061c6480f209b9353cb9b3664a4d/diccionario_datos_iter_19CSV20.csv)

[Base de datos](https://github.com/Ethan-R-R/Modelo-Poblacion-por-condiciones-de-vivienda/blob/614fe5e51442e8d259dcfaa41cdc45c79564272c/conjunto_de_datos_iter_19CSV20.csv)
