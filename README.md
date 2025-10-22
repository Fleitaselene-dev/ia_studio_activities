# Gestión de Hospital con Implementación de IA

Este proyecto está diseñado para un hospital que quiere implementar un **asistente inteligente** que ayude al personal médico a responder preguntas de pacientes y analizar imágenes médicas.

El sistema utiliza modelos de IA de **Google Gemini** para generar contenido explicativo, responder consultas médicas y analizar imágenes radiográficas.

---

## Características Principales

1. **Respuestas médicas explicativas**
   - El asistente puede explicar conceptos médicos de forma sencilla, como hipertensión o diabetes.
   - Puede responder preguntas largas y mostrar las respuestas en tiempo real usando `generate_content_stream`.

2. **Análisis de imágenes médicas**
   - Permite subir radiografías o tomografías.
   - La IA describe hallazgos y posibles indicios clínicos.

---

## Requisitos

- Python 3.10 o superior
- Jupyter Notebook
- Biblioteca `google-genai`
- Biblioteca `python-dotenv`
- Acceso a una **API Key** de Google Gemini

---

## Instalación

1. Clonar el repositorio
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_REPOSITORIO>
2. Crear un entorno virtual con uv (Recomendado)
    ```bash
    uv venv env
3.Activar el entorno virtual
  - Windows:
     ```bash
     .\env\Scripts\activate
  - Linux/macOS
     ```bash
     source env/bin/activate
4.Instalar dependencias
    ```bash
    pip install google-genai python-dotenv
     ```
5.Configurar la API Key:
  - Crear un archivo .env en la raíz del proyecto con tu API Key:
     ```bash
     API_KEY=TU_API_KEY_DE_GOOGLE_GEMINI
6. Ejecuta las celdas  de tu Jupyter Notebook


