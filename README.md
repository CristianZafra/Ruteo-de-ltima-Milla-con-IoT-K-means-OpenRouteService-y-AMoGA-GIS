# 📦 Ruteo de Ultima Milla con IoT, K-means, OpenRouteService y AMoGA-GIS

Este repositorio contiene un enfoque práctico para resolver el problema de ruta de última milla integrando sensores IoT simulados, agrupando geoespacial, algoritmos evolutivos y herramientas de georreferencia. La solución aplica el aprendizaje automático y la optimización para mejorar la eficiencia logística.

---

## 🎯 Objetivo

Optimizar las rutas de entrega urbana media:

- Agrupamiento de entregas por cerca geográfica.
- Comparación entre rutas tradicionales y rutas óptimas generadas por un algoritmo genético multiobjetivo (AMoGA-GIS).
- Visualización y análisis de resultados en términos de distancia y duración.

---

## 📁 Estructura del Proyecto

---

## ?? ¦ Datos utilizados

### 1. [`artículos_peso_volumen_ubicacion_clustering.csv`](https://github.com/CristianZafra/Ruteo-de-ltima-Milla-con-IoT-K-means-OpenRouteService-y-AMoGA-GIS/blob/main/items_peso_volumen_ubicacion_clustering.csv)

Archivo con datos simulados de entregas que incluyen:

- Coordenadas geográficas de los puntos de entrega
- Peso y volumen de cada tema
- Datos útiles para aplicar técnicas de agrupamiento 

### 2. [Conjunto de datos de comercio eléctrico brasileño de Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Descargado automático medio `kagglehub` código con el señor:

```pitón
importar kagglehub
ruta = kagglehub.dataset_download("olistbr/brasilian-ecommerce")

