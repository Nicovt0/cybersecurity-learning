# Linux Fundamentals – Part 1

## Objetivo
Este writeup documenta los fundamentos básicos de Linux aprendidos en la sala *Linux Fundamentals Part 1* de TryHackMe, incluyendo el uso de la terminal, comandos esenciales, navegación por el sistema de archivos y operadores básicos de la shell.  
Las prácticas fueron realizadas en una máquina virtual basada en **Ubuntu** proporcionada por la plataforma TryHackMe.

Estos conceptos son fundamentales para el trabajo en ciberseguridad y para el uso de herramientas en entornos reales.


## Introducción a Linux
Linux es uno de los sistemas operativos más utilizados en el mundo de la tecnología y especialmente en ciberseguridad. Su popularidad se debe a su estabilidad, seguridad y flexibilidad, además de ser el sistema base de la mayoría de servidores y herramientas utilizadas por analistas de seguridad y pentesters.

Durante esta sala se interactuó por primera vez con una máquina Linux (Ubuntu) utilizando la terminal, aprendiendo a ejecutar comandos básicos y a comprender cómo se organiza el sistema.


## Uso de la terminal
La terminal permite interactuar directamente con el sistema operativo mediante comandos. A través de ella es posible navegar por directorios, visualizar archivos, buscar información y automatizar tareas, lo cual es esencial en entornos de seguridad.


## Comandos fundamentales

El comando `echo` se utiliza para mostrar texto en pantalla y también para enviar texto hacia archivos cuando se combina con operadores de redirección.

```bash
echo "Texto de ejemplo"
```

El comando `whoami` permite identificar el usuario con el que se está trabajando actualmente en el sistema.

```bash
whoami
```

El comando `pwd` muestra la ruta completa del directorio en el que el usuario se encuentra actualmente.

```bash
pwd
```

El comando `ls` permite listar el contenido de un directorio, el cual permite visualizar archivos y carpetas.

```bash
ls
```

El comando `cd` permite cambiar de directorio, lo cual es esencial para navegar por el sistema de archivos.

```bash
cd /ruta/del/directorio
```

El comando `cat` permite mostrar el contenido de un archivo en pantalla.

```bash
cat nombre_del_archivo
```

El comando `find` permite buscar archivos dentro del sistema, el cual permite localizar archivos por nombre u otros criterios.

```bash
find /ruta/del/directorio -name "nombre_del_archivo"
```

El comando `wc` se utiliza para contar líneas, palabras o caracteres dentro de un archivo.

```bash
wc nombre_del_archivo
```

El comando `grep` permite buscar texto específico dentro de archivos, siendo especialmente útil para análisis de logs o búsqueda de información relevante.

```bash
grep "texto_a_buscar" nombre_del_archivo
```

##Operadores de la shell

El operador & permite ejecutar un comando en segundo plano sin bloquear la terminal.

El operador && permite ejecutar un segundo comando únicamente si el primero se ejecuta correctamente.

```bash
comando1 && comando2
```

El operador > redirige la salida de un comando hacia un archivo, sobrescribiendo su contenido.

```bash
echo "Texto de ejemplo" > nombre_del_archivo
```

El operador >> redirige la salida de un comando hacia un archivo, agregando su contenido al final del archivo.

```bash
echo "Texto de ejemplo" >> nombre_del_archivo
```

#Aplicación en ciberseguridad

Los comandos y operadores aprendidos en esta sala son ampliamente utilizados en tareas de ciberseguridad, tales como:

- Análisis de archivos y logs

- Búsqueda de indicadores de compromiso

- Automatización de tareas en sistemas Linux

- Investigación de incidentes en entornos SOC

Comprender estos fundamentos permite avanzar hacia herramientas y técnicas más avanzadas de análisis y seguridad.