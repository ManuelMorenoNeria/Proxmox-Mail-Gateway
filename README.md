# Proxmox Mail Gateway

![6a6a75220ab5a226a74717a4a96bcf23](https://github.com/ManuelMorenoNeria/Proxmox-Mail-Gateway/assets/114908218/4a3620f5-7c1b-44fd-b6d5-e091381c1e2d)

## Descripción

Proxmox Mail Gateway es una solución de filtrado de correo electrónico de código abierto que proporciona protección contra spam, virus y otros tipos de amenazas. Este repositorio ofrece una guía detallada sobre la instalación, configuración y administración de Proxmox Mail Gateway.

## Contenido

- [Características](#características)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Configuración Inicial](#configuración-inicial)
- [Uso](#uso)

## Características

- Filtrado de spam y virus
- Reglas de filtrado personalizables
- Integración con LDAP y Active Directory
- Gestión de cuarentenas de correo
- Interfaz web intuitiva
- Actualizaciones automáticas de bases de datos de spam y antivirus

## Requisitos

Antes de instalar Proxmox Mail Gateway, asegúrate de que tu sistema cumpla con los siguientes requisitos:

- Un servidor con Proxmox VE instalado
- Acceso a internet para actualizaciones y descarga de paquetes
- Recursos de hardware adecuados (CPU, RAM, almacenamiento)

## Instalación

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

## Uso

- **Gestión de Correo**: Revisa y gestiona los correos en cuarentena.
- **Configuración de Reglas**: Personaliza las reglas de filtrado de correo.
- **Informes**: Genera informes sobre el tráfico de correo y las amenazas detectadas.

## Actualización

Mantén tu Proxmox Mail Gateway actualizado para garantizar la mejor protección contra las amenazas.

1. Accede a la interfaz web.
2. Navega a `Configuration > Updates`.
3. Aplica las actualizaciones disponibles.

## Contribuir

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Agregar nueva funcionalidad'`).
4. Empuja tus cambios a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Soporte

Si tienes problemas o preguntas, por favor abre un [issue](https://github.com/tu-usuario/proxmox-mail-gateway/issues) en el repositorio.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

¡Gracias por usar Proxmox Mail Gateway! Si tienes alguna sugerencia o mejora, no dudes en contribuir.
