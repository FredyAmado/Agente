# Guía de Visualización Gráfica (Canvas)

Tu asistente tiene la capacidad de mostrarte visualmente el progreso de las páginas web y diseños mediante la herramienta **Canvas** de OpenClaw.

## Cómo ver las visualizaciones

Como Telegram es principalmente texto, para ver las herramientas gráficas debes usar una de las siguientes opciones mientras hablas con tu bot:

1. **OpenClaw Control UI (Recomendado):**
   - Abre tu navegador en la computadora donde corre OpenClaw.
   - Ve a: `http://localhost:18789`
   - En la pestaña de chat o en la sección de Canvas, verás cómo el agente dibuja y construye las interfaces en tiempo real.

2. **Aplicaciones Complementarias:**
   - Si usas macOS, puedes ver el Canvas directamente en la barra de menú con **OpenClaw.app**.
   - En Android/iOS, la app de OpenClaw tiene una pestaña dedicada para el Canvas.

## Qué pedirle a tus agentes

Ahora puedes pedir cosas como:
- "CEO, dile al diseñador que me muestre un boceto del logo en el Canvas".
- "CEO, dile al frontend que renderice la estructura del landing page en el Canvas".

## Cómo funciona técnicamente
El agente utiliza una herramienta llamada `canvas_render` o `canvas_update`. He configurado a tus agentes de Frontend y Diseño para que utilicen estas herramientas automáticamente cuando les pidas visualizaciones.
