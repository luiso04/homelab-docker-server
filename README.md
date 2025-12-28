# Homelab auto-gestionado con Docker

Proyecto de servidor doméstico auto-gestionado orientado a simular un entorno
de producción realista, utilizando Linux y contenedores Docker para el despliegue
de servicios autoalojados.

## Objetivos
- Desplegar un servidor Linux funcional sin entorno gráfico
- Ejecutar servicios mediante Docker Compose
- Centralizar el acceso mediante un reverse proxy
- Aplicar buenas prácticas de aislamiento y seguridad básica

## Stack tecnológico
- Ubuntu Server 24.04 LTS
- Docker y Docker Compose
- Caddy (reverse proxy)
- Jellyfin (media server)

## Servicios desplegados
- Reverse proxy para acceso unificado
- Servidor multimedia accesible únicamente a través del proxy

> Proyecto desarrollado inicialmente en máquina virtual (VirtualBox) como
> entorno de pruebas, con despliegue en hardware físico previsto.
