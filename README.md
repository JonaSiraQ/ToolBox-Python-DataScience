[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-green?logo=GitHub)](https://github.com/JonatanSiracusa/download-historical-series)
[![Connect on LinkedIn](https://img.shields.io/badge/LinkedIn-Connect_on_LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/ajsiracusa/)
[![Read on Medium](https://img.shields.io/badge/Medium-Read_on_Medium-blueviolet?logo=medium)](https://jonatansiracusa.medium.com/)
[![View on Website](https://img.shields.io/badge/GitHub-View_on_Website-red?logo=GitHub)](https://jonatansiracusa.github.io/2024/11/14/Download-historical-series/)


# Downloading Historical Prices

In this simple notebook, we can download historical price series in a scalable way, including various categories (Adj Close, Close, High, Low, Open, Volume). Additionally, we save the data in downloadable files in case you want to work offline.

## Contact

If you have any questions about this project, feel free to contact me:

- **LinkedIn:** [linkedin.com/in/ajsiracusa](https://www.linkedin.com/in/ajsiracusa)
- **GitHub:** [github.com/JonatanSiracusa](https://github.com/JonatanSiracusa)
- **Medium:** [jonatansiracusa.medium.com](https://jonatansiracusa.medium.com/)
- **GitHub Page:** [jonatansiracusa.github.io](https://jonatansiracusa.github.io/)

## Demo on..

## Table of Contents:

1. [Features](#Features)
2. [Requirements](#Requirements)
3. [Installation](#Installation)
4. [Usage](#Usage)
5. [Examples and Visualizations](#Examples-and-Visualizations)
6. [Project Structure](#Project-Structure)
7. [Technologies](#Technologies)
8. [Contribution](#Contribution)
9. [License](#License)

## Features

* Download financial data from `yfinance`.
* Convert data into a time series Dataframe.
* Export data to `.csv` and `.xlsx` files.
* Deployed on GitHub Pages and Streamlit.

## Requirements

Python 3.8 or higher was used in development. Install dependencies by running:

```
pip install -r requirements.txt
```

## Installation

1. Clone the repository:

```
git clone https://github.com/YOUR_USER/PROJECT_NAME.git
cd PROJECT_NAME
```

2. Create a virtual environment:

```
python -m venv env
```

3. Activate the virtual environment:

- On Windows:
	```
	.\env\Scripts\activate
	```
- On macOS/Linux:
	```
	source env/bin/activate
	```

4. Install libraries:

```
pip install -r requirements.txt
```

## Usage

Run the main script to optimize a portfolio with selected assets:

```
python optimize_portfolio.py
```

Example input and output:

```
{
  "assets": ["AAPL", "MSFT", "TSLA", "AMZN"],
  "period": "5y"
}
```

Expected output:

```
{
  "optimized_weights": {"AAPL": 0.3, "MSFT": 0.25, "TSLA": 0.2, "AMZN": 0.25},
  "expected_return": 0.15,
  "risk": 0.12
}
```

## Examples and Visualizations

📈 Efficient Frontier Chart (Example)\

📉 Return Distribution\

## Project Structure

```
portfolio-optimization/
│-- optimize_portfolio.py   # Main script
│-- data/                   # Downloaded data
│-- models/                 # Financial model implementations
│-- utils/                  # Utility functions
│-- tests/                  # Unit tests
│-- README.md               # This file
│-- LICENSE                 # Project license
│-- requirements.txt        # Project dependencies
│-- .gitignore              # Files to ignore in Git
```

## Technologies

- Python (Pandas, NumPy, SciPy)
- Matplotlib / Plotly
- GitHub Pages for deployment
- Streamlit for UI

## Contribution

If you want to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-new-feature`).
3. Make commits with clear descriptions (`git commit -m "Add new feature"`).
4. Submit a Pull Request.

For more details, check the `CONTRIBUTING.md` file.

## License

This project is under the MIT License. See the `LICENSE` file for details.

--

*If you find this repository useful, give it a star ⭐ on GitHub and follow me on [LinkedIn](https://www.linkedin.com/in/ajsiracusa) and [GitHub](https://github.com/JonatanSiracusa).*

---

# Descargando Precios Históricos

En este sencillo notebook podemos descargar, de forma escalabale, series de precios históricos con sus distintas categorías (Adj Close, Close, High, Low, Open, Volume). Asimismo, guardamos los datos en archivos descargables, en caso de desear trabajar sin estar conectados a internet.

## Contacto

Si tenes preguntas sobre este proyecto, no dudes en contactarme a través de:

- **LinkedIn:** [linkedin.com/in/ajsiracusa](https://www.linkedin.com/in/ajsiracusa)
- **GitHub:** [github.com/JonatanSiracusa](https://github.com/JonatanSiracusa)
- **Medium:** [jonatansiracusa.medium.com](https://jonatansiracusa.medium.com/)
- **GitHub Page:** [jonatansiracusa.github.io](https://jonatansiracusa.github.io/)

## Demo en..

## Tabla de Contenidos:

1. [Características](#Características)
2. [Requisitos](#Requisitos)
3. [Instalación](#Instalación)
4. [Uso](#Uso)
5. [Ejemplos y Visualizaciones](#Ejemplos-y-Visualizaciones)
6. [Estructura del Proyecto](#Estructura-del-Proyecto)
7. [Tecnologías](#Tecnologías)
8. [Contribución](#Contribución)
9. [Licencia](#Licencia)

## Características

* Descarga de datos financieros desde `yfinance`.
* Conversión de datos en una serie de datos.
* Se exportan los datos en archivos `.csv` y `.xlsx`. 
* Desplegado en GitHub Pages y Streamlit.

## Requisitos

Se utilizo Python 3.8 o superior instalado, en el desarrollo. Instala las dependencias ejecutando:

```
pip install -r requirements.txt
```

## Instalación

1. Clonar el repositorio:

```
git clone https://github.com/TU_USUARIO/NOMBRE_DEL_PROYECTO.git
cd NOMBRE_DEL_PROYECTO
```

2. Crear un entorno virtual:

```
python -m venv env
```

3. Activar el entorno virtual:

- En Windows:
	```
	.\env\Scripts\activate
	```
- En macOS/Linux:
	```
	source env/bin/activate
	```

4. Instalar librerías:

```
pip install -r requirements.txt
```

## Uso

Ejecuta el script principal para optimizar un portafolio con activos seleccionados:

```
python optimize_portfolio.py
```

Ejemplo de entrada y salida:

```
{
  "assets": ["AAPL", "MSFT", "TSLA", "AMZN"],
  "period": "5y"
}
```

Salida esperada:

```
{
  "optimized_weights": {"AAPL": 0.3, "MSFT": 0.25, "TSLA": 0.2, "AMZN": 0.25},
  "expected_return": 0.15,
  "risk": 0.12
}
```

## Ejemplos y Visualizaciones

📈 Gráfico de Frontera Eficiente (Ejemplo)\

📉 Distribución de Retornos\


## Estructura del Proyecto

```
portfolio-optimization/
│-- optimize_portfolio.py   # Script principal
│-- data/                   # Datos descargados
│-- models/                 # Implementaciones de modelos financieros
│-- utils/                  # Funciones auxiliares
│-- tests/                  # Pruebas unitarias
│-- README.md               # Este archivo
│-- LICENSE                 # Licencia del proyecto
│-- requirements.txt        # Dependencias del proyecto
│-- .gitignore              # Archivos a ignorar por Git
```

## Tecnologías

- Python (Pandas, NumPy, SciPy)
- Matplotlib / Plotly
- GitHub Pages para despliegue
- Streamlit para la interfaz

## Contribución

Si deseas contribuir, segui estos pasos:

1. Realiza un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature-nueva-funcionalidad`).
3. Realiza commits con descripciones claras (`git commit -m "Añadir nueva funcionalidad"`).
4. Envia un Pull Request.

Para más detalles, revisa el archivo `CONTRIBUTING.md`.


## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

--

*Si el respositorio te resulta útil, dale una estrella ⭐ en GitHub y seguime en [LinkedIn](https://www.linkedin.com/in/ajsiracusa) y [GitHub](https://github.com/JonatanSiracusa).*
