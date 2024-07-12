# Descripción del Proyecto

Este proyecto es un desafío para desarrollar una aplicación de foro como parte del programa ONE y Alura Latam.

# Funcionalidades

Autenticación y Login

Permite a los usuarios iniciar sesión ingresando su correo electrónico y contraseña.
Operaciones CRUD

Los usuarios autenticados pueden realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en:
- Cursos
- Perfiles
- Usuarios
- Respuestas
- Tópicos
- Documentación de la API

La API está documentada utilizando Swagger-UI, accesible a través del navegador.

# Funcionamiento

- Creación de Usuario

- Se debe crear un usuario en la base de datos con su correo electrónico y contraseña encriptada utilizando bcrypt.

- También se deben crear los perfiles asociados.
## Login

Los usuarios pueden iniciar sesión con su correo electrónico y contraseña.
Gestión de Tópicos y Respuestas

Una vez autenticados, los usuarios pueden crear nuevos registros para tópicos y respuestas.
