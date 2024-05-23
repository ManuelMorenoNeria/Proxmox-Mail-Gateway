### Descarga de la ISO

1. Descarga la ISO de Proxmox Mail Gateway desde el [sitio oficial de Proxmox](https://www.proxmox.com/en/downloads/category/mail-gateway).

### Creación de la Máquina Virtual

1. Inicia sesión en tu servidor Proxmox VE.
2. Sube la ISO descargada a la biblioteca de imágenes ISO de Proxmox VE.
3. Crea una nueva máquina virtual utilizando la ISO de Proxmox Mail Gateway.

### Configuración de la Máquina Virtual

1. Asigna recursos adecuados (CPU, RAM, almacenamiento) a la máquina virtual.
2. Configura la red para asegurarte de que la VM tenga acceso a internet y pueda comunicarse con otros sistemas en tu red.

### Instalación de Proxmox Mail Gateway

1. Arranca la VM desde la ISO de Proxmox Mail Gateway.
2. Sigue las instrucciones del asistente de instalación.

## Configuración Inicial

1. Accede a la interfaz web de Proxmox Mail Gateway en `https://<IP_de_la_VM>:8006`.
2. Inicia sesión con las credenciales configuradas durante la instalación.
3. Configura los dominios y servidores de correo destino.
4. Establece reglas de filtrado de spam y antivirus según tus necesidades.
5. Configura las actualizaciones automáticas para las bases de datos de spam y antivirus.
