# hotel-reservation-database

## 1. Introducción al problema

- Descripción del problema para poner en contexto el proyecto, incluyendo información sobre los clientes y usuarios, la situación actual, problemas, expectativas, etc. Se valorará la presencia de información multimedia (fotos, gráficos, documentos escaneados, etc.).<br>

El hotel actualmente gestiona la mayoría de sus operaciones de forma manual, lo que provoca pérdida de tiempo, duplicidad de los datos y posibles errores en la gestión diaria. Las reservas se registran sin un sistema centralizado, lo que dificulta el control de la disponibilidad de las habitaciones y el acceso a información actualizada por parte del personal.<br>
<br>
Todo esto genera problemas como reservas duplicadas, dificultad para coordinar el trabajo del personal de limpieza y falta  de trazabilidad sobre el estado de las habitaciones y las estancias de los clientes. Además los trabajadores implicados no reciben la información de inmediato ni de manera uniforme.<br>
<br>
Ante esta situación, el hotel ha solicitado el diseño de una base de datos centralizada que permita gestionar de forma eficiente las reservas, los clientes, las habitaciones y las tareas internas tales como la limpieza, garantizando de esta manera la consistencia de los datos y facilitando futuras ampliaciones del sistema.<br>

## 2. Glosario de términos

- Términos específicos del dominio del problema, ordenados alfabéticamente. Se valorará la presencia de información multimedia.

## 3. Visión general del sistema

### 3.1. Requisitos generales

#### R.G.01. Gestión de cuentas
Como administrador del sistema,<br>
quiero que el sistema gestione y almacene la información de los usuarios,<br>
para poder identificar y diferenciar quiénes utilizan la plataforma.

#### R.G.02. Gestión de habitaciones
Como administrador del sistema,<br>
quiero que el sistema gestione la información relacionada con las habitacione.

#### R.G.03. Gestión de reservas
Como administrador del sistema,<br>
quiero que el sistema guarde la información de las reservas que se hagan,<br>
para saber la ocupación del hotel.

#### R.G.04. Gestión de la limpieza
Como administrador del sistema,<br>
quiero que el sistema gestione la limpieza de las habitaciones,<br>
para saber qué habitaciones se van limpiando.

#### R.G.05. Gestión de pagos
Como administrador del sistema,<br>
quiero que el sistema guarde la debida información acerca de los pagos,<br>
para garantizar que las transacciones quedan correctamente reflejadas.

#### R.G.06 Gestión de valoraciones
Como administrador del sistema,<br>
quiero que el sistema guarde las valoraciones que se ponen.


### 3.2. Usuarios del sistema

El sistema del hotel va a contar con los siguientes tipos de usuarios:

**Administradores**
   * Gestionan usuarios, habitaciones, supervisan incidentes y pueden hacer una reserva para un cliente.

**Clientes**
   * Se registran para reservar habitaciones, consultar disponibilidad de estas, poner valoraciones.

**Servicio limpieza**
   * Consultan qué habitaciones faltan por limpiar, marcan habitaciones como limpias.

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Título requisito funcional

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.1.01. Registro de usuarios

Como administrador del sistema,<br>
quiero que los clientes y trabajadores se puedan registrar en el sistema,<br>
para poder hacer reservas o gestionar el servicio de limpieza.

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.1.02. Eliminación de la cuenta

Como cliente del sistema,<br>
quiero poder eliminar mi cuenta junto a sus datos asociados,<br>
para poder tener control sobre mi información personal y asegurar mi privacidad.

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.1.03. Actualización de datos de la cuenta

Como cliente del sistema,<br>
quiero poder modificar mis datos personales,<br>
para mantener mi información actualizada y correcta en el sistema.

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.1.04. Consulta de información personal

Como cliente del sistema,<br>
quiero consultar mis datos personales,<br>
para verificar que mi información está correcta.

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.2.01. Registro de habitaciones

Como administrador del sistema,<br>
quiero poder registrar nuevas habitaciones en el sistema.

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.2.02. Eliminación de habitaciones

