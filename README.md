# Análisis y Predicción de Precios de Laptops

Proyecto final del curso de **Ciencia de Datos**: aplicamos el flujo completo de un proyecto de datos —exploración, limpieza, estadística descriptiva, visualización y un modelo predictivo simple— sobre un dataset de especificaciones y precios de laptops.

## 👥 Integrantes

| Nombre | GitHub |
|---|---|
| Juan Bello | [@JEstebanBello](https://github.com/JEstebanBello) |
| Martin | https://github.com/Zamxsu |
| Jenncy | jenncynayely2903@gmail.com |

## 🎯 ¿Por qué este dataset?

Como estudiantes de **Ingeniería de Sistemas**, el hardware es parte de nuestro día a día. Entender qué características determinan el precio de un equipo (RAM, almacenamiento, procesador, marca) es útil, por ejemplo, para que un área de TI evalúe cotizaciones y decida qué equipos comprar con un presupuesto dado.

## 🗂️ Estructura del repositorio

```
analisis-precios-laptops/
├── README.md          ← contexto, integrantes y enlace al video
├── datos/             ← dataset utilizado
├── notebook/          ← cuaderno de Google Colab (.ipynb)
├── presentacion/      ← presentación de apoyo (PDF o PPTX)
└── video/             ← enlace al video
```

## 🧭 Etapas del proyecto

1. **Fundamentos y herramientas:** selección, exploración y limpieza del dataset.
2. **Estadística descriptiva:** tendencia central, dispersión, comparación de variables y outliers.
3. **Modelado y storytelling:** visualizaciones, regresión lineal y aplicación profesional.

## 💻 Notebook

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JEstebanBello/analisis-precios-laptops/blob/main/notebook/analisis_precios_laptops.ipynb)

[`notebook/analisis_precios_laptops.ipynb`](notebook/analisis_precios_laptops.ipynb) contiene las tres etapas. En Colab basta con *Entorno de ejecución → Ejecutar todas*: el dataset se carga directamente desde este repositorio.

## 📌 Hallazgos principales

- El precio típico (mediana) de una laptop es **≈ 989 €**, con mucha dispersión: de 174 € a 6.099 €.
- **RAM, SSD y procesador** son lo que más encarece un equipo; el disco duro (HDD) y el tamaño de pantalla casi no influyen.
- Una **regresión lineal** con 4 variables (RAM, SSD, peso y densidad de píxeles) explica el **70 %** de la variación del precio, con un error promedio de **≈ 298 €**.

## 📑 Presentación

[`presentacion/presentacion_precios_laptops.pdf`](presentacion/presentacion_precios_laptops.pdf) (también en `.pptx`, con el guion del video en las notas del orador).

## 🎥 Video

_Pendiente._

## 📊 Fuente de los datos

- **Dataset:** [Laptop Price – Kaggle](https://www.kaggle.com/datasets/muhammetvarl/laptop-price) (Muhammet Varlı).
- **Archivos:** `datos/laptop_price.csv` (original, 1.303 filas), `datos/laptops_limpio.csv` (depurado, 1.275 filas) y `datos/laptops.xlsx` (versión en Excel con resumen estadístico y diccionario de columnas).
- **Limitaciones:** los precios son de una tienda en línea de ~2017-2018 y están en **euros**, así que no reflejan el mercado colombiano actual.
