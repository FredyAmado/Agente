# Guía para subir tu Agente a GitHub

Sigue estos pasos para poner tu agente en tu propio repositorio:

1. **Crea un repositorio en GitHub:**
   - Ve a [github.com/new](https://github.com/new).
   - Ponle un nombre (ej: `mi-agente-emprendedor`).
   - Manténlo como **Privado** para mayor seguridad.

2. **Prepara la carpeta local:**
   - Abre una terminal en tu computadora y entra a la carpeta que te he preparado (`agente-emprendedor`).

3. **Inicializa Git y sube el código:**
   ```bash
   git init
   git add .
   git commit -m "Initial setup for Entrepreneur CEO Agent"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/TU_REPOSITORIO.git
   git push -u origin main
   ```

4. **¡Listo!** Ahora ya tienes tu código a salvo en GitHub. Recuerda **NUNCA** subir tu `openclaw.json` real si contiene tus llaves de API. Usa siempre el `.example` para compartir la estructura.
