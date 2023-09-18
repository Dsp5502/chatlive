# ChatLive

Recuerden que deben de ejecutar `npm install` para reconstruir los módulos de Node.

## Tecnologías Requeridas:

- Node.js
- Express.js
- MongoDB (base de datos NoSQL)
- Socket.io (para la funcionalidad de chat en tiempo real)

### Descripción del Proyecto:

Desarrollar un sistema de chat en tiempo real que permita a los usuarios registrados comunicarse entre sí. Los usuarios pueden enviar mensajes de texto y crear salas de chat para conversaciones grupales.

## Requisitos Funcionales:

#### Registro de Usuarios:

Los usuarios deben poder registrarse en el sistema proporcionando un nombre de usuario, una dirección de correo electrónico y una contraseña.
Se debe verificar que el nombre de usuario y la dirección de correo electrónico sean únicos.
La contraseña debe estar encriptada antes de almacenarse en la base de datos.

#### Autenticación:

Los usuarios registrados deben poder iniciar sesión utilizando su nombre de usuario y contraseña.
Implementar un sistema de autenticación para proteger las rutas y funciones que requieren autenticación.

#### Lista de Usuarios Conectados:

Mostrar una lista de usuarios conectados en tiempo real.
Actualizar la lista cuando un usuario inicia o cierra sesión.

#### Chat en Tiempo Real:

Los usuarios deben poder enviar mensajes de texto a otros usuarios en tiempo real.

## Segundo Nivel de requisitos.

- Implementar salas de chat para conversaciones grupales, donde los usuarios pueden unirse a una sala y enviar mensajes a todos los miembros de la sala.
- Los mensajes deben incluir información sobre el remitente, el contenido y la hora de envío.
- Los mensajes deben mostrarse en tiempo real a medida que se envían.

### Gestión de Salas de Chat:

- Los usuarios pueden crear nuevas salas de chat.
- Los usuarios pueden unirse a salas de chat existentes.
- Los usuarios pueden abandonar salas de chat.
- Los administradores pueden eliminar salas de chat si es necesario.
