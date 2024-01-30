# api-books
LEER ANTES DE INICIAR

Para correr el proyecto ejecutar npm run dev no es necesario otro comando ya que este actualiza todo en tiempo real
para correr el eslint ejecutar npm run lint

En caso de querer ejecutar comando separados ejecutar:
npm run tsc
npm run start

RUTAS

localhost:3000/hello
localhost:3000/books
localhost:3000/books/3f24cbda-dce7-499d-9b65-4ebd3bff4cd8

POST->  localhost:3000/books
prueba->
{
    "id": "2",
    "title": 2,
    "author": "la sirenita",
    "price": 8.354,
    "availability": 19,
    "num_reviews": 519,
    "stars": 5,
    "description": "esto es una prueba."
  }

  localhost:3000/books/price/450
