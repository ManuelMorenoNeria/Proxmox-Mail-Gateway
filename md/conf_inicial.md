### Configuración de la Máquina Virtual

1. Asigna recursos adecuados (CPU, RAM, almacenamiento) a la máquina virtual. Si necesitas saber los requisitos [¡Aquí puedes verlos!](/md/requisitos.md)
2. Configura la red para asegurarte de que la VM tenga acceso a internet y pueda comunicarse con otros sistemas en tu red.

### Instalación de Proxmox Mail Gateway

1. Arranca la VM desde la ISO de Proxmox Mail Gateway.
2. Sigue las instrucciones del asistente de instalación.

## Configuración Inicial

1. Accede a la interfaz web de Proxmox Mail Gateway a traves de la IP de la VM. Ejemplo: `https://192.168.6.238:8006/`. (Si necesitas saber la IP de tu VM ejecuta el comando `ip a` para saber la IP de la VM)
2. Inicia sesión con las credenciales configuradas durante la instalación.
3. Configura los dominios y servidores de correo destino. ¿Quieres ver cómo?, [¡Aquí puedes!](/md/dominio.md)
4. Establece reglas de filtrado de spam según tus necesidades. ¿Quieres ver cómo? [¡Aquí puedes!](/md/spam.md)
