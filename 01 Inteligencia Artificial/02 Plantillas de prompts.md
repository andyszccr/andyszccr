# 📝 Plantilla de Prompts: NotebookLM & Gemini Chat

Esta plantilla está diseñada para que la audiencia pueda copiarla, adaptarla y utilizarla directamente tanto en **NotebookLM** (para trabajar con sus fuentes privadas) como en el **Chat de Gemini AI** (cuando necesiten ampliar con enlaces oficiales y referencias externas).

---

## 🧩 La Fórmula del Prompt Maestro (4 Pilares)

Antes de enviar cualquier consulta a la IA, asegúrate de estructurarla con esta base para evitar respuestas genéricas:

1. **Rol:** Quién es la IA (experiencia y especialización).
2. **Objetivo:** Qué tarea exacta va a resolver.
3. **Formato y Enlaces:** Cómo debe entregar la respuesta y si requiere fuentes oficiales externas.
4. **Contexto:** Las fuentes seleccionadas (en NotebookLM) o el fragmento de código pegado (en Gemini Chat).

---

## 🚀 Plantilla 1: Para usar dentro de NotebookLM (Auditoría Local)

*Ideal para cuando subes tu código heredado o documentación y quieres respuestas basadas estrictamente en tus archivos sin alucinaciones.*

```text
[ROL]
Actúa como un Arquitecto de Software Senior y experto en refactorización de código heredado.

[OBJETIVO]
Analiza la arquitectura y los fragmentos de código del backend heredado cargados en las fuentes de esta libreta para detectar posibles cuellos de botella de rendimiento o riesgos de seguridad en el flujo de autenticación y acceso a datos.

[FORMATO Y RESTRICCIONES]
- Presenta la respuesta en una lista ordenada por severidad (Alta, Media, Baja).
- Indica claramente el archivo o módulo afectado según las fuentes.
- Básate exclusivamente en los documentos de esta libreta. No inventes métodos ni librerías que no aparezcan en los archivos cargados.
```

---

## 🌐 Plantilla 2: Para usar en el Chat de Gemini AI (Búsqueda y Enlaces Externos)

*Ideal para cuando ya identificaste un hallazgo en NotebookLM y quieres que Gemini te proporcione la solución técnica moderna junto con los enlaces a la documentación oficial más reciente.*

```text
[ROL]
Actúa como un Ingeniero de Software Principal y especialista en optimización de rendimiento de sistemas.

[OBJETIVO]
Tomando como base este fragmento de código del sistema heredado:
[Pega aquí tu fragmento de código o consulta]
Explícame cómo refactorizarlo para evitar bloqueos por concurrencia y mejorar la eficiencia.

[FORMATO Y ENLACES OFICIALES]
1. Explica la solución técnica paso a paso de forma clara y limpia.
2. Incluye obligatoriamente al final un apartado titulado "📚 Referencias y Documentación Oficial" con los enlaces web oficiales y verificados que respalden la solución (ej. documentación oficial de la plataforma, Microsoft Learn, repositorios oficiales).
- Restricción: No inventes URLs. Utiliza únicamente enlaces reales y confiables de la documentación oficial.
```

---

## 👤 Autor y Contacto

**Andrey Sánchez Zúñiga**  
*CEO & Founder at Inovatry Solutions | Systems Engineering*  
🔗 [Portfolio](https://andreysz.netlify.app/) | [GitHub Repository](https://github.com/andyszccr/andyszccr)