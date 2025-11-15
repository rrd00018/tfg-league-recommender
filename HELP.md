# tfg-league-recommender

El objetivo del proyecto es crear usando el framework SpringBoot y un enfoque de arquitectura hexagonal un sistema de recomendación de items del videojuego League of Legends utilizando los algoritmos Topsis y Todim. Para ello se deberan seguir varios pasos.
1. Se deberán cargar mediante un batch de SpringBoot los datos de los objetos, campeones, runas, hechizos etc desde los archivos JSON almacenados en la carpeta resources/data. Estos datos se trasladaran a entidades de
   dominio y luego mediante un mapper de MapStruct se mapearan a entidades JPA para su posterior almacenamiento en una base de datos relacional. Se debe crear para cada entidad su repositorio de Jpa así como el repositorio de dominio
   que reciba desde el servicio la entidad de domino y llame al repositorio JPA para almacenar la entidad mapeada. Además se debe de crear un servicio que tenga las operaciones CRUD básicas para cada
   entidad.
