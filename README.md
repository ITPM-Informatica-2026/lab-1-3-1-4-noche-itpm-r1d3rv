[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23268576&assignment_repo_type=AssignmentRepo)
# 🚀 Laboratorio DPW-207: Formulación y Utilidades Front-End

Este repositorio contiene la base para el desarrollo de la **Sección 1.3 (Formularios)** y **1.4 (Utilidades y extras)** de la asignatura Diseño y Programación Web II.

## 🎯 Objetivo
Construir una interfaz de captura de datos profesional, aplicando validaciones nativas de HTML5 y un diseño basado en clases de utilidad del Framework, manteniendo fidelidad con el prototipo de Figma.

---

## 🛠️ Instrucciones del Laboratorio

### 1. D1: Descripción (Diseño en Figma)
Antes de modificar el código, debes completar en tu archivo de Figma:
* **Componente Maestro:** Crear un Input con variantes para los estados: `Default`, `Focused`, `Invalid` y `Disabled`.
* **Documentación:** Pega el link de tu prototipo de Figma al final de este README.

### 2. D2: Delegación (Implementación en index.html)
Utilizando el archivo `index.html` provisto, deberás:
* Añadir al menos **3 campos adicionales** (ejemplo: Fecha de nacimiento, Dirección, Género).
* Configurar los atributos `name` e `id` de forma semántica.
* Implementar el uso de `input-group` para añadir iconos a los campos (Sección 1.3).

### 3. D3: Discernimiento (Validación)
El formulario debe ser capaz de filtrar datos erróneos antes de cualquier proceso posterior:
* **Emails:** Solo formato institucional.
* **Teléfonos:** Solo números válidos en Bolivia (8 dígitos, inicio 6 o 7).
* **Requeridos:** Todos los campos críticos deben tener el atributo `required`.

### 4. D4: Diligencia (Utilidades 1.4)
Queda prohibido el uso de CSS personalizado dentro de etiquetas `<style>`. Debes usar las **Utilidades del Framework** para:
* **Espaciado:** Gestionar márgenes y rellenos (`mb-*`, `p-*`).
* **Layout:** Hacer que el formulario sea responsivo (Sección 1.4).
* **Feedback:** Mostrar mensajes de error claros con `invalid-feedback`.

---

## 📝 Entregables
1.  **Código Fuente:** Subido a este repositorio en la rama `main`.
2.  **Figma Link:*ewn el classroom de la asignatura*
3.  **Captura de Validación:** Una imagen en la carpeta `docs/` donde se vea el formulario rechazando un dato incorrecto.

---
## 🤖 Uso de GitHub Copilot (Opcional pero Sugerido)
Como beneficiarios del GitHub Student Pack, pueden usar Copilot bajo las siguientes reglas:
1. **Validación Humana:** Todo código generado por IA debe ser explicado por el alumno si el docente lo solicita (D3).
2. **Prompts Semánticos:** Deben dejar el comentario (prompt) en el código de qué le pidieron a la IA.
3. **Prioridad 1.4:** Si la IA sugiere CSS en línea, es obligación del alumno corregirlo usando **Utilidades del Framework (Bootstrap)**.
---

## 📑 Ficha Técnica (Uso Exclusivo Docente - FELIX)
* **Asignatura:** DPW-207 (Segundo Año).
* **Evaluación:** Se revisará la limpieza del código (Clean Code) y la correcta aplicación de utilidades de la Sección 1.4.
* **Control de Versiones:** Se exige un mínimo de 3 commits con mensajes descriptivos.
