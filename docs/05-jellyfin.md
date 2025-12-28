## Servidor multimedia (Jellyfin)

Jellyfin se despliega como servidor multimedia autoalojado mediante contenedores
Docker.

### Características
- Despliegue con Docker Compose
- Volúmenes persistentes para configuración y caché
- Biblioteca multimedia montada desde el host

### Seguridad
- Jellyfin no expone puertos directamente al host
- Acceso exclusivamente a través del reverse proxy
- Comunicación interna mediante red Docker aislada
