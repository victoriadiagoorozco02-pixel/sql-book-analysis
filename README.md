# Análisis de base de datos de libros - Proyecto SQL

## Descripción del proyecto
Este proyecto analiza una base de datos de una plataforma de libros digitales con el objetivo de generar insights que apoyen la definición de una propuesta de valor para un nuevo producto.

El análisis se enfoca en entender el catálogo disponible, el comportamiento de los usuarios y la relación entre popularidad, calidad y engagement.

---

## Objetivo
Explorar la base de datos mediante consultas SQL para identificar patrones relevantes en libros, autores, editoriales y comportamiento de usuarios, con el fin de generar recomendaciones estratégicas para el desarrollo de un producto competitivo.

---

## Dataset
La base de datos incluye las siguientes tablas:

- books: información de libros  
- authors: datos de autores  
- publishers: editoriales  
- ratings: calificaciones de usuarios  
- reviews: reseñas de usuarios  

---

## Herramientas utilizadas
- SQL  
- PostgreSQL / entorno de consultas  
- Análisis exploratorio de datos  

---

## Proceso de análisis

Se desarrollaron consultas SQL para responder preguntas clave:

- Libros publicados después del año 2000  
- Número de reseñas y calificación promedio por libro  
- Editorial con mayor número de publicaciones relevantes  
- Autor con mejor calificación promedio (considerando volumen)  
- Nivel de participación de usuarios activos  

---

## Insights clave

- El catálogo incluye una alta proporción de libros contemporáneos (819 publicados después del 2000).  
- La popularidad de un libro no siempre está alineada con su calificación.  
- Penguin Books lidera en volumen de publicaciones relevantes.  
- J.K. Rowling destaca por alto volumen y consistencia en calificaciones.  
- Existe baja proporción de reseñas en comparación con calificaciones.  

---

## Recomendaciones

- Priorizar contenido que combine alta calificación y volumen de interacción.  
- Diferenciar entre popularidad y calidad en sistemas de recomendación.  
- Incentivar la generación de reseñas para mejorar el engagement.  
- Destacar autores con alto volumen de valoraciones confiables.  

---

## Conclusión

El análisis demuestra que el valor del catálogo no depende únicamente del volumen de contenido, sino de la calidad percibida y la interacción de los usuarios. Estos hallazgos permiten orientar el desarrollo de un producto más competitivo y centrado en la experiencia del usuario.

---

## Limitaciones

- No se analizaron variables externas como tendencias del mercado o comportamiento temporal.  
- El análisis se basa únicamente en datos históricos disponibles.  

---

## Próximos pasos

- Implementar modelos de recomendación basados en comportamiento del usuario.  
- Analizar segmentación de usuarios por preferencias.  
- Integrar datos adicionales para enriquecer el análisis.  
