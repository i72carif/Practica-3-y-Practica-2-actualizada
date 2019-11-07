# Clinica médica
### Requisitos:
>Para realizar dicha tarea hemos reunido una serie de requisitos estudiados con nuestro cliente.
Nuestro cliente desea tener para antes del 23 de Diciembre un programa que pueda almacenar a los pacientes y todos sus datos, siendo estos su informacion personal, el historial, los tratamientos y las citas con la clinica. Esto se realiza en un sistema operativo Linux con gran capacidad de almacenamiento.

**Para ello se crea un menu inicial en el que aparecen dos apartados; pacientes y citas.**

**El apartado de citas:**
* **Mostrar citas:** muestra una lista completa de las citas que tiene la clinica con sus clientes, ordenadas de las mas reciente hasta la mas alejada de fecha.

**En el apartado de pacientes podemos realizar varias operaciones:**
* **Añadir paciente:** consiste en dejar que el secretario de la clinica pueda introducir la informacion de un nuevo paciente  y crea un historial vacio para posteriormente ser rellenado, haciendo que cumpla con las condiciones establecidas, siendo estas que el paciente no este en la base de datos y que todos los campos sean rellenados.
* **Mostrar lista de pacientes:** es una operacion simple que muestra en pantalla todos los pacientes ordenados por apellidos, siempre y cuando haya al menos un paciente registrado.
* **Borrar paciente:** esta operacion es poco usada por el cliente, al decidir esto, todos los datos del paciente indicado seran borrados, es necesario que exista el cliente.
* **Mostrar paciente:** esta operacion pide al cliente el nombre completo de un paciente para mostrar todos sus datos existentes en la base de datos, es necesario que exista. Hay que concretar que al realizar esta operación, se muestran el historial, tratamiento y cita existentes.
Al realizar esto, aparecen varias opciones ligadas al paciente mostrado:
	- **Modificar datos del paciente:** Si el paciente cambia de municipio, nombre o cualquier tipo de informacion, el secretario puede cambiar estos datos en esta opcion.
	- **Añadir en historial:** trata de actualizar el historial con alguna anotacion relevante del paciente que deba ser registrada.
	- **Añadir cita:** se añade la fecha y nombre del paciente para tener una cita con la clinica y que el secretario pueda informarse del dia.
	- **Mover cita:** se modifica la cita para cambiar la fecha y hora estimada.
	- **Cancelar cita:** se cancela la cita ya sea por ser realizada o porque se ya no se va a realizar.
	- **Añadir tratamiento:** esta opcion añade la concentracion del medicamento, la planificacion y la fecha de inicio y fin de dicho tratamiento para el paciente al que se le aplica. Puede tener mas de un tratamiento y cada uno indica si esta activo o terminado para que el secretario pueda tener constancia de ello.
	- **Cancelar tratamiento:** con esta opcion da por finalizado el tratamiento activo que tenga el paciente.
