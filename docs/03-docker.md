## Docker y estructura del proyecto

Docker se utiliza como tecnología principal para el despliegue de servicios.

### Estructura de directorios
/srv/homelab
- compose/: archivos docker-compose
- data/: datos persistentes (no versionados)
- docs/: documentación del proyecto

### Redes Docker
- Red bridge externa: homelab
- Comunicación entre servicios exclusivamente mediante red interna
