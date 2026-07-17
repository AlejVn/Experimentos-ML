# Bank Marketing Dataset Analysis

---

## Español

Este proyecto contiene un análisis exploratorio de datos (EDA) y la implementación de modelos de Machine Learning utilizando el dataset de Bank Marketing. El objetivo principal es predecir si un cliente se suscribirá a un depósito a plazo (variable objetivo `y`).

### Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- **`eda_bank_marketing.ipynb`**: Notebook de Jupyter que contiene el Análisis Exploratorio de Datos (EDA). Incluye visualizaciones, análisis de distribuciones y correlaciones para entender mejor las características de los clientes y la campaña de marketing.
- **`modelado_bank_marketing.ipynb`**: Notebook de Jupyter enfocado en el preprocesamiento de datos, entrenamiento y evaluación de diferentes modelos de Machine Learning (por ejemplo, Regresión Logística, Árboles de Decisión, Random Forest, etc.) para predecir la suscripción.
- **`bank-full.csv`**: El dataset original utilizado para el análisis y modelado.
- **`data_procesada/`**: Directorio destinado a almacenar los conjuntos de datos limpios y preprocesados generados durante las etapas de EDA y modelado.
- **`resultados_modelos/`**: Directorio donde se guardan las métricas, gráficas de evaluación (como curvas ROC) y los modelos entrenados exportados.
- **`venv/`**: Entorno virtual de Python que contiene las dependencias necesarias para ejecutar el proyecto.

### Requisitos y Configuración

Para ejecutar los notebooks localmente, se recomienda utilizar el entorno virtual proporcionado o crear uno nuevo con las dependencias necesarias (como `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn` y `jupyter`).

#### Usando el entorno virtual existente

1. Activa el entorno virtual:
   - En Mac/Linux:
     ```bash
     source venv/bin/activate
     ```
   - En Windows:
     ```cmd
     .\venv\Scripts\activate
     ```
2. Inicia Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Abre los archivos `.ipynb` en tu navegador y ejecuta las celdas secuencialmente.

### Autores
Alejandro Villamil Niño
Samuel Rodríguez Murillo
Tomas A. Barbosa Rey

---

## English

This project contains an Exploratory Data Analysis (EDA) and Machine Learning models implementation using the Bank Marketing dataset. The main goal is to predict if a client will subscribe to a term deposit (target variable `y`).

### Project Structure

The project is organized as follows:

- **`eda_bank_marketing.ipynb`**: Jupyter Notebook containing the Exploratory Data Analysis (EDA). It includes visualizations, distribution analysis, and correlations to better understand customer features and the marketing campaign.
- **`modelado_bank_marketing.ipynb`**: Jupyter Notebook focused on data preprocessing, training, and evaluation of different Machine Learning models (e.g., Logistic Regression, Decision Trees, Random Forest, etc.) to predict the subscription.
- **`bank-full.csv`**: The original dataset used for analysis and modeling.
- **`data_procesada/`**: Directory intended to store clean and preprocessed datasets generated during the EDA and modeling stages.
- **`resultados_modelos/`**: Directory where metrics, evaluation plots (like ROC curves), and exported trained models are saved.
- **`venv/`**: Python virtual environment containing the necessary dependencies to run the project.

### Requirements and Setup

To run the notebooks locally, it is recommended to use the provided virtual environment or create a new one with the necessary dependencies (such as `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, and `jupyter`).

#### Using the existing virtual environment

1. Activate the virtual environment:
   - On Mac/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```cmd
     .\venv\Scripts\activate
     ```
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the `.ipynb` files in your browser and run the cells sequentially.

### Authors
Alejandro Villamil Niño
Samuel Rodríguez Murillo
Tomas A. Barbosa Rey
