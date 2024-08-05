# MetaRadar

MetaRadar es una herramienta para extraer metadatos de diversos tipos de archivos, incluyendo documentos, imágenes, archivos de audio y vídeo. Proporciona una interfaz gráfica intuitiva para seleccionar directorios, iniciar análisis y generar informes detallados en HTML.

## Características

- Extrae metadatos de archivos PDF, imágenes (PNG, JPEG, TIFF, BMP), documentos DOCX, archivos de audio (MP3, FLAC, WAV, AAC) y archivos de vídeo (MP4, MKV, AVI, MOV).
- Interfaz gráfica de usuario (GUI) basada en `tkinter`.
- Opciones de configuración para seleccionar los tipos de archivos a analizar.
- Barra de progreso y mensajes de estado en tiempo real.
- Generación de informes HTML bien diseñados y organizados.

## Requisitos

- Python 3.6 o superior
- Bibliotecas de Python:
  - `PyPDF2`
  - `Pillow`
  - `python-docx`
  - `mutagen`
  - `pymediainfo`
  - `tkinter`
  - `jinja2`

## Instalación

1. Clona el repositorio:
   ```sh
   git clone https://github.com/omrpps/MetaReglan.git
   cd MetaReglan
