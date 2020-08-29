# Proyecto de Visualización de Datos, descripción de rutas de jugadores costarricenses

# Introducción

El proyecto final del curso de Visualización de Datos, consiste en realizar una presentación basada en un dataset específico. En este caso, el dataset se genera a partir de un web scrappin del sitio TransferMarkt, con el fin de obtener el historial de los jugadores de fútbol costarricense. El objetivo de la investigación es tratar de determinar cuales son las rutas más efectivas para lograr la venta de un jugador a un equipo foráneo. Esta información puede resultar de gran importancia para los representantes de jugadores, gerentes de equipos y jugadores mismos. Los primeros porque pueden encaminar a sus representados por la mejor ruta, los gerentes para darse cuenta que si son o no son vitrina para sus jugadores y los jugadores para tener presente esta información al momento de tomar decisiones de donde jugar en el corto, mediano y largo plazo.

# Descripción de los datos

El archivo que se utiliza para este trabajo es "Lista de Jugadores Costarricenses y sus equipos", el cual se encuentra en formato CSV. Este archivo fué obtenido mediante una consulta directa a wikidata ejecutada por el profesor Dagoberto Herrera. 


- *Nombre:* jugadores_final.csv
- *Fuente/Creador:* Dagoberto Herrera, Nelson Alfaro, Jorge Zapata
- *Proceso de creación:* Web Scrapping en TransferMarkt, procesamiento en python notebook de nuevas variables.
- *Forma de acceso:* Libre
- *Fecha de publicación/Fecha de recuperación:* 29 de agosto del 2020
- *Formato de los archivos:* .csv, .ipnyb


# Diccionario de datos

- *Player:* Nombre de jugador
- *Selector1-href:* URL de la búsqueda en TransferMarkt
- *Date:* Fecha de transacción
- *From club*: Equipo de origen
- *To club:* Equipo de destino
- *Date of birth:* Fecha de nacimiento del jugador
- *Age:* Edad actual del jugador
- *National player:* Jugador de Selección Nacional de Costa rica
- *International Matches:* Cantidad de partidos internacionales con la Selección Nacional de Costa Rica
- *Market Value:* Valor actual del mercado
- *Posición:* Posición de desempeño del jugador
- *from_club_path:* Ruta de equipos de origen del jugador
- *final_club_path:* Ruta de equipos de destino del jugador
- *final_team:* Último equipo de juego
- *from_pais:* País del origen del equipo
- *to_pais:* Último país de juego
- *path_country:* Ruta de países del recorrido del jugador