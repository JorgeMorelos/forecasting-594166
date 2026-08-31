# Proyecto de Modelos de Pronósticos

Este repositorio contiene un Jupyter Notebook enfocado en modelos de pronósticos y análisis de series de tiempo. El proyecto está diseñado para ayudar a los estudiantes a entender e implementar diversas técnicas de pronóstico.

## Descripción del Proyecto

El proyecto incluye la implementación y análisis de diversos modelos y técnicas de pronóstico, tales como:

- Análisis de Series de Tiempo
- Modelos de Pronóstico
- Análisis Predictivo
- Evaluación y Selección de Modelos
- Análisis Estadístico

## Estructura del Proyecto

- `Modelos de Pronósticos - Completo.ipynb`: Notebook principal con los modelos de pronóstico y análisis
- `requirements.txt`: Lista de paquetes Python requeridos para este proyecto

## Herramientas y Tecnologías

- Python 3.11
- Jupyter Notebook
- Librerías de Análisis de Datos:
  - Pandas
  - Plotly
  - Scikit-learn
  - Category Encoders
  - SciPy
  - NumPy

## Instrucciones de Instalación

### Opción 1: GitHub Codespaces (Recomendado)

Simplemente abre este repositorio en GitHub Codespaces y el entorno se configurará automáticamente.

### Opción 2: Instalación Local

1. Clona este repositorio:
   ```bash
   git clone https://github.com/jorgermzg15/forecasting-students.git
   cd forecasting-students
   ```

2. Crea un entorno virtual:
   ```bash
   # En macOS/Linux
   python -m venv .venv
   source .venv/bin/activate

   # En Windows
   python -m venv .venv
   .\venv\Scripts\activate
   ```

3. Instala los paquetes requeridos:
   ```bash
   pip install -r requirements.txt
   ```

4. Inicia Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Open `Modelos de Pronósticos - Completo.ipynb` in your browser and start learning!

## Troubleshooting

If you encounter any issues:

1. Make sure your virtual environment is activated (you should see `(.venv)` in your terminal)
2. Try upgrading pip before installing requirements:
   ```bash
   pip install --upgrade pip
   ```
3. If you have problems with any visualization, make sure Plotly is properly installed:
   ```bash
   pip install plotly --upgrade
   ```
4. If you encounter kernel issues in Jupyter:
   ```bash
   python -m ipykernel install --user
   ```

## For Students

This repository is designed to be a learning resource for forecasting and time series analysis. Each section in the notebook is structured to build upon previous concepts. Make sure to:

1. Follow the installation instructions carefully
2. Execute the notebook cells in order
3. Complete any exercises or challenges provided
4. Experiment with the code and parameters to deepen your understanding

## License

This project is available for educational purposes. Feel free to use and learn from it!

## Database Credits

The SQLite databases used in this project are sourced from the [SQLite Databases for Learning Data Science](https://github.com/davidjamesknight/SQLite_databases_for_learning_data_science) repository by David James Knight.