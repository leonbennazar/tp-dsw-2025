# Propuesta TP DSW

## Grupo
### Integrantes
* 51236 - JUAN BENNAZAR, León
* 51729 - MORETTI, Lucca

### Repositorios
* [frontend app](https://github.com/leonbennazar/tp-dsw-frontend)
* [backend app](https://github.com/leonbennazar/tp-dsw-backend)

## Tema (NOMBRAR APLICACIÓN)
### Descripción

[NOMBRE DE APP] es un sistema para gestionar reservas de canchas de fútbol. Solamente tenés que registrar un usuario con tu mail para empezar a reservar. Elegís la fecha, la hora y la cancha que más te guste [y pagar la seña para confirmar la reserva]. Nosotros te recordamos cuando te toca jugar!

### Modelo
[imagen del modelo](https://drive.google.com/file/d/1B_XXn6uLUYE9IYtGiJ_Q2tqKOh1vT_ZC/view?usp=sharing)

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tamaño Cancha<br>2. CRUD Material Cancha|
|CRUD dependiente|1. CRUD Cancha {depende de} CRUD Tamaño Cancha y Material Cancha<br>2. CRUD Agenda {depende de} CRUD Complejo|
|Listado<br>+<br>detalle| 1. Listado de Canchas libres filtrado por Material, Tamaño y fecha => detalle Crud Reserva<br> 2. Listado de Reservas filtrado por fecha: muestra número de Cancha, hora de inicio, hora de finalizado y nombre del Cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una cancha.|

Adicionales para Aprobación Directa:
|Req|Detalle|
|:-|:-|
|CRUD |1. <br>2. <br>3. <br>4. <br>5.Pago con MP <br>6. <br>7. |
|CUU/Epic|1. <br>2. <br>3. |

### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.
