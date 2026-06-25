# Predicción temprana de ansiedad usando datos fisiológicos multimodales
---

## Introducción

El estrés crónico representa uno de los principales factores de riesgo para enfermedades cardiovasculares, depresión y deterioro cognitivo. Su detección temprana en base a datos de la vida diaria es un desafío relevante tanto para la medicina como para el desarrollo de sistemas de salud digital.

En el proyecto utiliza el dataset **SWEET** (*Large-scale wearable data reveal digital phenotypes for daily-life stress detection*), un estudio a gran escala con 1002 sujetos monitoreados durante 5 días consecutivos mediante dispositivos wearables. A partir de una selección de 55 usuarios, se construyó un pipeline de Machine Learning que comprende análisis exploratorio de datos, extracción de características mediante imágenes generadas con TINTOlib, y comparación estadística de dos modelos ML (Random Forest y SVM).

El objetivo es conocer si con estos modelos se pueden crear estrategias para distinguir tres niveles de estrés auto-reportado: **S1** (sin estrés), **S2** (estrés leve) y **S3** (estrés alto), utilizando exclusivamente señales fisiológicas no invasivas (ECG, ACC, TEMP).

Anderson Santiago Alvarez G.
