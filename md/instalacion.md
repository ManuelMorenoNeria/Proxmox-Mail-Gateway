### Descarga de la ISO

Descarga la ISO de Proxmox Mail Gateway desde el [sitio oficial de Proxmox](https://www.proxmox.com/en/downloads/proxmox-mail-gateway).
   
![image](https://github.com/ManuelMorenoNeria/Proxmox-Mail-Gateway/assets/114908218/de693498-0e0b-4314-bef8-647c98793b51)

### Creación de la Máquina Virtual

1. Inicia sesión en tu servidor Proxmox VE.
2. Sube la ISO descargada a la biblioteca de imágenes ISO de Proxmox VE.

   ![image](https://github.com/ManuelMorenoNeria/Proxmox-Mail-Gateway/assets/114908218/0645b79c-7b83-4c03-a9c3-f0da0fa53369)

4. Crea una nueva máquina virtual utilizando la ISO de Proxmox Mail Gateway. Averigua su IP, ya que nos hara falta mas tarde para poder acceder mas adelante
   
   ![image](https://github.com/ManuelMorenoNeria/Proxmox-Mail-Gateway/assets/114908218/9534e980-ca58-4a5c-8652-b05d3e9793eb)


### Configuración de la Máquina Virtual

1. Asigna recursos adecuados (CPU, RAM, almacenamiento) a la máquina virtual. Si necesitas saber los requisitos [¡Aquí puedes verlos!](/md/requisitos.md)
2. Configura la red para asegurarte de que la VM tenga acceso a internet y pueda comunicarse con otros sistemas en tu red.

### Instalación de Proxmox Mail Gateway

1. Arranca la VM desde la ISO de Proxmox Mail Gateway.
2. Sigue las instrucciones del asistente de instalación.

## Configuración Inicial

1. Accede a la interfaz web de Proxmox Mail Gateway a traves de la IP de la VM. Ejemplo: `https://192.168.6.238:8006/`. (Si necesitas saber la IP de tu VM ejecuta el comando `ip a` para saber la IP de la VM)
2. Inicia sesión con las credenciales configuradas durante la instalación.
3. Configura los dominios y servidores de correo destino. ¿Quieres ver cómo?, [¡Aquí puedes!](/md/dominios.md)
4. Establece reglas de filtrado de spam según tus necesidades. ¿Quieres ver cómo? [¡Aquí puedes!](/md/spam.md)
