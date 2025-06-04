
# 🗺️ Clustering K-Means en Datos de Vivienda de California

Este proyecto demuestra cómo aplicar **aprendizaje automático no supervisado** utilizando el algoritmo de **K-Means** en datos reales de viviendas. El objetivo es explorar patrones regionales basados en características geográficas y económicas.

## 🔍 Descripción General

Usando un conjunto de datos simplificado de viviendas en California, realizamos:

- Carga y preprocesamiento de datos con **pandas**
- Aplicación del algoritmo **K-Means** para agrupar regiones similares
- Visualización de los clústeres en un mapa usando **Plotly**
- (Opcional) Exploración del uso de **RandomForestClassifier** para tareas de clasificación

## 📁 Conjunto de Datos

El conjunto de datos está disponible públicamente y se carga directamente desde:

```
https://raw.githubusercontent.com/4GeeksAcademy/k-means-project-tutorial/main/housing.csv
```

Solo se utilizan las siguientes características para el clustering:
- `Latitude` (Latitud)
- `Longitude` (Longitud)
- `MedInc` (Ingreso Medio)

## ⚙️ Tecnologías Utilizadas

- `pandas`, `numpy` – Manipulación de datos
- `scikit-learn` – Modelos de clustering y aprendizaje automático
- `plotly.express` – Visualización interactiva de datos
- `Jupyter Notebook` – Análisis exploratorio y flujo de trabajo

## 🚀 Cómo Ejecutar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/jilemp/k-means-project-housing.git
   ```
2. Navega a la carpeta del proyecto:
   ```bash
   cd tu-repo
   ```
3. Abre el Jupyter Notebook:
   ```bash
   jupyter notebook "explore.ipynb"
   ```
4. Ejecuta cada celda en orden.

## 📊 Resultados

- El algoritmo K-Means segmenta California en **6 clústeres distintos** basados en ingresos y geografía.
- Los gráficos interactivos muestran cómo se distribuyen los clústeres espacialmente.

## 🧠 Trabajo Futuro

- Evaluar el rendimiento del clustering usando métricas como el Silhouette Score
- Añadir clasificación usando `RandomForestClassifier`
- Mejorar la selección de características (por ejemplo, incluir población o antigüedad de la vivienda)

## 📜 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

---

> Hecho usando Jupyter & scikit-learn
