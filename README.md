# evaluacion_softek
Evaluacion solicitada por Softek

Combina la informacion de la API SWAPI con una API de IMDB para dar un resultado en conjunto, 
se guarda un cacheo en DynamoDB, permite extraer la informacion de todas las peliculas como
de cada pelicula individualmente.

GET/ Fusionados: 

Combina la informacion de la API SWAPI con una API de IMDB para dar un resultado en conjunto, 
se guarda un cacheo en DynamoDB, permite extraer la informacion de todas las peliculas como
de cada pelicula individualmente.

https://<API_AWS>/dev/fusionados
https://<API_AWS>/dev/fusionados/1

POST /Almacenar::

Permite almacenar comentarios sobre cada pelicula 

Header:
Content-Type: application/json

https://<API_AWS>/dev/almacenar/1  

Body:

{
  "comentario": "Comentario a guardar"
}

GET/Historial:

Permite consultar el historial de comentarios, todos los comentarios como individualmente por película

https://<API_AWS>/dev/historial  
https://<API_AWS>/dev/historial/1
