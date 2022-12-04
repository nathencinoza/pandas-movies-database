
Vamos a utilizar como dataset los csvs de [esta carpeta](https://drive.google.com/drive/folders/1fOBnuxITZSsbChHfmrvw8rQt_D_SyJ18). Es una mezcla del dataset de “the movie database” para 45mil películas y datos de imdb.

Los csvs son:

+ Movies.csv
  + adult: 😏🥵
  + belongs_to_collection: Nombre de la colección a la que pertenece la película
  + budget: presupuesto
  + genres: géneros separados por coma
  + homepage: web de la peli
  + id: id de la peli
  + imdb_id: id de la película en imdb
  + original_language: idioma original
  + original_title: título en el idioma original
  + overview: descripción de la película
  + popularity: popularidad
  + poster_path: ruta a la imagen del poster
  + production_companies: id de las empresas que produjeron la película, separadas por comas
  + production_countries: países donde se produjeron las películas
  + release_date: fecha de estreno
  + revenue: ingresos que generó
  + runtime: largo total en minutos
  + spoken_languages: idiomas que se hablan en la película
  + status: estado de la película
  + tagline: eslogan
  + title: título en inglés
  + video
  + vote_average: promedio de calificaciones
  + vote_count: cantidad de votos
  
+ cast.csv
  + id: id de película en la que participó
  + cast_id: id de la persona
  + character: personaje que hizo
  + name: nombre

+ crew.csv
  + id: id de la película en la que participó
  + crew_id: id de la persona
  + department: departamento en el que trabajo
  + job: título de su trabajo
  + name: nombre
  
+ companies.csv
  + id: id de la compañía
  + name: nombre
  + keywords.csv
  + id: id de la película
  + keywords: palabras clave separadas por coma

+ ratings.csv
  + userId: user que dejó el rating
  + movieId: película donde lo dejó
  + rating: el rating que dejó, del 1 al 5
  + timestamp: timestamp de cuando dejó el rating
  
+ imdb_actors.csv: Es un csv extra que sale de imdb que contiene información de muchos actores y actrices
  + nconst: id de la persona
  + primaryName: nombre
  + birthYear: año de nacimiento
  + deathYear: año de muerte
  + primaryProfession: profesiones principales separadas por comas
  + knownForTitles: ids de imdb por los cuales se lo conoce, separado por comas
  
+ links.csv
  + movieId: un ID único para cada película
  + imdbId: el id de imdb de esa película
  + tmdbId: el ID de “the movie database” que aparece en la mayoría de las otras tablas

### Consignas realizadas

+ #### P9) De las películas que están siendo rumoreadas, ¿cuál es el título de la que presenta el presupuesto más alto?

#### + P13) Según los cinéfilos, ¿cuál es el rating promedio de las 5 películas más populares? Un usuario es cinéfilo cuando puntuó más de 50 películas y todas las puntuaciones son de más de 2.5 estrellas. Indicar id, título, popularidad y rating promedio de la película.

#### + P35) Queremos hacer una película que incluya al mejor empleado para cada categoría de la tabla crews como líder de equipo. Para los empleados que participaron en más de 5 películas considerando el promedio de ratings de las películas en las que participaron, ¿Cúal es el mejor de cada tupla (department, job)? Con este mismo criterio, consiga un top 5 de actores y top 5 de actrices para el elenco de la misma. Con este mismo criterio queremos también el tema de la película, ¿cuáles son las 4 mejores keywords?

#### + N6) Queremos predecir el género de la película según su descripción. Para esto vamos a buscar para una descripción nueva los 10 vecinos más cercanos y asignar el género que más se repita entre ellos. Pruebe este algoritmo para 5 películas al azar y para una descripción inventada que se le ocurra para una película nueva de Disney.

#### + C5) ¿Cúal es la película cuya entropía de las ratings que recibe es más alta? Esta será la película con opiniones más variadas. Considere sólo películas con más de 30 ratings.

#### + C9) Para cada usuario que hizo más de 100 reviews, ¿cuáles son los dos usuarios con mayor distancia normalizada de compresión entre la concatenación de la descripción de 100 películas al azar que vieron? ¿Y con menor? Muestrelos intentando justificar por qué resultan así. Si no le alcanza el tiempo para estos usuarios puede tomar un filtro de usuarios que hicieran más reviews.


#### + V4) Realizar un heatmap de represente la correlación entre los géneros de películas.
