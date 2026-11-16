# 📘 Manual Técnico Paso a Paso: Dominando NotebookLM y el Ecosistema Gemini

Bienvenido al manual oficial de apoyo para la charla **"Más allá del Chat: Cómo dominar NotebookLM y el Ecosistema Gemini para Ingeniería y Productividad"**. Este documento te guiará paso a paso para transformar la Inteligencia Artificial de un simple chat de consultas a un motor privado de gestión de conocimiento técnico y automatización de código.

---

## 🎯 1. Filosofía y Cambio de Paradigma: De la Web al RAG Privado

Durante años hemos dependido de modelos públicos que no conocen nuestros repositorios, nuestra arquitectura interna ni nuestros estándares de código. 

* **¿Qué es RAG (*Retrieval-Augmented Generation*)?** Es una técnica donde el modelo no responde basándose únicamente en su entrenamiento general, sino buscando estrictamente dentro de un conjunto de fuentes privadas y seleccionadas por ti.
* **¿Por qué NotebookLM?** Te permite crear una base de conocimiento segura, con cero alucinaciones fuera del contexto proporcionado y con la capacidad de generar citas exactas a tus documentos de diseño o código fuente.

---

## 🧩 2. La Anatomía del Prompt Perfecto

Para evitar respuestas genéricas al auditar o escribir código, toda consulta profesional a una IA debe estructurarse bajo esta fórmula de 4 pilares:

1. **El Rol (¿Quién es la IA?):** Define el nivel de experiencia y especialización (ej. *"Actúa como un Arquitecto de Software Senior y experto en microservicios..."*).
2. **El Objetivo (¿Qué tarea debe resolver?):** Sé directo sobre el entregable (ej. *"Analiza este módulo y detecta cuellos de botella de rendimiento..."*).
3. **El Formato y Restricciones (¿Cómo lo entrega?):** Especifica la estructura (ej. *"Devuélvelo en formato de tabla con columnas: Archivo, Riesgo [Alto/Medio/Bajo], Línea afectada y Propuesta de Refactorización"*).
4. **Las Fuentes (Contexto acotado):** Delimita de dónde debe obtener la información (en NotebookLM seleccionando los archivos específicos).

---

## 🛠️ 3. Paso a Paso: Configurando NotebookLM para Ingeniería

### Paso 1: Creación de la Libreta de Conocimiento
1. Ingresa a [NotebookLM](https://notebooklm.google.com/).
2. Haz clic en **Nueva Libreta** (*New Notebook*).
3. Asignale un nombre claro y profesional, por ejemplo: `DevFest-Arquitectura-Backend`.

### Paso 2: Ingesta de Fuentes Limpias
1. Sube la documentación técnica clave de tu proyecto. Se recomiendan:
   * Especificaciones de arquitectura en formato PDF.
   * Diagramas técnicos o esquemas de bases de datos.
   * Fragmentos limpios de código fuente o archivos de configuración (`.json`, `.yaml`, `.md`).
2. *Nota de ingeniería:* Asegúrate de remover credenciales, llaves de API o información altamente sensible antes de subir cualquier archivo a entornos de prueba.

### Paso 3: Consultas Estratégicas y Audio Overviews
* **Pregunta de auditoría sugerida:**
  > *"Actúa como un Arquitecto de Software Senior. Basándote en estas fuentes, ¿cuáles son los principales puntos de fallo en la capa de persistencia y cómo los refactorizarías?"*
* **Explota los *Audio Overviews*:** Utiliza esta funcionalidad para generar un podcast conversacional automatizado que resuma la arquitectura técnica, ideal para repasar conceptos clave camino al trabajo o con tu equipo de desarrollo.

---

## ⚡ 4. Escalando al Ecosistema Gemini (Google AI Studio)

Cuando necesitas ir más allá de la lectura de documentos estáticos y trabajar directamente con lógica de código avanzada, automatización o integración mediante APIs, utilizas **Google AI Studio**.

1. Ingresa a [Google AI Studio](https://aistudio.google.com/).
2. Crea un **Chat Prompt** o **Structured Prompt**.
3. **Configura las System Instructions:** Define el comportamiento permanente del modelo. *(Puedes usar el archivo de ejemplo ubicado en la carpeta `02-ai-studio-prompts/system-instruction.txt` de este repositorio).*
4. **Multimodalidad aplicada:** Sube capturas de pantalla de diagramas UML o arquitectura de red para que el modelo te ayude a traducirlos a código base o documentación técnica automatizada.

---

## 🚀 5. Plantillas de Prompts Listos para Usar

### 📌 Plantilla 1: Auditoría y Refactorización de Código
```text
Rol: Actúa como un Ingeniero de Software Senior especializado en optimización de rendimiento y buenas prácticas de código.
Objetivo: Analiza el fragmento de código adjunto en las fuentes y detecta posibles vulnerabilidades, código obsoleto o problemas de concurrencia.
Formato: Presenta los resultados en una lista ordenada por severidad (Alta, Media, Baja). Para cada hallazgo incluye:
1. Archivo o módulo afectado.
2. Descripción técnica del problema.
3. Propuesta de refactorización de código limpia y comentada.
Restricciones: No inventes métodos o librerías que no existan en las fuentes proporcionadas.
```

### 📌 Plantilla 2: Generación de Pruebas Unitarias
```text
Rol: Actúa como un especialista en Aseguramiento de Calidad (QA Engineer) y experto en TDD.
Objetivo: Genera un conjunto de pruebas unitarias robustas para la lógica de negocio descrita en la especificación técnica.
Formato: Código fuente listo para implementar utilizando el framework estándar del proyecto (ej. xUnit / Jest), cubriendo casos felices, casos borde y manejo de excepciones.
```

---

## 👤 Autor y Contacto
* **Andrey Sánchez Zúñiga**  
*CEO & Founder at Inovatry Solutions | Systems Engineering*  
🔗 [Portfolio](https://andreysz.netlify.app/) | [GitHub Repository](https://github.com/andyszccr/andyszccr)