## Configuración de Reglas de Filtrado de Spam y Antivirus

Proxmox Mail Gateway ofrece poderosas herramientas para el filtrado de spam y antivirus. A continuación, detallamos algunas:

![image](https://github.com/ManuelMorenoNeria/Proxmox-Mail-Gateway/assets/114908218/32adf704-880c-4971-81f5-fd63b13a8bdb)

- **Use Auto-Whitelist**: Lista blanca automática para remitentes conocidos.
- **Use Bayesian Filter**: Clasifica correos basándose en su contenido y aprendizaje automático.
- **Use RBL Checks**: Verifica si la IP del remitente está en listas negras conocidas.
- **Use Razor2 Checks**: Utiliza la retroalimentación de usuarios para identificar spam.
- **Extract Text from Attachments**: Analiza texto en archivos adjuntos.
- **Max Spam Size**: Establece el tamaño máximo para correos marcados como spam.
- **Languages**: Especifica idiomas a analizar.
- **Backscatter Score**: Identifica y clasifica automáticamente correos de rebote como spam.
- **Heuristic Score**: Clasifica correos basándose en características del mensaje.
