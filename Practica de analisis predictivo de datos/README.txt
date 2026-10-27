Practica de Análisis Predictivo de Datos - Caso TecnoAndes

LIBRERIAS USADAS:
- from google.colab import files
- from IPython.display import Markdown, display
- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import seaborn as sns
- import os
- from sklearn.model_selection import train_test_split
- from sklearn.ensemble import RandomForestClassifier, RandomForestRegressor
- from sklearn.metrics import classification_report, confusion_matrix, accuracy_score, ConfusionMatrixDisplay, mean_squared_error, r2_score
- from sklearn.model_selection import cross_val_score

COMO EJECUTAR EL CODIGO:

- Descargar los 3 archivos que se encuentran en este repositorio (ventas.csv, clientes.json y productos.xlsx) e identificar su ubicación en la ruta local.
- Se abre el notebook y oprimir el botón "Abrir en Colab".
- Se guarda una copia propia con Archivo → Guardar una copia en Drive.
- Las celdas se ejecutan en orden.
- La segunda celda de código te pedirá subir los 3 archivos al mismo tiempo, así que da clic en "Elegir archivos" y selecciona los 3.
- Continua con la ejecución de las celdas de código.
- Revisar los resultados y gráficas para interpretar los hallazgos

TRABAJO REALIZADO POR:
- DUVAN STEVEN GARCIA RAMOS
- LIBER ANDREY LEAL FORERO



