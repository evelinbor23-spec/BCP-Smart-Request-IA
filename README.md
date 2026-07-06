🤖 Smart Request IA - BC_Proyectos
📌 Descripción

Smart Request IA es una solución diseñada para automatizar la recepción, registro y clasificación inicial de solicitudes de clientes enviadas por correo electrónico.

El sistema combina automatización de procesos, Inteligencia Artificial generativa y validación humana para mejorar la trazabilidad, reducir tiempos operativos y estandarizar la gestión de requerimientos desde su ingreso.

🚀 Tecnologías utilizadas
n8n
Google Gemini
Gmail API
Airtable
Inteligencia Artificial Generativa
Human in the Loop

🔄 Flujo del proceso
Recepción de correo electrónico con filtro aplicado por asunto que contiene la referencia “REQ -”, asegurando que solo ingresen solicitudes válidas.
Creación automática del registro del requerimiento en Airtable.
Análisis del contenido del correo mediante Google Gemini.
Intento de clasificación automática del requerimiento.
Actualización del registro en caso de éxito o registro del error en caso de falla.
En caso de error, envío automático de notificación al equipo responsable para su revisión.
Derivación del caso a instancia de validación humana según corresponda.

🧠 Clasificación automática
La IA intenta determinar automáticamente:

Tipo de solicitud
Prioridad
Complejidad
Equipo responsable
Comentarios de análisis

En caso de no poder procesar la información, el sistema registra el error para asegurar trazabilidad y activar la alerta correspondiente.

⚠️ Manejo de errores

Cuando la IA no logra clasificar correctamente el requerimiento:

Se registra el error en Airtable
Se mantiene la trazabilidad del caso
Se envía una alerta automática al equipo responsable
Se finaliza el flujo de automatización con notificación
👤 Human in the Loop

Cada requerimiento clasificado por la IA pasa a una instancia de revisión humana, donde el equipo valida la información antes de su gestión final.

📂 Archivos
Workflow de n8n (.json)
Documentación técnica
Evidencia del flujo (capturas y ejecución)
📈 Beneficios
Automatiza la recepción de solicitudes.
Estandariza el ingreso de información.
Reduce tiempos de clasificación manual.
Mejora la trazabilidad end-to-end del proceso.
Incorpora IA generativa en la operación diaria.
Permite detección y gestión de errores en tiempo real.

Proyecto desarrollado como Trabajo Final de Automatización con Inteligencia Artificial.
