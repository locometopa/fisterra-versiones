# Fisterra — versiones

Descargas de **Fisterra**, centro de control de red para el router Sagemcom F@st 5366SM y NAS Synology.

**Descargar la última versión:** [Fisterra 0.22](https://github.com/locometopa/fisterra-versiones/raw/main/0.22/Fisterra.exe)

Desde la 0.4, Fisterra se actualiza solo al abrirse (consulta `latest.json`). Se puede desactivar en *Ajustes*.

| Versión | Cambios |
|---|---|
| [0.22](0.22/Fisterra.exe) | Quitado el aviso de sesión/sync de Edge. Iconos del menú planos y monocromos. Nueva función **Wake-on-LAN** (encender equipos) y «Abrir web» de cada dispositivo. |
| [0.21](0.21/Fisterra.exe) | Separaciones corregidas: las rejillas de tarjetas dejan hueco con el bloque siguiente (Fibra e Inicio ya no se pegan). |
| [0.20](0.20/Fisterra.exe) | Cajas que ya no se pisan: las rejillas se reorganizan solas según el ancho (útil con el escalado de Windows). Menú reagrupado (Seguridad en RED, nuevo grupo Conectividad). |
| [0.19](0.19/Fisterra.exe) | Reinicio tras actualizar con nuevo método: relanza vía explorer.exe (shell de Windows), así el proceso nuevo no muere con el viejo. Arranque tolerante al solape de puerto. |
| [0.18](0.18/Fisterra.exe) | Menú lateral de texto como antes y barra de desplazamiento oscura acorde al tema. |
| [0.17](0.17/Fisterra.exe) | Reinicio tras actualizar más fiable: la versión nueva abre su propia ventana y la vieja se cierra sola; aviso claro si algo falla. |
| [0.16](0.16/Fisterra.exe) | Menú lateral como Driver Booster (carril de iconos). Botones separados: «Bloquear» y «Cerrar». |
| [0.15](0.15/Fisterra.exe) | Reinicio de la actualización arreglado: renombra el .exe en marcha y relanza reintentando el puerto; la ventana se recarga sola. Ya no se queda en «reiniciando». |
| [0.14](0.14/Fisterra.exe) | Nuevo aspecto estilo Driver Booster: negro con acento rojo, botones redondeados y cabecera de estado en Inicio. |
| [0.13](0.13/Fisterra.exe) | **Mapa de red**: lista los dispositivos conectados (nombre, IP, MAC, fabricante), avisa de equipos nuevos y reserva IP de un clic. **Chequeo de seguridad**: revisa contraseña, UPnP, puertos sensibles expuestos y CGNAT. |
| [0.12](0.12/Fisterra.exe) | Actualización sin ventana de consola ni bucles: lanzador oculto (VBScript) que espera a que el .exe se libere, lo sustituye y relanza. Cortafuegos anti-bucle si una actualización falla. |
| [0.11](0.11/Fisterra.exe) | Nuevo tema oscuro (estilo modem.tools): fondo azul marino, acentos turquesa y tarjetas redondeadas. |
| [0.10](0.10/Fisterra.exe) | Sin ventana de consola: arranca directo en su ventana de escritorio (solo avisa si hay un fallo). Arreglado el atasco de actualizaciones y apertura de ventana más robusta. Botón «Cerrar Fisterra». |
| [0.9](0.9/Fisterra.exe) | Se abre en su propia ventana compacta y centrada (modo app de Edge/Chrome), como una aplicación de escritorio. |
| [0.8](0.9/Fisterra.exe) | Fibra: además del SIP, extrae por API el perfil de conexión (VLAN y usuario PPPoE) útil para montar un router neutro. |
| [0.7](0.9/Fisterra.exe) | Fibra verificada en el F@st 5366S: recupera la identidad SIP (usuario, número, proxy, registrar) por la API del router. La clave GPON y la contraseña SIP no están en la API de este firmware. |
| [0.6](0.9/Fisterra.exe) | Fibra más robusta: extrae GPON/SIP primero por la API del router (sin SSH) rastreando el árbol de datos; SSH de respaldo probando varias contraseñas de root. |
| [0.5](0.9/Fisterra.exe) | Herramienta de fibra: extrae la clave GPON (hex→texto) y las credenciales SIP del router, automático por SSH o pegando el cfg.xml. |
| [0.4](0.9/Fisterra.exe) | Actualización automática: al abrirse busca la última versión, la descarga, verifica su huella SHA-256 y se reinicia. Opción en Ajustes. |
| [0.3](0.3/Fisterra.exe) | Nuevo nombre (antes Abre-Puertos) e icono de faro. Estilo empresarial, página centrada para monitores ultrawide, acceso remoto separado router/NAS. |

**Uso:** ejecuta `Fisterra.exe` y se abre en el navegador (`http://127.0.0.1:8777`). La primera vez Windows puede avisar con SmartScreen: *Más información → Ejecutar de todos modos*.
