# DISEÑO E IMPLEMENTACIÓN DE UNA SOLUCIÓN DE BIG DATA PARA LA TRANSFORMACIÓN Y ANÁLISIS DEL ESTADO DE RESULTADOS POR AGENCIAS – CONFIAR COOPERATIVA FINANCIERA

**Estudiantes:** Paola Duque Cardona
                 Ana Carolina Osorio 
                 Yuliana Gomez Franco
# 1. CASO DE NEGOCIO

## 1.1. Descripción del problema

En las entidades financieras se generan grandes volúmenes de información contable que requieren procesos de extracción, transformación, clasificación y análisis para convertir los datos en información útil para la toma de decisiones. 
En Confiar Cooperativa Financiera, la información contable es gestionada mediante el ERP institucional, el cual registra los movimientos contables generados por las diferentes Agencias. De forma mensual, el sistema genera informes de libros auxiliares que contienen el detalle de cada movimiento contable realizado durante el período.
Aunque estos reportes constituyen una fuente valiosa de información para el análisis financiero, los datos se encuentran sin una estructura para el análisis gerencial, por lo que es necesario realizar procesos de consolidación, clasificación y transformación antes de obtener información útil para la toma de decisiones.

Por lo anterior, se plantea desarrollar una solución que permita automatizar el procesamiento de los libros auxiliares contables, estructurar la información y facilitar la construcción del estado de resultados por cada una de las Agencias en su respectivo periodo, mediante herramientas de analítica de datos y visualización.

## Objetivo General
Diseñar e implementar una solución para el procesamiento y análisis de datos que permita automatizar la transformación, clasificación y consolidación de los movimientos contables de Confiar Cooperativa Financiera, con el propósito de facilitar la construcción y análisis del estado de resultados por agencias y periodos, apoyando la toma de decisiones mediante herramientas de analítica y visualización.

## Objetivos Especificos
 - Analizar la estructura y composición de los libros auxiliares contables generados por el ERP de Confiar Cooperativa Financiera, identificando las variables necesarias para la construcción del estado de resultados.
 - Diseñar un proceso de transformación de datos que permita clasificar y asociar las cuentas contables a las categorías de ingresos, gastos y demás componentes requeridos para el análisis financiero por agencia.
 - Implementar un flujo automatizado de procesamiento de datos mediante la herramienta KNIME para la integración, depuración y consolidación de la información proveniente de múltiples períodos contables.
 - Desarrollar un tablero de visualización que facilite el seguimiento de los resultados financieros por agencia, período y concepto contable, apoyando la toma de decisiones organizacionales.


## 1.4. Alcance del proyecto

El proyecto transforma los libros auxiliares contables correspondientes a diferentes periodos de Confiar Cooperativa Financiera en un modelo de Perdidas y ganancias (PyG)

La solución comprende las siguientes actividades:

- Consolidación de los archivos que contienen la información contable.
- Validación de la estructura y calidad de los datos.
- Limpieza y estandarización de los campos necesarios para el análisis.
- Clasificación y agrupación de cuentas contables según los criterios del PyG.
- Consolidación de los movimientos por agencia y periodo.
- Construcción de la estructura de datos para la elaboración del estado de resultados.
- Automatización del procesamiento mediante KNIME.
- Visualización de los resultados a través de un tablero en Power BI.

## 1.5. Justificación

La transformación de datos contables en información estructurada permite reducir actividades manuales, mejorar la consistencia de los resultados y facilitar el análisis de la información financiera.

se utilizará KNIME como herramienta principal para diseñar y ejecutar el flujo de transformación de datos, permitiendo automatizar tareas repetitivas y garantizar una estructura de información estandarizada. 

Posteriormente, los datos procesados serán visualizados en Power BI mediante un tablero interactivo que facilite la consulta y el análisis de los resultados financieros.

De esta manera, el proyecto busca convertir datos contables dispersos en información útil para la toma de decisiones, aplicando técnicas de analítica de datos para mejorar la eficiencia del proceso y fortalecer la disponibilidad de información financiera para las diferentes áreas de la organización.

