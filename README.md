# Clasificador de artículos de Wikipedia

Pasos para ejecutar el análisis de texto:

## Dataset

1. Descomprimir los .zip del folder `dataset`

## Environment

2. Ejecutar `python -m venv text-venv` para crear un ambiente virtual de Python

3. Ejecutar `source text-venv/bin/activate` para cargar el ambiente virtual

4. Ejecutar `pip install -r requirements.txt` para instalar las dependencias en el ambiente virtual

5. Ejecutar `python -m spacy download en_core_web_sm` para instalar el core del idioma inglés

## Kernel

6. Crear un kernel en base al entorno virtual ejecutando `python -m ipykernel install --user --name=text-kernel`

## Ejecutar notebook

7. Ejecutar `python -m notebook` para abrir el editor de notebooks en el navegador

9. Abrir el notebook llamado `wikipedia_article_analizer.ipynb`

10. Seleccionar el kernel creado en Kernel -> Change Kernel -> text-kernel


Listo! Ya se encuentra listo para ejecutar el analizador de texto.

## Stopwords custom

Las siguientes palabras son excluídas del análisis, por ser parte del cuerpo HTML de los artículos:

```
STOPWORDS = ['style', 'text', 'align', 'center', 'right', 'background', 
             'leave', 'fff', 'width', 'px', 'text', 'vertical', 'wikitable',
             'category', 'also', 'know', 'may', 'reference', 'read', 'call', 'find'
             'include', 'file', 'date', 'last', 'note', 'image', 'left', 'bgcolor', 'color',
             'font', 'rowspan', 'solid', 'value', 'access']
```

## Resultados

### Con 5 tópicos:

Topic 0:
- Biografias

Topic 1:
- Deportes / Deportistas

Topic 2:
- Animales / Especies / Naturaleza

Topic 3:
- Directores / Peliculas / Musica

Topic 4:
- Políticos 
