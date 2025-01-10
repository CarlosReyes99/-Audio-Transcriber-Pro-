# 🎙️ Audio Transcriber Pro 📝

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python Version">
  <img src="https://img.shields.io/badge/Whisper-v1.0+-green.svg?style=for-the-badge&logo=openai&logoColor=white" alt="Whisper Model">
  <img src="https://img.shields.io/badge/SRT-Format-yellow.svg?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAERlWElmTU0AKgAAAAgAAYdpAAQAAAABAAAAGgAAAAAAA6ABAAMAAAABAAEAAKACAAQAAAABAAAAHqADAAQAAAABAAAAAgAAAACb84vLAAAAkklEQVQ4jWM4c+bMfwYgqM3bt1+M0QjU/0Wj8c1QjY6hG1F8w4jGZ5oQ+Y4xG7/8g0z1iG8s/9vH//n2m6l8g+P/8//s2c1f8z/9/d//9//07+4//+vj//6f//37//3n//9t//8H//+V+f/s//+f//1//5s//+V//9/5/v//+f///+b/z0//8P/39//8//+f/+d//9//9////9g0z9qgAAAABJRU5ErkJggg==" alt="SRT Subtitles">
</p>

<p align="center">
  Transforma tus archivos de audio en subtítulos con precisión y facilidad.
</p>

---

## 🚀 Descripción del Proyecto

**Audio Transcriber Pro** es una herramienta de Python que utiliza el potente modelo de reconocimiento de voz **Whisper** de OpenAI para transcribir archivos de audio (MP3) a subtítulos en formato SRT. Este proyecto te proporciona una manera rápida y eficiente de generar subtítulos para tus videos, podcasts y otros contenidos multimedia.

### ✨ Características Principales

-   **Transcripción Precisa:** Usa el modelo Whisper para una transcripción de alta calidad.
-   **Salida SRT:** Genera archivos de subtítulos en el formato SRT estándar.
-   **Tiempos a Nivel de Palabra:** Incluye marcas de tiempo detalladas a nivel de palabra para sincronización perfecta.
-   **Porcentaje de Avance:** Muestra el porcentaje de avance durante la transcripción con una estimación de tiempo restante.
-   **Fácil de Usar:** Interfaz sencilla para seleccionar archivos en Google Colab.
-   **Optimizado para Colab:** Diseñado para funcionar sin problemas en entornos de Google Colab.
-   **Soporte GPU:** Usa la GPU para una transcripción más rápida si está disponible.

---

## ⚙️ Cómo Usar

### 1. **Configuración en Google Colab**

   -   Abre un nuevo notebook de Google Colab.
   -   Copia y pega todo el código del script en una celda.
   -   Ejecuta la celda.

### 2. **Cargar el Archivo MP3**

   -   Aparecerá un botón "Choose Files" para seleccionar el archivo MP3.
   -   Selecciona el archivo de audio que deseas transcribir.

### 3. **Espera la Transcripción**

   -   La transcripción comenzará automáticamente.
   -   Verás el progreso con el porcentaje de avance y una estimación de tiempo restante.

### 4. **Descargar el Archivo SRT**

   -   Una vez finalizada la transcripción, el archivo SRT estará disponible en el mismo directorio de Colab.
   -   Descarga el archivo SRT desde el panel de archivos de Colab o directamente desde el código usando el método `files.download()`.

### 💻 Ejemplo de uso en Google Colab:

```python
# Código de ejemplo (incluir el script)
# ... [aquí el código de tu script] ...
