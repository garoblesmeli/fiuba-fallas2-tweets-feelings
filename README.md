# fiuba-fallas2-tweets-feelings

Pasos para ejecutar el análisis de texto:

## Dataset

1. Descargar dataset desde https://www.kaggle.com/code/paoloripamonti/twitter-sentiment-analysis/data?select=training.1600000.processed.noemoticon.csv

2. Ubicar dataset en la raiz de deste proyecto

3. Renombrar dataset por 'tweets_feelings.csv'

## Environment

4. Ejecutar `python -m venv text-venv` para crear un ambiente virtual de Python

5. Ejecutar `source text-venv/bin/activate` para cargar el ambiente virtual

6. Ejecutar `pip install -r requirements.txt` para instalar las dependencias en el ambiente virtual

7. Ejecutar `python -m spacy download en_core_web_sm` para instalar el core del idioma inglés

## Kernel

8. Crear un kernel en base al entorno virtual ejecutando `python -m ipykernel install --user --name=text-kernel`

## Ejecutar notebook

10. Ejecutar `python -m notebook` para abrir el editor de notebooks en el navegador

11. Abrir el notebook llamado tweets_feelings_analyzer.ipynb

12. Seleccionar el kernel creado en Kernel -> Change Kernel -> text-kernel


Listo! Ya se encuentra listo para ejecutar el analizador de texto.
