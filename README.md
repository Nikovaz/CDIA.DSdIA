# 🧠 Desarrollo de Sistemas de Inteligencia Artificial (DSIA)
### 🏛️ IFTS Nº 24 — Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![DeepNote](https://img.shields.io/badge/DeepNote-Cloud%20Data%20Science-2E55F2?style=for-the-badge)](https://deepnote.com/)

---

## 👤 Información del Estudiante & Cursada
* **Estudiante:** Nicolás Galarza
* **Carrera:** Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial
* **Institución:** Instituto de Formación Técnica Superior Nº 24 (IFTS 24, CABA)
* **Materia:** Desarrollo de Sistemas de Inteligencia Artificial (DSIA)
* **Docente:** Prof. Valeria Feito
* **Cuatrimestre:** 2º Cuatrimestre 2026

---

## 🎯 Objetivo del Repositorio
Este repositorio tiene como finalidad registrar de forma estructurada, versionada y documentada todas las actividades prácticas, talleres y avances correspondientes a la materia **Desarrollo de Sistemas de Inteligencia Artificial**, consolidando buenas prácticas en control de versiones mediante **Git y GitHub** aplicadas a la Ciencia de Datos.

---

## 📂 Estructura del Repositorio

```text
CDIA.DSdIA/
│
├── 📁 01_Introduccion_DeepNote/
│   └── 📓 01_Entorno_DeepNote_y_Fundamentos.ipynb    # Configuración del entorno DeepNote, kernel cloud y manejo de datos.
│
├── 📁 02_Python_Repaso/
│   └── 📓 02_Repaso_Python_Fundamentos.ipynb         # Tipos de datos, comprehensions, funciones tipadas, excepciones y POO.
│
├── 📁 03_Python_Librerias/
│   ├── 📓 03_Librerias_Ciencia_de_Datos_e_IA.ipynb   # Análisis con NumPy, Pandas, Matplotlib, Seaborn y Scikit-Learn.
│   └── 📁 data/
│       └── 📄 sample_dataset.csv                     # Dataset de muestra para pruebas de análisis.
│
├── 📁 04_Trabajo_Practico_Integrador_TPI/
│   └── 📄 README.md                                  # Espacio reservado para las etapas 1, 2, entrega final y defensa del TPI.
│
├── 📄 .gitignore                                     # Exclusión de temporales, checkpoints y entornos virtuales.
├── 📄 requirements.txt                               # Dependencias del proyecto.
└── 📄 README.md                                      # Documentación general del repositorio.
```

---

## 🚀 Contenido de las Unidades y Prácticas

### 1. [01_Introduccion_DeepNote](./01_Introduccion_DeepNote/)
- Reconocimiento de la interfaz colaborativa de DeepNote.
- Configuración de dependencias, variables de entorno y ejecución interactiva de bloques de código.
- Carga de datasets en formato `.csv` y visualización preliminar.

### 2. [02_Python_Repaso](./02_Python_Repaso/)
- Nivelación de sintaxis moderna de Python 3.
- Estructuras iterables avanzadas y transformaciones mediante comprehensions.
- Funciones modulares, type hints y manejo de errores con bloques `try-except`.
- Diseño de clases y arquitectura de objetos para preprocesamiento de datos.

### 3. [03_Python_Librerias](./03_Python_Librerias/)
- **NumPy:** Creación de arrays multidimensionales, vectorización y álgebra lineal.
- **Pandas:** Carga de DataFrames, filtrado, imputación de valores faltantes y agregaciones.
- **Matplotlib & Seaborn:** Gráficos de distribución (KDE/histogramas) y matriz de correlación (Heatmap).
- **Scikit-Learn:** Pipeline de regresión supervisada y evaluación mediante métricas estándar ($R^2$, $MAE$, $RMSE$).

### 4. [04_Trabajo_Practico_Integrador_TPI](./04_Trabajo_Practico_Integrador_TPI/)
- Espacio designado para el desarrollo del **TPI Grupal** con entregas parciales por etapas:
  1. *Entrega 1:* EDA individual consolidado ($\ge 2500$ filas, $\ge 9$ columnas).
  2. *Entrega 2:* EDA univariado/bivariado, formulación de 4 hipótesis y análisis gráfico.
  3. *Entrega Final:* Modelos predictivos (regresión/clasificación/agrupación), métricas y selección óptima.
  4. *Defensa:* Presentación ejecutiva en formato Data Storytelling.

---

## 💻 Instalación y Ejecución Local

Para clonar y reproducir este entorno en tu computadora local:

```bash
# 1. Clonar el repositorio
git clone https://github.com/Nikovaz/CDIA.DSdIA.git

# 2. Ingresar al directorio
cd CDIA.DSdIA

# 3. Crear y activar entorno virtual (opcional pero recomendado)
python -m venv .venv
source .venv/bin/activate   # En Windows: .venv\Scripts\activate

# 4. Instalar librerías requeridas
pip install -r requirements.txt

# 5. Iniciar Jupyter Lab / Notebook
jupyter lab
```

---
*Desarrollado por Nicolás Galarza para la Tecnicatura Superior en Ciencia de Datos e IA (IFTS 24).*
