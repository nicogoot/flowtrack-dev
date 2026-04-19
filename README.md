# FlowTrack DEV

Entorno de staging para probar cambios antes de promoverlos a producción.

- **Producción**: `https://tuusuario.github.io/flowtrack/`
- **Backend**: mismo Apps Script + Sheet que producción (datos compartidos)
- **Deploy**: automático al pushear a main

⚠️ Cambios destructivos (endpoints que escriben) deben probarse contra un Sheet de prueba.
