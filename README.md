
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