Como administrador del sistema,<br>
quiero poder eliminar habitaciones del sistema,<br>
para mantener actualizada la disponibilidad de estas.

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.2.03. Actualización de datos de una habitación

Como administrador del sistema,<br>
quiero poder modificar los datos de las habitaciones,<br>
para mantener la información actualizada.

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.2.04. Lista de habitaciones para limpieza

Como administrador del sistema,<br>
quiero poder consultar qué habitaciones están limpias o pendientes de ser limpiadas,<br>
para poder planificar mejor el servicio de limpieza.

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.2.05. Lista de habitaciones

Como administrador del sistema,<br>
quiero 

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### R.F.3.01. Registro de reservas

Como cliente del sistema,<br>
quiero poder registrar una reserva seleccionando las características que quiero que tenga mi habitación.

#### R.F.3.02. Anulación de reservas

Como administrador del sistema,<br>
quiero que los clientes y trabajadores puedan anular una reserva,<br>
para saber si una habitación al final no va a ser ocupada.

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...



#### 4.1.1. Requisitos de información

##### R.I.01. Información sobre los usuarios

Como administrador del sistema,<br>
quiero que se guarde el nombre, correo y contraseña de los usuarios.

##### R.I.02. Información sobre las habitaciones

Como administrador del sistema,<br>
quiero conocer la planta y el número de las habitaciones, también quiero conocer qué tipo de habitación es (individual, doble...), qué categoría es (normal, suite...).

##### R.I.03. Información sobre las reservas

Como administrador del sistema,<br>
quiero conocer le fecha de la reserva (cuándo se ha realizado), fecha de inicio de estancia, fecha de fin de estancia.

##### R.I.04. Información sobre la limpieza

Como administrador del sistema,<br>
quiero conocer la fecha programada, la fecha de realización, el estado de la limpieza (pendiente, en proceso, realizada o cancelada), el tipo de limpieza y si hay alguna observación.

##### R.I.05. Información sobre los pagos

Como administrador del sistema,<br>
quiero conocer la fecha de realización del pago, la cantidad pagada, tipo de pago (reserva o pago estancia).

##### R.I.06. Información sobre las valoraciones

Como administrador del sistema,<br>
quiero conocer la puntuación recibida y un comentario opcional.


#### 4.1.2. Reglas de negocio

##### R.N.01. Título regla negocio

Descripción de la regla de negocio.

### 4.2. Mapa de historias de usuario (opcional)

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Título requisito no funcional**
Como [tipo de usuario]
quiero [servicio]
para [razón]


## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

- con restricciones.

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:------|:-----------|:-----------|:-----------|:-----------|
| RI-1  | X          | X          | X          | X          |
| RI-2  |            | X          |            | X          |
| RF-1  |            | X          |            | X          |
| RF-2  | X          |            | X          | X          |
| RN-1  |            | X          |            |            |
| RN-2  | X          | X          | X          |            |
| ...   |            |            |            |            |


## 7. Modelo relacional en 3FN

- Relaciones obtenidas al aplicar la transformación del modelo conceptual.

### 7.1.  Justificación de la estrategia de transformación de jerarquías

- si se identificaron jerarquías en el MC.


### 8. Matriz de trazabilidad MC/SQL (opcional):

- Restricciones sobre el MC / Elementos del modelo tecnológico (SQL) (Triggers, checks, etc.)
- Incluir Reglas de negocio — Constraints/Triggers en las matrices de trazabilidad para el entregable 3

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:-------|:-------|:-------|:-------|:-------|
| TABLA-1 |        |        |        |        |
| TABLA-2 |        |        |        |        |
| TABLA-3 |        |        |        |        |
| TABLA-4 |        |        |        |        |
| TRIG-1 |        |        |        |        |
| TRIG-2 | X      | X      |        | X      |
| TRIG-3 |        | X      |        | X      |
| TRIG-4 |        |        | X      |        |
| CONST-1 |        |        |        |        |
| CONST-2 | X      | X      |        | X      |
| CONST-3 |        | X      |        | X      |
| CONST-4 |        |        | X      |        |

Se consideran todo tipo de constraints declarativas (aquellas definidas durante el CREATE TABLE).

## Referencias

