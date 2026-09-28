# Servidor Linux

Proyecto para configurar y desplegar un servidor web en una red local con infraestructura de servidores y terminales.

## Objetivos
* Configurar un servidor web en Linux.
* Asignar IPs fijas a los equipos de la red.
* Crear una guía clara de instalación.

## Tecnologías
* Debian Linux
* Apache
* Markdown

## Equipos de la Red

| Equipo | IP | SO |
| :--- | :--- | :--- |
| Servidor | 192.168.1.10 | Debian |
| PC01 | 192.168.1.20 | Windows |
| PC02 | 192.168.1.21 | Ubuntu |

## Arquitectura

<img width="270" height="148" alt="descarga" src="https://github.com/user-attachments/assets/75a77c77-1abc-4498-8cc8-6f3330c206c2" />


## Instalación
Para verificar la red usa el comando `ip addr` en la terminal.

Para instalar el servidor ejecuta:

```bash
sudo apt update
sudo apt install apache2 -y
```
**Completadas**:

[x] Crear repositorio   
PDF

[x] Instalación / Instalar y configurar el servidor web Apache   
PDF

**Pendientes**:

[ ] Configurar servidor / Configurar los certificados de seguridad SSL/TLS   
PDF

[ ] Pruebas / Realizar las pruebas de carga y optimización del sistema   
PDF
