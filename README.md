# 🎙️ Audio Transcriber Pro 📝


LINK DEL SCRIPT: https://colab.research.google.com/drive/1G0ie1BDT7_h0jJvdYpiTwPnNNAfsJc-l?usp=sharing

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python Version">
  <img src="https://img.shields.io/badge/Whisper-v1.0+-green.svg?style=for-the-badge&logo=openai&logoColor=white" alt="Whisper Model">
  <img src="https://img.shields.io/badge/SRT-Format-yellow.svg?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAAXNSR0IArs4c6QAAAERlWElmTU0AKgAAAAgAAYdpAAQAAAABAAAAGgAAAAAAA6ABAAMAAAABAAEAAKACAAQAAAABAAAAHqADAAQAAAABAAAAAgAAAACb84vLAAAAkklEQVQ4jWM4c+bMfwYgqM3bt1+M0QjU/0Wj8c1QjY6hG1F8w4jGZ5oQ+Y4xG7/8g0z1iG8s/9vH//n2m6l8g+P/8//s2c1f8z/9/d//9//07+4//+vj//6f//37//3n//9t//8H//+V+f/s//+f//1//5s//+V//9/5/v//+f///+b/z0//8P/39//8//+f/+d//9//9////9g0z9qgAAAABJRU5ErkJggg==" alt="SRT Subtitles">
</p>

<p align="center">
  Transforma tus archivos de audio en subtítulos con precisión y facilidad.
</p>

---

# 🚀 Descripción del Proyecto

**Audio Transcriber Pro** es una herramienta avanzada de Python que utiliza el potente modelo de reconocimiento de voz **Whisper** de OpenAI para transcribir archivos de audio a subtítulos en formato SRT. Esta versión mejorada incluye capacidades de transcripción multiidioma y características profesionales que la convierten en la solución completa para generar subtítulos de alta calidad para tus videos, podcasts y contenidos multimedia.

## ✨ Características Principales

### 🎯 **Funcionalidades Básicas**
- **Transcripción Precisa:** Utiliza modelos Whisper de última generación para transcripción de alta calidad
- **Salida SRT Profesional:** Genera archivos de subtítulos en formato SRT estándar compatible con todos los reproductores
- **Timestamps de Precisión:** Marcas de tiempo detalladas a nivel de palabra para sincronización perfecta
- **Interfaz Intuitiva:** Diseño simple y fácil de usar en Google Colab con selección de archivos drag-and-drop
- **Optimizado para Colab:** Funcionamiento sin problemas en entornos de Google Colab con instalación automática

### 🚀 **Características Avanzadas (NUEVAS)**

#### 🌍 **Transcripción Multiidioma**
- **Transcripción Dual:** Genera automáticamente subtítulos en **español** e **inglés** simultáneamente
- **Archivos Separados:** Crea archivos independientes (`archivo_español.srt` y `archivo_english.srt`)
- **Detección Automática:** Optimización inteligente para cada idioma objetivo

#### ⚡ **Rendimiento y Monitoreo**
- **Soporte GPU Completo:** Aprovecha al máximo la aceleración CUDA para transcripción ultra-rápida
- **Métricas en Tiempo Real:** Muestra velocidad de procesamiento (ej: "5.2x más rápido que tiempo real")
- **Indicadores de Progreso:** Seguimiento detallado del estado de transcripción con estimaciones precisas
- **Análisis de Rendimiento:** Estadísticas completas de tiempo y eficiencia

#### 🔧 **Flexibilidad y Control**
- **Selección de Modelos:** Elige entre 5 modelos Whisper (tiny, base, small, medium, large)
- **Balance Velocidad/Precisión:** Configuración adaptable según tus necesidades específicas
- **Múltiples Formatos:** Soporte extendido para MP3, WAV, M4A, FLAC, OGG
- **Gestión Inteligente:** Procesamiento automático de archivos temporales y limpieza

#### 📊 **Análisis y Reportes**
- **Resumen Detallado:** Información completa de cada transcripción (segmentos, duración, preview)
- **Estadísticas de Calidad:** Métricas de precisión y confianza por idioma
- **Descarga Automática:** Los archivos SRT se descargan automáticamente al completarse
- **Verificación de Resultados:** Validación automática de la calidad de transcripción

### 🛠️ **Características Técnicas**

#### 🧠 **Inteligencia Artificial**
- **Modelos Whisper Actualizados:** Acceso a los últimos modelos de OpenAI
- **Procesamiento Adaptativo:** Optimización automática según el hardware disponible
- **Timestamps Inteligentes:** Segmentación automática cada 5-6 palabras o al final de oraciones
- **Detección de Contexto:** Reconocimiento mejorado de pausas naturales y puntuación

#### 🔒 **Confiabilidad y Seguridad**
- **Gestión de Errores:** Manejo robusto de excepciones y recuperación automática
- **Verificación de Dependencias:** Instalación y validación automática de todos los componentes
- **Limpieza Automática:** Eliminación segura de archivos temporales
- **Compatibilidad Garantizada:** Tested en diferentes configuraciones de Google Colab

### 📈 **Mejoras de Rendimiento**

| Característica | Versión Anterior | **Nueva Versión** |
|---|---|---|
| Idiomas | Solo español | **Español + Inglés simultáneo** |
| Modelos | Modelo fijo | **5 modelos seleccionables** |
| Métricas | Básicas | **Análisis completo de rendimiento** |
| Formatos | MP3 únicamente | **5 formatos de audio** |
| Descarga | Manual | **Descarga automática** |
| GPU | Soporte básico | **Optimización completa CUDA** |
| Informes | Mínimos | **Resúmenes detallados** |

### 🎯 **Casos de Uso Ideales**
- **Creadores de Contenido:** Subtítulos profesionales para YouTube, TikTok, Instagram
- **Educadores:** Transcripción de clases y conferencias en múltiples idiomas
- **Empresas:** Subtitulado de webinars, presentaciones y material corporativo
- **Podcasters:** Generación de transcripciones completas para accesibilidad
- **Investigadores:** Transcripción de entrevistas y material de investigación
- **Traductores:** Base para traducción y localización de contenido

### 💡 **Ventajas Competitivas**
- **Sin Límites de Duración:** Procesa archivos de audio de cualquier longitud
- **Calidad Profesional:** Precisión comparable a servicios de transcripción pagos
- **Completamente Gratuito:** Utiliza recursos gratuitos de Google Colab
- **Personalizable:** Configuración adaptable a necesidades específicas
- **Código Abierto:** Totalmente modificable y extensible

---

## 🚀 **¿Qué Hace Único a Audio Transcriber Pro?**

Esta herramienta no es solo un transcriptor más. Es una **solución completa de subtitulado multiidioma** que combina la potencia de Whisper con una interfaz intuitiva y características profesionales. La capacidad de generar simultáneamente subtítulos en español e inglés, junto con el análisis detallado de rendimiento y la flexibilidad de configuración, la convierten en la herramienta definitiva para cualquier proyecto que requiera transcripción de alta calidad.

**¡Transforma tus archivos de audio en subtítulos profesionales en minutos, no en horas!**

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




