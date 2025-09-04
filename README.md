[ES] Prueba el servicio utilizando Postman:
- Creación de actores (POST) o actualización (PUT): https://moviecards-service-tfmcopilot.azurewebsites.net/actors

(al actualizar es necesario poner el ID del actor)

~~~
{

    "id": "",

    "name": "",

    "birthDate": "YYYY-MM-DD",

    "deadDate": "YYYY-MM-DD",

    "country": "",

    "movies": []

}
~~~
 
- Listado de actores (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/actors

- Obtener actor por ID (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/actors/id

- Creación de películas (POST) o actualización (PUT): https://moviecards-service-tfmcopilot.azurewebsites.net/movies

(al actualizar es necesario poner el ID de la película)

~~~
{

    "id": "",

    "title": "",

    "releaseYear": "YYYY",

    "duration": ,

    "country": "",

    "director": "",

    "genre": "",

    "sinopsis": "",

    "actors": []

}
~~~

-	Listado de películas (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/movies

- 	Obtener película por ID (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/movies/id
 
-	Vinculación de un actor a una película (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/movies/insc/actor/movie


[EN] Test the service using Postman:
- Actor creation (POST) or update (PUT): https://moviecards-service-tfmcopilot.azurewebsites.net/actors

(on update it's necessary to use the actor's ID)

~~~
{

    "id": "",

    "name": "",

    "birthDate": "YYYY-MM-DD",

    "deadDate": "YYYY-MM-DD",

    "country": "",

    "movies": []

}
~~~
 
- Actor list (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/actors

- Get actor by ID (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/actors/id

- Movie creation (POST) or update (PUT): https://moviecards-service-tfmcopilot.azurewebsites.net/movies

(on update it's necessary to use the movie's ID)

~~~
{

    "id": "",

    "title": "",

    "releaseYear": "YYYY",

    "duration": ,

    "country": "",

    "director": "",

    "genre": "",

    "sinopsis": "",

    "actors": []

}
~~~

-	Movie list (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/movies

-	Get movie by ID (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/movies/id	
 
-	Add an actor to a movie (GET): https://moviecards-service-tfmcopilot.azurewebsites.net/movies/insc/actor/movie
