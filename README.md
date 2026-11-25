# Reintentos del servidor Oracle

Cada 10 minutos, GitHub Actions intenta crear el servidor `portal-ramos` (Always Free) en Oracle São Paulo.
Cuando lo consigue abre un issue (llega un correo) y se desactiva solo.

- Para pausarlo: **Actions → Reintentar servidor Oracle → ⋯ → Disable workflow**.
- Las credenciales de Oracle viven en **Settings → Secrets and variables → Actions** y se borran al terminar.
- `llave-ssh.pub` es la llave **pública** del servidor (no es secreta).
