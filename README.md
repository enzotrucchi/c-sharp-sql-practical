Primera parte del TP: 
CRUD de servicio de streaming de películas.

Tablas:
Pelicula:

- Fecha de lanzamiento
- presupuesto
- título
- genero (1 sólo)

Genero

- descripcion

Usuario

- nombre
- mail

Películas vistas por un usuario (¿tal vez una tabla intermedia para ir guardando?) con la fecha en que se visualizó.

Entonces quedaría: 
- Una arquitectura de 3 capas
- La interfaz (vista) de la aplicación, sería una tabla que muestre:

Usuario | Película | Fecha de lanzamiento | Fecha de vista
