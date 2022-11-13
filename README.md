# Analizador de estado de ánimo en Tweets

Pasos para ejecutar el análisis de texto:

## Dataset

1. Descomprimir el archivo de `tweets_feelings.csv.zip`

2. Renombrar dataset por 'tweets_feelings.csv'

## Environment

3. Ejecutar `python -m venv text-venv` para crear un ambiente virtual de Python

4. Ejecutar `source text-venv/bin/activate` para cargar el ambiente virtual

5. Ejecutar `pip install -r requirements.txt` para instalar las dependencias en el ambiente virtual

6. Ejecutar `python -m spacy download en_core_web_sm` para instalar el core del idioma inglés

## Kernel

7. Crear un kernel en base al entorno virtual ejecutando `python -m ipykernel install --user --name=text-kernel`

## Ejecutar notebook

8. Ejecutar `python -m notebook` para abrir el editor de notebooks en el navegador

9. Abrir el notebook llamado tweets_feelings_analyzer.ipynb

10. Seleccionar el kernel creado en Kernel -> Change Kernel -> text-kernel


Listo! Ya se encuentra listo para ejecutar el analizador de texto.
