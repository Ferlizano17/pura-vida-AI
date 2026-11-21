# Pura Vida IA

Web de Pura Vida IA con un asistente de IA.

- `public/`: páginas de la web (`index.html` y `legal.html`).
- `netlify/functions/chat.mjs`: función que conecta el chat con la API de Claude. Aquí están las instrucciones del asistente.
- `netlify.toml`: configuración de publicación en Netlify.

La clave de la API se guarda en Netlify como variable de entorno `ANTHROPIC_API_KEY`. Nunca debe subirse a este repositorio.
