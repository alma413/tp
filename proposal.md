# Propuesta TP DSW

## Grupo
### Integrantes
* 52184 - Luraschi Zárate, Alma
* 53236 - Alfonso, Avril Antonela
* 52184 - Rau, Anelén
* 52184 - Monzón, Maximiliano
  
### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
En sus batallas, los Avengers siempre dejan destrozos por distintas ciudades, hasta a veces heridos. Industrias Stark nos contrató para diseñar un sitio web que les permita a los ciudadanos solicitar distintos tipos de servicios (que ellos financian) para enmendar los daños causados. Además, los clientes podrán reseñar los servicios brindados.


### Modelo
![tp-dsw drawio (1)](https://github.com/user-attachments/assets/fd3d4084-4896-48ce-af29-a1e08f772f1f)
https://drive.google.com/file/d/13IB2velebcsy1rYUaoyFeBbZxdMyXc72/view?usp=sharing


## Alcance Funcional 

### Alcance Mínimo
 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Habitación {depende de} CRUD Tipo Habitacion<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

