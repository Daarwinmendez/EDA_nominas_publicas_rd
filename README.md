# Análisis Exploratorio de Datos (EDA) de Nóminas Públicas

## Descripción del Proyecto
Este proyecto fue desarrollado por Darwin Domingo Méndez (2023-0769) y Roither Sánchez Sosa (2022-2111) como parte de la asignatura de Procesamiento de Lenguaje Natural (NLP) impartida por el maestro Carlos Ogando en el ITLA, y se considera un warm-up de la asignatura. El objetivo principal es realizar un **Análisis Exploratorio de Datos (EDA)** a partir de nóminas públicas de cinco instituciones: UASD, MIVHED, OPRET, UAF y SNS. Se utiliza **Python** junto con las bibliotecas **pandas**, **numpy** y **matplotlib** para cargar, concatenar, limpiar, visualizar y analizar los datos, buscando patrones importantes relacionados con los salarios y otras variables.

## Objetivos del Proyecto
1. Recopilar nóminas públicas de cinco instituciones.
2. Cargar los datos en Python sin procesarlos previamente en Excel.
3. Concatenar todas las nóminas en un solo dataset.
4. Evaluar la calidad de los datos, identificando valores nulos o mal formateados.
5. Calcular estadísticas básicas (promedio, mediana, mínimo, máximo, desviación estándar) usando **numpy**.
6. Explorar la distribución de los datos por columna.
7. Analizar ingresos por género, cargo, institución y otras variables.
8. Visualizar distribuciones salariales y correlaciones usando **matplotlib**.
9. Reportar otros hallazgos importantes durante el análisis.

## Tecnologías Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Key Takeaways del EDA
- **Integración de datos**: Se lograron combinar nóminas de cinco instituciones en un solo conjunto de datos estandarizado.
- **Distribución salarial**: Se observaron distribuciones salariales sesgadas hacia la derecha, con algunos valores atípicos.
- **Disparidad de género**: En el SNS, el 70% de los empleados son mujeres.
- **Correlación sueldo bruto-neto**: Existe una fuerte correlación entre el sueldo bruto y el neto, analizada con **numpy**.
- **Outliers salariales**: Se identificaron numerosos valores atípicos, lo que sugiere disparidad salarial.
- **Variabilidad en descuentos**: Se notó una variabilidad significativa en los descuentos por ISR, seguro, y otros conceptos.
- **Estandarización de datos**: Mejoras en la calidad de los datos mediante estandarización de variables y manejo de valores faltantes.
- **Diferencias institucionales**: Existen variaciones significativas en la composición de la fuerza laboral y en la estructura salarial entre las instituciones.

## Requisitos
- Python 3.x
- pandas
- numpy
- matplotlib
- Jupyter Notebook

## Cómo ejecutar el proyecto
1. Clona este repositorio: `git clone https://github.com/Daarwinmendez/EDA_nominas_publicas_rd`
2. Instala las dependencias: `pip install -r requirements.txt`
3. Ejecuta el archivo `EDA_nominas_publicas_rd` en Jupyter Notebook o en cualquier IDE de Python.

## Contribuciones
Las contribuciones y sugerencias son bienvenidas. Por favor, abre un issue o envía un pull request si deseas mejorar el proyecto.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
