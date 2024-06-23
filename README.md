# Creacion de una API con .NET

Para empesar, puesto que estoy trabajando en linux, se
debe instalar ciertas cosas, como mi distribucion es basada
en arch instalaré lo siguiente
```bash
$ sudo pacman -S dotnet-runetime dotnet-sdk aspnet-runtime
```

Ahora, para el desarrollo de la API vamos a desarrollar un
proyecto de ASP .NET Core

## ASP .NET Core
ASP.NET Core es un framework de código abierto y 
multiplataforma desarrollado por Microsoft para construir 
aplicaciones modernas basadas en la web, incluyendo
aplicaciones web, APIs, y microservicios. ASP.NET Core es
una reescritura de ASP.NET, diseñado para ser más modular,
más ligero y más flexible.

### ¿Por qué es necesario para desarrollar tu API?
1. **Multiplataforma:** ASP.NET Core permite desarrollar y
ejecutar aplicaciones en Windows, macOS y Linux, lo cual es
ideal para desarrolladores que buscan la flexibilidad de
trabajar en diferentes sistemas operativos.

2. **Alto Rendimiento:** ASP.NET Core es conocido por su
rendimiento rápido y su capacidad de manejar grandes
volúmenes de solicitudes HTTP de manera eficiente.

3. **Modularidad:** El framework es modular, lo que
significa que puedes agregar solo los componentes que
necesitas para tu aplicación, reduciendo la carga y
aumentando la
eficiencia.

4. **Inyección de Dependencias:** ASP.NET Core tiene
soporte nativo para la inyección de dependencias, lo que
facilita la gestión de dependencias y mejora la
mantenibilidad del código.

5. **Middleware:** Utiliza un pipeline de middleware,
permitiendo manejar solicitudes HTTP de manera flexible y
configurable.

6. **Actualizaciones y Soporte:** ASP.NET Core recibe
actualizaciones regulares de Microsoft y tiene una gran
comunidad de desarrolladores que contribuyen al proyecto.

## HTTP
HTTP (Hypertext Transfer Protocol) es el protocolo de
comunicación utilizado en la World Wide Web para
transferir datos entre un cliente (como un navegador web) y
un servidor web. HTTP es un protocolo basado en texto y sin
estado, lo que significa que cada solicitud y respuesta es
independiente y no guarda información sobre solicitudes
anteriores. Utiliza TCP como su protocolo de transporte.

### Funcionamiento
1. Cliente realiza una solicitud HTTP:
 - El cliente envía una solicitud HTTP al servidor. Esta
solicitud incluye un método HTTP, una URL, encabezados
opcionales y, en algunos casos, un cuerpo de mensaje.

**Los métodos HTTP más comunes son:**
   1. GET: Solicita un recurso sin modificarlo.
   2. POST: Envía datos al servidor, a menudo para crear
   o actualizar un recurso.
   3. PUT: Envía datos al servidor para crear o reemplazar
   un recurso.
   4. DELETE: Solicita la eliminación de un recurso.
   5. PATCH: Envía datos parciales al servidor para
   modificar parcialmente un recurso.

 -
