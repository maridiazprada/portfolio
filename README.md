# 👩‍💻 Portfolio de Automatización

Este repositorio reúne algunos de los flujos de automatización desarrollados para optimizar procesos internos en empresas, reducir errores operativos y mejorar la eficiencia del equipo.

---

## 🛠️ Herramientas utilizadas

- **n8n** (automatización de workflows)
- **Airtable** (base de datos flexible tipo no-code)
- **Google Sheets**
- **Kommo CRM**
- **APIs REST, Webhooks y autenticaciones OAuth2**
- **OpenAI GPT y Whisper** (procesamiento de lenguaje natural y transcripción de voz)

---

## 📁 Proyectos incluidos

### `asistente_virtual_agio.json`
**Asistente conversacional inteligente** para una fábrica de muebles.  
Integra Kommo CRM con OpenAI GPT para detectar intenciones del cliente, responder de forma empática y derivar prospectos calificados al equipo comercial.  
Incluye:
- Memoria contextual de conversaciones
- Integración con catálogo
- Reconocimiento de voz con Whisper

---

### `act_precios_LOOP.json`
**Automatización escalable** para actualizar precios en Airtable usando catálogos de proveedores.  
Incluye:
- Loop con paginación y manejo de offsets
- Validación y limpieza de datos
- Actualización masiva en base de datos
- Preparado para grandes volúmenes (+1000 registros)

---

### `act_precios_NEW.json`
**Versión modular optimizada** del flujo de actualización de precios.  
Diseñado por proveedor, permite:
- Estructura clara y mantenible
- Condiciones específicas por lote
- Comparación eficiente entre Google Sheets y Airtable
- Menor consumo de recursos

---

## 🚀 Impacto

Estas automatizaciones permitieron:
- Reducir tiempos de actualización de precios de días a minutos
- Filtrar y calificar prospectos automáticamente, mejorando la conversión comercial
- Minimizar errores manuales y mejorar la toma de decisiones con datos actualizados

---

💡 *Este portfolio sigue en construcción. Próximamente sumaré nuevos flujos y casos de uso.*
