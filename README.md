# 🎵 MP3BatchTagger & Optimizer 🐍

![Licencia](https://img.shields.io/github/license/GaelCanoDev/music-to-vbr?style=flat-square)
![Versión Python](https://img.shields.io/badge/python-3.8%2B-blue?style=flat-square&logo=python)
![FFmpeg](https://img.shields.io/badge/motor-FFmpeg-green?style=flat-square&logo=ffmpeg)

**MP3BatchTagger & Optimizer** es una mini-app de Python que automatiza la optimización integral de lotes de música local. Convierte tus archivos MP3 desordenados en archivos perfectos: comprimidos con la máxima calidad perceptual (VBR Clase 0), con su portada incrustada y, lo más importante, con letras sincronizadas integradas.

Este proyecto nació de una necesidad personal: tener música local de alta calidad, pero optimizada en tamaño y con metadatos completos (letras sincronizadas, portada) en reproductores compatibles, sin tener que usar múltiples herramientas o procesos manuales.

## ✨ Características Principales

* 🔄 **Procesamiento en Lote:** Escanea una carpeta completa y procesa todos los archivos MP3 automáticamente.
* 📉 **Optimización de Audio (VBR 0):** Reduce el tamaño del MP3 utilizando Variable Bit Rate (VBR) Clase 0 (máxima calidad perceptual de LAME) para un equilibrio perfecto entre peso y fidelidad. *Ideal para ahorrar espacio sin comprometer el sonido.*
* 📝 **Letras Sincronizadas:** Busca e incrusta automáticamente letras de canciones sincronizadas (si están disponibles, ej: en archivos `.lrc` o vía tags existentes). Esta es la característica diferencial que resuelve un dolor de cabeza común.
* 🖼️ **Incrustación de Portadas (Covers):** Detecta y añade una imagen de portada al archivo MP3 (ej: `cover.jpg` en la misma carpeta).
* 🛡️ **Preservación de Metadatos:** Mantiene intactos el resto de metadatos (Artista, Álbum, Año, etc.) del archivo original.
* 🚀 **Rápido y Eficiente:** Automatiza todo el flujo de trabajo en un solo comando.

## 🛠️ Requisitos e Instalación

### Pre-requisitos
Necesitas tener instalado Python 3.8+ y la herramienta de línea de comandos `ffmpeg` instalada y accesible desde tu PATH.

* **Instalar FFmpeg:** Asegúrate de que `ffmpeg` esté en tu PATH.
  * [Instrucciones oficiales](https://ffmpeg.org/download.html)
* **Instalar Dependencias de Python:** Clona el repositorio e instala las bibliotecas necesarias.

### Instalación

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/GaelCanoDev/music-to-vbr.git](https://github.com/GaelCanoDev/music-to-vbr.git)
   cd music-to-vbr

🤝 Contribuciones

Este proyecto nació como una herramienta personal, pero ¡las mejoras son bienvenidas! Si encuentras un error o tienes una idea (como integración con APIs de letras), siéntete libre de abrir un Issue o enviar un Pull Request.
📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
✍️ Autor

    GaelCanoDev - Desarrollador Principal - https://github.com/GaelCanoDev
