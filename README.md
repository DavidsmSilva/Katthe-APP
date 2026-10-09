# Socialización RIT 2026 — Formulario conectado con GitHub

Formulario de constancia y evaluación del Reglamento Interno de Trabajo 2026 de Fractal Estrategias Sostenibles S.A.S. Cada respuesta queda registrada como un **issue** en este repositorio y una GitHub Action la califica automáticamente.

## Cómo responder

- **Formulario de GitHub (nativo):** https://github.com/DavidsmSilva/Katthe-APP/issues/new?template=socializacion-rit.yml
- **Página web (GitHub Pages):** https://davidsmsilva.github.io/Katthe-APP/ — muestra la calificación al instante y abre GitHub con las respuestas listas.

## Cómo funciona

| Archivo | Función |
|---|---|
| `.github/ISSUE_TEMPLATE/socializacion-rit.yml` | Formulario nativo de GitHub (datos, 10 preguntas, constancia) |
| `docs/index.html` | Versión web del formulario para GitHub Pages |
| `.github/scripts/quiz.json` / `docs/quiz.json` | Preguntas y respuestas correctas |
| `.github/workflows/calificar-rit.yml` | Califica cada respuesta, comenta el resultado y etiqueta `aprobado` / `requiere-repaso` (mínimo 70 %) |

Para ver todas las respuestas: pestaña **Issues**, filtro `label:socializacion-rit`.

## Activar la página web

Settings → Pages → *Build and deployment* → Source: **Deploy from a branch** → rama `claude/upbeat-volta-ydmejc` (o la rama por defecto), carpeta **/docs** → Save.

> Si el repositorio es público, los issues también lo son: no se piden números de documento ni datos sensibles.
