# Fisterra — versiones

Descargas de **Fisterra**, centro de control de red para el router Sagemcom F@st 5366SM y NAS Synology.

**Descargar la última versión:** [Fisterra 0.7](https://github.com/locometopa/fisterra-versiones/raw/main/0.7/Fisterra.exe)

Desde la 0.4, Fisterra se actualiza solo al abrirse (consulta `latest.json`). Se puede desactivar en *Ajustes*.

| Versión | Cambios |
|---|---|
| [0.7](0.7/Fisterra.exe) | Fibra verificada en el F@st 5366S: recupera la identidad SIP (usuario, número, proxy, registrar) por la API del router. La clave GPON y la contraseña SIP no están en la API de este firmware. |
| [0.6](0.7/Fisterra.exe) | Fibra más robusta: extrae GPON/SIP primero por la API del router (sin SSH) rastreando el árbol de datos; SSH de respaldo probando varias contraseñas de root. |
| [0.5](0.7/Fisterra.exe) | Herramienta de fibra: extrae la clave GPON (hex→texto) y las credenciales SIP del router, automático por SSH o pegando el cfg.xml. |
| [0.4](0.7/Fisterra.exe) | Actualización automática: al abrirse busca la última versión, la descarga, verifica su huella SHA-256 y se reinicia. Opción en Ajustes. |
| [0.3](0.3/Fisterra.exe) | Nuevo nombre (antes Abre-Puertos) e icono de faro. Estilo empresarial, página centrada para monitores ultrawide, acceso remoto separado router/NAS. |

**Uso:** ejecuta `Fisterra.exe` y se abre en el navegador (`http://127.0.0.1:8777`). La primera vez Windows puede avisar con SmartScreen: *Más información → Ejecutar de todos modos*.
