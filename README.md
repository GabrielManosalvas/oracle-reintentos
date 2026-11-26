# Reintentos del servidor Oracle

Cada ~3 minutos, sin parar, GitHub Actions intenta crear el servidor  (Always Free) en Oracle São Paulo.
Cuando lo consigue abre un issue (llega un correo) y se desactiva solo.
Cada ejecución dura ~5,5 horas y se relanza sola; además hay un cron cada hora como respaldo.

- Para pausarlo: **Actions → Reintentar servidor Oracle → ⋯ → Disable workflow**.
- Las credenciales de Oracle viven en **Settings → Secrets and variables → Actions** y se borran al terminar.
- `llave-ssh.pub` es la llave **pública** del servidor (no es secreta).
