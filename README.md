# BC5 — Spotify Analytics Assistant

Business Case 5 del programa MDA13 de la escuela de negocios ISDI.

Este repositorio es un ejercicio docente. Los datos son sintéticos y no corresponden a ningún usuario real de Spotify. La estructura del dataset está inspirada en el formato de exportación de datos de Spotify, pero ha sido generada específicamente para este caso.

Ante cualquier duda: mtaboada@isdi.education

## Puesta en marcha

1. Clona el repositorio o descarga los archivos
2. Crea un entorno virtual y actívalo
3. Instala dependencias: `pip install -r requirements.txt`
4. Copia `.streamlit/secrets.toml.example` como `.streamlit/secrets.toml` y rellena la API key y tu contraseña
5. Ejecuta: `streamlit run app.py`

## Archivos

| Archivo | Descripción |
|---|---|
| `app.py` | Esqueleto de la aplicación. Tu trabajo está aquí. |
| `streaming_history.json` | Dataset del caso (~15.000 registros) |
| `requirements.txt` | Dependencias fijadas. No modificar. |
| `.gitignore` | Excluye secrets del repositorio |
| `.streamlit/secrets.toml.example` | Plantilla para API key y contraseña. Copiar como `secrets.toml`. |
# 🎧 Spotify Analytics Assistant

Aplicación interactiva que analiza tus hábitos de escucha en Spotify usando inteligencia artificial.

## Funcionalidades

- Análisis de artistas más escuchados
- Uso de modo shuffle
- Evolución temporal (horas, días, meses)
- Comparaciones dinámicas (ej. verano vs invierno)
- Generación automática de visualizaciones con IA

## Tecnologías

- Python
- Streamlit
- Plotly
- OpenAI API
- Pandas

## Cómo usar

1. Introduce la contraseña de acceso
2. Haz preguntas sobre tus hábitos de escucha:
   - "Top 5 artistas"
   - "¿Uso más el shuffle?"
   - "¿A qué hora escucho más música?"
3. La app generará automáticamente visualizaciones

## Notas

- Los datos provienen de `streaming_history.json`
- No se incluyen claves API por seguridad

## Demo

(Se añadirá la URL una vez desplegada en Streamlit Cloud)

update
