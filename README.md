Proyecto desarrollado para conectar formularios de Google Ads (Lead Forms) con la plataforma de CRM Clientify, mediante un webhook intermedio que recibe los datos del lead y los procesa para su registro automático en el CRM.

Objetivo:
Automatizar la captura y envío de leads generados en campañas de Google Ads hacia Clientify, permitiendo un seguimiento inmediato desde el CRM, sin intervención manual ni pérdida de información.

Funcionalidades:
Recepción segura de datos desde Google Ads via Webhook.

Validación de estructura y autenticidad del payload.

Transformación de campos según los requerimientos de Clientify (nombre, email, teléfono, etc.).

Envío del lead utilizando la API REST de Clientify.

Registro de logs y respuestas de la API para monitoreo y debugging.

Manejo de errores y reintentos en caso de fallos temporales.

Tecnologías utilizadas:
Node.js con Express.js para el servidor Webhook.

Axios para el consumo de la API de Clientify.

Dotenv y configuración de tokens seguros.

Firebase / Heroku / Vercel (según entorno de despliegue).

Este sistema permite escalar campañas de marketing automatizadas, reduciendo el tiempo de respuesta comercial y mejorando la conversión de leads.
