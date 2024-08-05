# MetaReglan

MetaReglan es una herramienta para extraer metadatos de diversos tipos de archivos, incluyendo documentos, imágenes, archivos de audio y vídeo. Proporciona una interfaz gráfica intuitiva para seleccionar directorios, iniciar análisis y generar informes detallados en HTML.

## Características

- **Compatibilidad con múltiples tipos de archivos**:
  - Documentos: PDF, DOCX
  - Imágenes: PNG, JPEG, TIFF, BMP
  - Audio: MP3, FLAC, WAV, AAC
  - Vídeo: MP4, MKV, AVI, MOV
- **Interfaz gráfica de usuario (GUI)**:
  - Fácil selección de directorios para análisis
  - Barra de progreso en tiempo real
  - Opciones de configuración para seleccionar los tipos de archivos a analizar
- **Generación de informes**:
  - Informes HTML detallados y organizados
  - Inclusión de metadatos GPS (si están disponibles) para imágenes

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

1. **Clona el repositorio**:
   ```sh
   git clone https://github.com/omrpps/MetaReglan.git
   cd MetaReglan
2. **Crea un entorno virtual (opcional pero recomendado)**:
   ```sh
   python -m venv venv
   source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
3. **Instala las dependencias:**
   pip install -r requirements.txt

## Uso

1. **Ejecuta el script principal:**
   python main.py
2. **Uso de la interfac gráfica**
   Aparecerá una ventana de tkinter donde podrás seleccionar el directorio que deseas analizar.
   Configura las opciones de análisis desde el botón de configuración.
   Inicia el análisis y revisa el progreso en la barra de estado.
   Una vez completado el análisis, abre el informe HTML generado desde la misma interfaz.

## Licencia

   Este proyecto está licenciado bajo la Licencia MIT. Ver el archivo LICENSE para más detalles.

## Contacto
   Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto con nosotros a través de omrpps@gmail.com
 