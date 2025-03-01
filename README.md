[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-green?logo=GitHub)](https://github.com/JonatanSiracusa/download-historical-series)
[![Connect on LinkedIn](https://img.shields.io/badge/LinkedIn-Connect_on_LinkedIn-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/ajsiracusa/)
[![Read on Medium](https://img.shields.io/badge/Medium-Read_on_Medium-blueviolet?logo=medium)](https://jonatansiracusa.medium.com/)
[![View on Website](https://img.shields.io/badge/GitHub-View_on_Website-red?logo=GitHub)](https://jonatansiracusa.github.io/2024/11/14/Download-historical-series/)


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

- Descarga de datos financieros desde `yfinance`.
*	Conversión de datos en una serie de datos.
* Se exportan los datos en archivos `.csv` y `.xlsx`. 




🚀 *Si te gustó este proyecto, dale una estrella ⭐ en GitHub y sígueme en [LinkedIn](https://linkedin.com/in/tuusuario) y [GitHub](https://github.com/tuusuario).*


---



# Portfolio Optimization with Python

## Descripción

Este proyecto implementa modelos de optimización de portafolios de inversión, incluyendo el modelo de Markowitz y Black-Litterman, utilizando Python.

## Características

- Optimización de portafolios usando teoría moderna de portafolios.
- Implementación del modelo de Black-Litterman.
- Uso de `cvxpy` para resolver problemas de optimización convexa.
- Descarga de datos financieros desde `yfinance`.
- Visualización de la frontera eficiente.

## Requisitos

Asegúrate de tener Python 3.8 o superior instalado. Instala las dependencias ejecutando:

```
pip install -r requirements.txt
```

## Instalación

1. Clonar el repositorio:
   ```
   git clone https://github.com/tuusuario/portfolio-optimization.git
   cd portfolio-optimization
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
4. Instalar dependencias:
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

## Contribución

Si deseas contribuir, sigue estos pasos:

1. Realiza un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature-nueva-funcionalidad`).
3. Realiza commits con descripciones claras (`git commit -m "Añadir nueva funcionalidad"`).
4. Envía un Pull Request.

Para más detalles, revisa el archivo `CONTRIBUTING.md`.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

🚀 *Si te gustó este proyecto, dale una estrella ⭐ en GitHub y sígueme en [LinkedIn](https://linkedin.com/in/tuusuario) y [GitHub](https://github.com/tuusuario).*
































🚀 *Si te gustó este proyecto, dale una estrella ⭐ en GitHub y sígueme en [LinkedIn](https://linkedin.com/in/tuusuario) y [GitHub](https://github.com/tuusuario).*
