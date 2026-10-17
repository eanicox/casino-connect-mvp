# Casino Connect — GitHub Pages MVP

Demo estática conceptual. No utiliza cuentas, juegos ni dinero reales.

## Publicar

1. Subir `index.html` y `README.md` a la raíz de la rama `main` de `eanicox/casino-connect-mvp` (extraer el ZIP primero; no subir el ZIP como archivo único).
2. GitHub > Settings > Pages > Build and deployment > Deploy from a branch > `main` / `(root)` > Save.
3. Abrir `https://eanicox.github.io/casino-connect-mvp/` cuando GitHub Pages termine de publicar.

## Rutas

- `/#terminal` — pantalla QR para terminal
- `/#control` — control móvil ficticio
- `/#games` — verticales de juego simuladas

**Limitación:** el QR abre la pantalla de control, pero no vincula sesiones reales. GitHub Pages no ejecuta backend. Para un MVP conectado entre dispositivos se requiere servidor y autenticación segura.

El QR se genera con un servicio público externo (api.qrserver.com) y contiene solamente la URL pública de la demo; no enviar credenciales ni datos personales.
