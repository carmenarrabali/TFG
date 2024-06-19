# Aprendizaje automático explicable a la detección y predicción del cáncer de pulmón
## Tabla de Contenidos
- [Introducción](#introducción)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)
- [Contacto](#contacto)


## Introducción
Debido a la alta mortalidad que está causando una enfermedad tan grave como es el cáncer, se propone hacer uso de modelos explicables de Machine Learning en el pronóstico y la predicción del cáncer, que no solo mejorará la confiabilidad de los resultados, sino que también ayudará a profesionales de la salud a estar más informados sobre el tratamiento clínico de los pacientes. También les ayudará a tomar mejores decisiones.

## Requisitos
Lista de las librerías y herramientas necesarias para ejecutar el código:
- Python 3.x
- Librerías de Python:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyter (opcional, si usas notebooks)

## Instalación

Instrucciones paso a paso sobre cómo instalar las dependencias y configurar el entorno.

1. Clona el repositorio:
    ```sh
    git clone https://github.com/carmenarrabali/TFG.git
    cd TFG
    ```

2. Crea un entorno virtual (opcional, pero recomendado):
    ```sh
    python3 -m venv env
    source env/bin/activate  # En Windows usa `env\Scripts\activate`
    ```

3. Instala las dependencias:
    ```sh
    pip install -r requirements.txt
    ```

## Uso
1. Lanza Jupyter notebook:
    ```sh
    jupyter notebook
    ```
2. Abre `TFG_arrabali.ipynb` y ejecuta las celdas.

## Estructura del Proyecto

Descripción de la estructura del proyecto y una breve descripción de cada archivo o directorio.

```plaintext
TFG/
├── data/                # Datos del proyecto
├── notebooks/           # Notebooks de Jupyter
├── .gitignore           # Archivos y directorios a ignorar por git
├── requirements.txt     # Lista de dependencias
└── README.md            # Este archivo
