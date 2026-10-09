# LeadFlow AI

LeadFlow AI es una automatización para la gestión de consultas inmobiliarias construida con n8n.

## Stack

- n8n
- Airtable
- Notion
- Cohere
- Telegram
- Gmail
- Slack

## Flujo

Airtable Trigger
→ Validación de Estado
→ RAG con Notion
→ Cohere
→ Persistencia en Airtable
→ Human-in-the-Loop con Telegram
→ Gmail
→ Trazabilidad y alertas con Slack

## Características

- RAG con contexto real inyectado al prompt
- Human-in-the-Loop
- Prevención de loops
- Estados persistentes
- Manejo de errores
- Trazabilidad
- Alertas mediante Slack
- Dashboard con KPIs

## Archivos

- `LeadFlow_AI_Workflow_Final.json`: workflow exportado de n8n
- `LeadFlow_AI_Arquitectura.pdf`: diagrama de arquitectura

## Seguridad

Las credenciales, API keys y secretos utilizados por las integraciones no se incluyen en este repositorio.
