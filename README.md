
## Procesos posteriores al despliege inicial

### Generar el know_hosts para github
``` ssh-keyscan -t rsa github.com >> ~/.ssh/known_hosts

### Cambiar los permisos de la llave privada
``` chmod 600 ~/.ssh/id_ed25519
