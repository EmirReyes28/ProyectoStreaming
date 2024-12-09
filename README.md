# Proyecto de Análisis de Plataformas de Streaming

Este proyecto demuestra mis habilidades en el uso de herramientas de Google Cloud Platform (GCP) para analizar datos relacionados con plataformas de streaming digitales como Netflix, Hulu, Apple TV, HBO y Amazon Prime. El flujo de trabajo del proyecto abarca desde la limpieza y creación de datasets hasta la visualización de los datos en un dashboard interactivo.

## Herramientas Utilizadas

- **Google Colab**: Para la limpieza y creación de los datasets.
- **Google Cloud Storage**: Para almacenar los archivos CSV generados.
- **Google Cloud Data Fusion**: Para la integración y transformación de los datos.
- **BigQuery**: Para el análisis de grandes volúmenes de datos.
- **Looker Studio**: Para crear el dashboard interactivo.

## Flujo de Trabajo

1. **Recolección de Datos**: Se obtienen los datasets de Kaggle, relacionados con las plataformas de streaming.
2. **[Limpieza de Datos](https://github.com/EmirReyes28/ProyectoStreaming/blob/main/plataformas.ipynb)**: Los datos son procesados y limpiados utilizando Google Colab.
3. **Exportación a Google Cloud Storage**: Los datasets limpios se exportan en formato CSV a un bucket en Google Cloud Storage.
4. **Transformación y Carga a BigQuery**: Utilizando Google Cloud Data Fusion, los datos se transforman y cargan a BigQuery para su análisis.
5. **Creación de Dashboard Interactivo**: Finalmente, se utiliza Looker Studio para crear un dashboard interactivo que permite explorar los datos de manera visual.

![](https://github.com/EmirReyes28/Contenido/blob/main/py2GCP.png)

## [Dataset](https://github.com/EmirReyes28/ProyectoStreaming/tree/main/Datasets)

El dataset utilizado proviene de Kaggle y contiene información sobre diversas plataformas de streaming, incluyendo datos sobre sus catálogos, precios, géneros, calificaciones, entre otros.

## Requisitos

- Cuenta de Google Cloud Platform.
- Acceso a Google Colab.
- Conocimiento básico en SQL, Python y herramientas de GCP.
- Acceso al dataset desde Kaggle.
