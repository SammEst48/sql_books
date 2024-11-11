# 📚 Booktop

## Descripción del Proyecto
El coronavirus tomó al mundo entero por sorpresa, cambiando la rutina diaria de todos y todas. Los habitantes de las ciudades ya no pasaban su tiempo libre fuera, yendo a cafés y centros comerciales; sino que más gente se quedaba en casa, leyendo libros. Eso atrajo la atención de las startups (empresas emergentes) que se apresuraron a desarrollar nuevas aplicaciones para los amantes de los libros.
Tenemos una base de datos de uno de los servicios que compiten en este mercado. Contiene datos sobre libros, editoriales, autores y calificaciones de clientes y reseñas de libros. Esta información se utilizará para generar una propuesta de valor para un nuevo producto.

## Objetivos
El objetivo del proyecto es utilizar la base de datos para generar información valiosa que pueda ayudar a la startup en el mercado de libros digitales a desarrollar un producto competitivo.
  
## Dataset
**`books`**
Contiene datos sobre libros:
- `book_id`: identificación del libro
- `author_id`: identificación del autor o autora
- `title`: título
- `num_pages`: número de páginas
- `publication_date`: fecha de la publicación
- `publisher_id`: identificación de la editorial

**`authors`**
Contiene datos sobre autores:
- `author_id`: identificación del autor o autora
- `author`: el autor o la autora

**`publishers`**
Contiene datos sobre editoriales:
- `publisher_id`: identificación de la editorial
- `publisher`: la editorial

**`ratings`**
Contiene datos sobre las calificaciones de usuarios:
- `rating_id`: identificación de la calificación
- `book_id`: identificación del libro
- `username`: el nombre del usuario que revisó el libro
- `rating`: calificación

**`reviews`**
Contiene datos sobre las reseñas de los y las clientes:
- `review_id`: identificación de la reseña
- `book_id`: identificación del libro
- `username`: el nombre del usuario que revisó el libro
- `text`: el texto de la reseña

## Diagrama de datos
![image](https://github.com/user-attachments/assets/adcf7037-2a6c-42d7-bf1d-9b1ee2640f06)

## Herramientas utilizadas
- **Python**: pandas, sqlalchemy
- **Jupyter Notebooks**: para análisis interactivo.

## Pasos de análisis
Se realizan varias tareas mediante consultas con SQL, incluyendo la identificación del número de libros publicados después de cierto año, el cálculo de calificaciones promedio de libros, la identificación de la editorial más productiva y la búsqueda del autor con la calificación promedio más alta. 

**Nota**: Este proyecto fue desarrollado como parte de mi formación en el bootcamp de Tripleten en el área de análisis de datos.


