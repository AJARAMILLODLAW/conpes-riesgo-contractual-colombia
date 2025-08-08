# 🧠 Prompts Utilizados para Extracción de Datos Jurídicos - Proyecto CONPES Riesgo Contractual

## 📌 Prompt Base - Versión 1

**Fecha:** 08 de agosto de 2025  
**Patrón usado:** Template Pattern + Cognitive Verifier Pattern  
**Propósito:** Extraer campos clave de documentos CONPES sobre gestión de riesgos en contratación pública.

### Prompt:

> Actúa como un analista jurídico especializado en políticas públicas de riesgo contractual en Colombia. Vas a extraer información de documentos CONPES que tengan como objeto la gestión del riesgo contractual en la contratación estatal.  
>   
> Organiza los datos en la siguiente estructura tabular:
>
> - 🆔 **Número CONPES**  
> - 📅 **Año de publicación**  
> - 🏢 **Sector** (ej. Infraestructura, Salud, Defensa)  
> - 🧱 **Subsector** (ej. carreteras, aeropuertos, APP, hospitales, logística)  
> - ⚠️ **Tipo(s) de riesgo identificado(s)** (jurídico, financiero, técnico, reputacional, etc.)  
> - 🛡️ **Medidas de mitigación recomendadas**  
> - 📌 **Objeto del CONPES** (resumen en 2 líneas máximo)  
> - 🔗 **Enlace al documento oficial (PDF o página del DNP)**

**Resultado esperado:** Tabla estructurada en Excel o CSV lista para ser usada en Google Looker Studio.

---

## 💡 Observaciones

- Si el CONPES no tiene relación directa con riesgo contractual, debe ser descartado.
- El prompt puede adaptarse para lectura en PDF o documentos Word.

---

## 📈 Próximos Prompts a Documentar

- Prompt para clasificación automática de riesgos.
- Prompt para detectar medidas de mitigación por sector.

