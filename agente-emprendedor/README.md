# Agente Emprendedor (CEO) con OpenClaw 🦞

Este repositorio contiene la configuración para un asistente personal de IA especializado en crear empresas digitales, orquestando un equipo de sub-agentes expertos.

## Estructura del Proyecto
- `openclaw.json.example`: Plantilla de configuración (debe renombrarse a `openclaw.json`).
- `workspace/`:
    - `SOUL.md`: Define la personalidad del CEO.
    - `AGENTS.md`: Define los roles y cómo se orquestan los sub-agentes.
    - `skills/`: Contiene los "cerebros" de tus especialistas (Frontend, Backend, Ads, etc.).

## Requisitos
- Node.js 22.16+ (Recomendado Node 24).
- Una cuenta en [Google AI Studio](https://aistudio.google.com/) para la API Key de Gemini.
- (Opcional) Una cuenta en **OpenCode** para usar modelos de código especializados.
- Un Bot de Telegram (creado vía [@BotFather](https://t.me/botfather)).

## Instalación Rápida

1. Instala OpenClaw globalmente:
   ```bash
   npm install -g openclaw@latest
   ```

2. Clona este repositorio en tu computadora.

3. Configura tus credenciales:
   - Copia `openclaw.json.example` a `openclaw.json`.
   - Edita `openclaw.json` e inserta tu `apiKey` de Google, tu `botToken` de Telegram, y opcionalmente tu `apiKey` de OpenCode.

4. Inicia el asistente:
   ```bash
   openclaw gateway
   ```

5. ¡Habla con tu asistente en Telegram!

## Cómo usarlo
- Simplemente escribe tu idea de negocio en el chat de Telegram.
- El CEO analizará la idea y empezará a delegar tareas a los sub-agentes.
- Puedes pedir cosas como: "CEO, pídele al Analista de Mercado que investigue a mi competencia" o "CEO, dile al Frontend que haga un boceto del landing page".
