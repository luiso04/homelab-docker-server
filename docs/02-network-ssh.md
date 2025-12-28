## Red y acceso remoto

- Modo de red: Adaptador puente (Bridged)
- IP asignada por DHCP en red local
- Acceso remoto mediante SSH

### Seguridad SSH
- Acceso mediante claves públicas
- Login de root deshabilitado
- Autenticación por contraseña desactivada

### Firewall
- UFW habilitado
- Puertos permitidos:
  - 22 (SSH)
  - 80 / 443 (HTTP / HTTPS)
