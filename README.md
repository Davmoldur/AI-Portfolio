# Checkpoint 1 - Agente Autónomo Básico

## Descripción
Flujo en n8n que implementa un agente conversacional para e-commerce capaz de consultar stock y catálogo de productos en Airtable de forma autónoma y registrar la interacción en Slack.

## Componentes del Flujo
- **Trigger:** Chat Trigger.
- **Cerebro (AI Agent):** Tools Agent con OpenAI Chat Model (límite de 7 iteraciones).
- **Herramienta (Tool):** Search records in Airtable para consulta de catálogo.
- **Observabilidad:** Notificación en Slack con consulta y respuesta generada.

## Cómo importar
1. Descargar el archivo `checkpoint1_nombre_apellido.json`.
2. En n8n: Menú del lienzo -> *Import from File*.
3. Configurar las credenciales correspondientes (OpenAI, Airtable y Slack).
