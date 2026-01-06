# How Websites Work

## Objetivo
Comprender cómo funcionan los sitios web, la diferencia entre frontend y backend, y cómo un atacante puede obtener información sensible a partir del código de una página web.



## ¿Cómo funcionan los sitios web?
Un sitio web funciona mediante la interacción entre dos partes principales:
- **Frontend**
- **Backend**

El usuario interactúa con el frontend, mientras que el backend procesa la lógica y los datos.



## Frontend
El **frontend** es la parte visible del sitio web, es decir, lo que el usuario ve e interactúa en el navegador.

Tecnologías vistas:
- **HTML**: estructura del sitio
- **JavaScript**: comportamiento dinámico del sitio

El código frontend es accesible para cualquier usuario, por lo que nunca debe contener información sensible.



## Backend
El **backend** es la parte del sitio que:
- Procesa la lógica
- Maneja bases de datos
- Controla autenticación y permisos

El backend no es visible directamente para el usuario, pero se comunica con el frontend mediante peticiones HTTP.



## HTML
HTML define la estructura de una página web:
- Títulos
- Formularios
- Enlaces
- Campos de entrada

El código HTML puede ser inspeccionado desde el navegador para obtener información sobre el funcionamiento del sitio.



## JavaScript
JavaScript permite que las páginas web:
- Respondan a acciones del usuario
- Validan datos en el navegador
- Ejecuten lógica del lado del cliente

Un uso incorrecto de JavaScript puede exponer información sensible o permitir manipulaciones.



## Sensitive Data Exposure
Se habló sobre la **exposición de datos sensibles**, que ocurre cuando:
- Credenciales están en el código fuente
- Comentarios revelan información interna
- Variables sensibles son visibles en frontend

Este tipo de fallas puede ser aprovechado por atacantes.



## HTML Injection
La **HTML Injection** ocurre cuando un sitio web permite que un usuario inyecte código HTML sin validación adecuada.

Esto puede permitir:
- Modificar la apariencia de la página
- Engañar a otros usuarios
- Preparar ataques más avanzados



## Importancia en ciberseguridad
Este conocimiento es clave porque:
- Muchas vulnerabilidades web ocurren en el frontend
- El análisis del código fuente puede revelar fallas
- SOC y analistas revisan este tipo de comportamientos en incidentes web



## Aprendizajes clave
- Los sitios web se dividen en frontend y backend
- El código frontend es visible y no debe contener datos sensibles
- HTML y JavaScript pueden revelar información importante
- La HTML Injection es una vulnerabilidad común si no hay validaciones
