# HTTP in Detail

## Objetivo
Comprender cómo funciona el protocolo HTTP, cómo se comunican los clientes con los servidores web y qué elementos intervienen en una petición HTTP.



## ¿Qué es HTTP?
**HTTP (HyperText Transfer Protocol)** es un protocolo que permite la comunicación entre un **cliente** (por ejemplo, un navegador web) y un **servidor**.

HTTP define:
- Cómo se realizan las peticiones
- Cómo responde el servidor
- Qué información se envía en cada comunicación



## HTTP vs HTTPS
- **HTTP**: los datos viajan en texto plano
- **HTTPS**: utiliza cifrado para proteger la información transmitida

HTTPS es fundamental para proteger credenciales y datos sensibles.



## Métodos HTTP
Durante la sala se utilizaron distintos métodos HTTP:

### GET
- Solicita información al servidor
- No modifica datos

### POST
- Envía datos al servidor
- Se usa comúnmente en formularios

### PUT
- Actualiza información existente

### DELETE
- Elimina recursos del servidor



## Códigos de estado HTTP
Los servidores responden con códigos que indican el resultado de la petición.

### Categorías vistas
- **100** → Respuestas informativas
- **200** → Peticiones exitosas
- **400** → Errores del cliente
- **500** → Errores del servidor

Ejemplos:
- `200 OK`
- `404 Not Found`
- `500 Internal Server Error`



## Headers HTTP
Los **headers** contienen información adicional sobre la petición o la respuesta, como:
- Tipo de contenido
- Información del navegador
- Autenticación
- Cookies



## Cookies y sesiones
- **Cookies**: pequeños datos almacenados en el navegador
- **Sesiones**: permiten mantener la autenticación del usuario

Ambos se utilizan para identificar y mantener el estado del usuario en aplicaciones web.



## Práctica realizada
Durante la sala se ejecutaron peticiones HTTP utilizando distintos métodos (`GET`, `POST`, `PUT`, `DELETE`), especificando:
- URLs específicas
- IDs de recursos
- Acciones concretas sobre páginas o datos

Esto permitió comprender cómo interactuar directamente con aplicaciones web.



## Importancia de HTTP en ciberseguridad
HTTP es clave en seguridad porque:
- Muchas vulnerabilidades ocurren a nivel web
- El análisis de peticiones permite detectar ataques
- SOC y pentesters monitorean tráfico HTTP constantemente



## Aprendizajes clave
- HTTP define la comunicación cliente-servidor
- Existen distintos métodos para interactuar con recursos
- Los códigos de estado indican el resultado de las peticiones
- Headers, cookies y sesiones son elementos fundamentales
