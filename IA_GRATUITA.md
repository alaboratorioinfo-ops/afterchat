# AfterChat 0.5 — IA gratuita

Esta versión mantiene la integración de IA existente del proyecto y deja documentada
la configuración para usar el backend/Space de Hugging Face sin exponer claves en el
código del navegador.

IMPORTANTE:
- No coloques claves API dentro de index.html, JavaScript público ni repositorios públicos.
- La configuración del endpoint de IA debe hacerse mediante variables/configuración del
  backend o Space correspondiente.
- Si se añade Gemini posteriormente, la clave debe permanecer en el servidor/backend.

Objetivo:
AfterChat (frontend) -> backend/Space de IA -> modelo gratuito disponible -> respuesta.
