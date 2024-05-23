### Configurar Dominios 

Proxmox Mail Gateway necesita saber a qué dominios debe filtrar el correo y a qué servidores debe enviar los correos filtrados. Aquí te mostramos cómo configurar esto:

1. **Acceder a la Configuración de Correo**:
   - En la interfaz web, navega a `Configuration` en el menú principal.

2. **Agregar Dominios**:
   - Ve a la sección `Mail Proxy`.
   - Haz clic en `Relay Domains`.
   - Haz clic en `Add` para agregar un nuevo dominio.
   - Ingresa el nombre del dominio (por ejemplo, Ejemplo.com).

    ![image](https://github.com/ManuelMorenoNeria/Proxmox-Mail-Gateway/assets/114908218/2850e377-8aa7-4453-bcfa-237ff24a9068)


Esto nos permite especificar los dominios para los cuales el gateway actuará como un relay, es decir, los dominios que el Proxmox Mail  Gateway gestionará, filtrará y reenviará el correo.
