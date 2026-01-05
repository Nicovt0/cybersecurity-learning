# DNS in Detail

## Objetivo
Comprender cómo funciona el sistema DNS, su rol en Internet y los distintos tipos de registros utilizados para resolver nombres de dominio.



## ¿Qué es DNS?
El **Domain Name System (DNS)** es el sistema que permite traducir un **nombre de dominio** (por ejemplo, `example.com`) en una **dirección IP**, que es la que utilizan los dispositivos para comunicarse entre sí.

Sin DNS, los usuarios tendrían que memorizar direcciones IP en lugar de nombres.



## Top-Level Domains (TLD)
Los **TLD** son la última parte de un nombre de dominio y ayudan a identificar el propósito del sitio.

Ejemplos:
- `.com` → comercial
- `.edu` → educación
- `.gov` → gobierno
- `.org` → organizaciones



## Tipos de registros DNS
Un dominio puede tener distintos tipos de registros, cada uno con una función específica.

### A
- Asocia un dominio a una dirección **IPv4**

### AAAA
- Asocia un dominio a una dirección **IPv6**

### MX
- Define los servidores de **correo electrónico** del dominio

### TXT
- Almacena información en texto
- Usado para verificaciones, políticas de correo y seguridad



## Servidores DNS Authoritative
Los **authoritative servers** son los servidores que contienen la información DNS oficial de un dominio.

Estos servidores:
- No almacenan el sitio web
- Proveen la información correcta sobre el dominio (IP, correo, etc.)



## Consultas DNS
Durante la sala se realizaron consultas DNS utilizando comandos que permiten especificar el tipo de registro:

```bash
--type=A
--type=AAAA
--type=MX
--type=TXT
