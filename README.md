# Aplicación de Mercado

Esta aplicación es un sistema de gestión para un mercado que utiliza Spring Framework junto con JPA para la persistencia de datos, mappers para la conversión entre objetos, y distintas capas de dominio que incluyen repositorio, DTO y servicios. Además, la aplicación cuenta con un controlador web para la interfaz de usuario y funcionalidades de seguridad.

## Tecnologías Utilizadas

- **Spring Framework**: Utilizado para la configuración de la aplicación y la inyección de dependencias.
- **JPA (Java Persistence API)**: Utilizado para la persistencia de datos en la base de datos relacional.
- **Mappers**: Utilizados para la conversión entre objetos de distintas capas de la aplicación.
- **Spring Security**: Utilizado para la implementación de funcionalidades de seguridad, como la autenticación y la autorización.
- **Controlador Web**: Utilizado para manejar las solicitudes HTTP y gestionar la interfaz de usuario.

## Capas de la Aplicación

La aplicación sigue una arquitectura de varias capas para separar las responsabilidades y facilitar el mantenimiento y la escalabilidad del sistema:

1. **Capa de Persistencia**: Contiene las entidades de JPA que representan las tablas de la base de datos, así como los repositorios que interactúan con la base de datos.
2. **Capa de DTO**: Contiene los objetos de transferencia de datos (DTO) que se utilizan para transferir datos entre las distintas capas de la aplicación y evitar acoplamientos no deseados.
3. **Capa de Servicios**: Contiene los servicios de negocio que encapsulan la lógica de la aplicación y realizan operaciones en los datos utilizando los repositorios y mappers correspondientes.
4. **Controlador Web**: Contiene los controladores web que manejan las solicitudes HTTP y las respuestas para la interfaz de usuario.
