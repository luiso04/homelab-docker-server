## Reverse proxy

Se utiliza Caddy como reverse proxy para centralizar el acceso a los servicios.

### Funciones
- Punto único de entrada al servidor
- Encaminamiento de peticiones a servicios internos
- Preparado para HTTPS automático con certificados TLS

### Configuración
- Puertos expuestos al host: 80 y 443
- Servicios accesibles únicamente a través del proxy
- Comunicación interna mediante red Docker compartida
