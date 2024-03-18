# Recursion_client

Parte cliente del proyecto 

La parte del cliente es la interfaz a través de la cual los usuarios interactúan con el sistema médico. Está implementada como una aplicación de consola que permite realizar diversas operaciones como hacer citas, ver citas, buscar pacientes, registrar nuevos pacientes y modificar/cancelar citas.

Aquí hay una descripción de las funciones principales en la parte del cliente:

Conexión WebSocket: El cliente se conecta al servidor a través de un WebSocket para enviar y recibir mensajes.

Menú de opciones: El cliente muestra un menú de opciones en la consola, donde el usuario puede seleccionar la operación que desea realizar.

Interacción con el usuario: El cliente solicita información al usuario según la operación seleccionada. Por ejemplo, al hacer una cita, solicita el nombre, cédula y número de teléfono del paciente.

Envío de mensajes al servidor: Una vez que el usuario proporciona la información requerida, el cliente envía un mensaje al servidor a través del WebSocket para realizar la operación correspondiente.

Recepción de respuestas del servidor: Después de enviar un mensaje al servidor, el cliente espera y recibe una respuesta del servidor a través del WebSocket. Esta respuesta se muestra en la consola para informar al usuario sobre el resultado de la operación.

En resumen, la parte del cliente actúa como la interfaz de usuario del sistema médico, permitiendo a los usuarios realizar diversas operaciones a través de una interfaz de consola simple y enviar mensajes al servidor para llevar a cabo estas operaciones.






