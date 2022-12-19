# ETL_Spotify

En este repositorio, realizo un proceso ETL basado en los datos de la API de Spotify. Se realiza a través de una pipeline que descarga datos de Spotify (canciones escuchadas) y guardo estos datos en una base de datos SQLite. La idea es que se ejecute diariamente. Para ello, vamos a usar Apache Airflow que es una plataforma de gestión de flujo de trabajo de código abierto escrita en Python, donde los flujos de trabajo se crean a través de scripts de Python.

Se trata de un ejercicio básico que permite adquirir unas nociones básicas de como funciona un flujo de datos de estas características, a parte de tener un pequeño bagaje relacionado con la ingeniería de datos.


La primera parte consiste en crear un programa que descargue los datos de mi cuenta de Spotify (canciones,hora de escucha, cantente, etc) y luego guarde esos datos en una base de datos relacional. La idea es que cada día que vamos escuchando más y más canciones se vayan guardando en la base de datos. Si dejamos el programa encendido por años, luego podríamos mirar todos los datos generados.

Para generar el token de Spotify API: https://developer.spotify.com/console/get-recently-played/
