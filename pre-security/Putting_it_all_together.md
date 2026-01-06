# Putting It All Together

## Objetivo
Unificar los conceptos aprendidos sobre DNS, HTTP y funcionamiento de sitios web, comprendiendo el flujo completo de cómo un usuario accede a una página web.



## Flujo general de acceso a un sitio web

Cuando un usuario accede a un sitio web, ocurren los siguientes pasos:

1. El usuario ingresa una URL en el navegador
2. El navegador revisa si existe información en caché
3. Si no existe, se consulta al sistema DNS
4. DNS traduce el dominio a una dirección IP
5. La petición es enviada al servidor correspondiente
6. La solicitud pasa por controles de seguridad
7. El servidor procesa la petición
8. La respuesta es enviada de vuelta al usuario



## Componentes involucrados

### DNS
- Traduce el nombre de dominio a una dirección IP
- Permite localizar el servidor correcto



### Web Application Firewall (WAF)
- Filtra y analiza las peticiones HTTP
- Bloquea tráfico malicioso o sospechoso



### Load Balancer
- Revisa qué servidor tiene menos carga
- Distribuye las peticiones entre varios servidores
- Mejora rendimiento y disponibilidad



### Servidor Web
- Recibe la petición HTTP (por ejemplo, GET)
- Procesa la solicitud
- Obtiene la información necesaria



### Base de Datos
- Almacena la información del sitio
- Proporciona datos solicitados por el servidor web



### Cliente (Usuario)
- Recibe la respuesta del servidor
- Renderiza el contenido en el navegador



## Importancia en ciberseguridad
Comprender este flujo permite:
- Identificar puntos donde pueden ocurrir ataques
- Detectar fallas en seguridad web
- Analizar incidentes desde una perspectiva completa
- Entender alertas en entornos SOC



## Aprendizajes clave
- Un sitio web depende de múltiples componentes
- DNS, HTTP y backend trabajan juntos
- El WAF y el balanceador cumplen roles críticos
- La seguridad se aplica en cada etapa del flujo
