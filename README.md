# TrackFlow — Frontend

Prototipo de la interfaz de TrackFlow, construido en Claude Design a partir del backend en
[EynerCG/trackflow](https://github.com/EynerCG/trackflow).

## Contenido

- `TrackFlow.dc.html` — el prototipo interactivo (las 6 pantallas: rastreo público, registrar
  envío, registrar evento, login, admin).
- `TrackFlow Especificación.dc.html` — el brief de diseño usado para construirlo (contrato de
  la API, reglas de negocio, estados por pantalla).
- `_ds/` — el sistema de diseño ("Industry") usado por el prototipo.
- `uploads/` — logo y referencias visuales usadas durante el diseño.

## Backend

El prototipo llama al backend real de TrackFlow. La URL base es configurable (tweak
`apiBaseUrl`):

- Local: `http://localhost:8080`
- Producción: `https://trackflow-5enb.onrender.com`

El plan gratuito de Render duerme tras inactividad: la primera petición después de un rato
puede tardar más de un minuto en responder.

## Estado

Prototipo de diseño, no la implementación final. El plan es reconstruirlo como una app Next.js
independiente, reutilizando este mismo contrato de API y sistema visual.
