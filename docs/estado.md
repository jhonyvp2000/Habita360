# Estado del proyecto Habita360

Última actualización: 2026-10-30

## Hecho

- Repositorio git en la rama `main`, vinculado con GitHub: el remoto `origin` apunta a https://github.com/jhonyvp2000/Habita360 (repositorio público).
- GitHub CLI (`gh`) tiene la sesión iniciada con la cuenta `jhonyvp2000` y permisos `repo`.
- Este resumen de estado (`docs/estado.md`).
- `.gitignore` creado para proteger secretos: excluye `.env` y `.env.*` (salvo `.env.example`), claves y certificados (`*.pem`, `*.key`, `*.p12`, `*.pfx`, `*.jks`, `*.keystore`, `id_rsa*`, `id_ed25519*`), `credentials.json`, `service-account*.json` y `secrets.*`. También excluye `.claude/settings.local.json`, dependencias, builds y archivos del sistema o del editor.
- Revisión de secretos: en el repositorio no hay ningún `.env` ni ninguna clave, ni en los archivos ni en el historial.

## A medias

- **Capturas de pantalla para el resumen visual (3 pantallas con datos inventados):** no se generaron. Todavía no hay código de la app, ni en local ni en GitHub, así que no hay nada que capturar. La pregunta sobre el concepto y el formato se canceló antes de responderla.

## Decisiones tomadas

- No inventar capturas de una app que no existe sin saber antes qué hace Habita360.
- Ignorar los secretos desde el principio, antes de que exista código, para que ninguna clave llegue a GitHub (el repositorio es público).
- Se permite subir `.env.example` como plantilla, sin valores reales.

## Pendientes

1. Definir qué es Habita360. Opciones que se plantearon: portal inmobiliario, administración de edificios, gestión de alquileres o recorridos virtuales 360°.
2. Elegir el formato de las capturas: web de escritorio (1440×900), móvil (390×844) o mixto.
3. Construir las pantallas (prototipo o app real) y generar las 3 capturas.
4. Convertir `README.md` de UTF-16 a UTF-8: tal como está, GitHub muestra caracteres raros.
5. Ampliar el README con la descripción del proyecto.
6. Cuando se elija el stack, añadir al `.gitignore` sus patrones específicos (por ejemplo `.venv/` o `__pycache__/` si es Python).
