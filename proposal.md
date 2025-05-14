
## Grupo
### Integrantes
* 52184 - Luraschi Zárate, Alma
* 53236 - Alfonso, Avril
* 52184 - Rau, Anelén
* 52184 - Monzón, Maximiliano
  
### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)


## Tema
### Descripción
En sus batallas, los Avengers siempre dejan destrozos por distintas ciudades, hasta a veces heridos. Industrias Stark nos contrató para diseñar un sitio web que les permita a los ciudadanos solicitar distintos tipos de servicios (que ellos financian) para enmendar los daños causados. Además, los clientes podrán reseñar los servicios brindados.


### Modelo
![tp-dsw](https://github.com/user-attachments/assets/40615d2c-bbe7-49e4-b4ac-708b798ec4ef)# Propuesta TP DSW
https://drive.google.com/file/d/13IB2velebcsy1rYUaoyFeBbZxdMyXc72/view?usp=sharing



## Alcance Funcional 

### Alcance Mínimo
 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Categoría<br>3. CRUD Localidad<br>4. CRUD Solicitud|
|CRUD dependiente|1. CRUD Solicitante {depende de} CRUD Usuario<br>2. CRUD Prestador {depende de} CRUD Usuario|
|Listado<br>+<br>detalle| 1. Listado de prestadores filtrado por tipo de servicio, muestra descripción del prestador.<br> 2. Listado de solicitudes (hechas por un solicitante) filtrado por fecha, muestra descripción de la solicitud.
|CUU/Epic|1. Solicitar la prestación de un servicio<br>2. Publicar un servicio|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Categoría<br>3. CRUD Localidad<br>4. CRUD Solicitud<br>5. CRUD Reseña<br>6. CRUD Cliente<br>7. CRUD Prestador<br>8. CRUD Administrador<br>9. CRUD Servicio|
|CUU/Epic|1. El solicitante realiza una reseña<br>2. Moderador evalúa una reseña|


### Alcance Adicional Voluntario


|Req|Detalle|
|:-|:-|
|Listados |1. Reseñas filtradas por prestador, muestra la valoración, descripción y fecha|


