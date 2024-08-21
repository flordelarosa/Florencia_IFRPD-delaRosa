# Predicción del Riesgo de Diabetes Basado en Encuestas de Salud

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un modelo de clasificación para predecir el desarrollo de diabetes en individuos, utilizando datos de encuestas sobre variables relacionadas con la salud, hábitos, y parámetros socioeconómicos y demográficos. La identificación de los factores de riesgo más significativos que predicen el riesgo de diabetes puede ser una herramienta valiosa para profesionales de la salud, estudiantes e investigadores, ayudando a identificar patrones en los datos que puedan influir en el desarrollo de la enfermedad y apoyando la toma de decisiones para la prevención y tratamiento.

## Archivos del Proyecto

- **Florencia_IFRPD+delaRosa_EntregaFinal.ipynb**: Cuaderno Jupyter que contiene el código final del modelo de predicción, análisis de datos, y resultados.
- **Florencia_IFRPD+delaRosa_EntregaFinal.pdf**: Documento en PDF que incluye la explicación detallada del proyecto, los métodos utilizados, y los resultados obtenidos.
- **Florencia_IFRPD+delaRosa_Preentrega.ipynb**: Cuaderno Jupyter de una entrega preliminar que documenta el progreso y los ajustes realizados durante el desarrollo del proyecto.
- **Florencia_IFRPD+delaRosa_Preentrega.pdf**: Documento en PDF de la versión preliminar del proyecto.
- **diabetes_012_health_indicators_BRFSS2015.csv**: Dataset utilizado para el análisis, proveniente de la Encuesta BRFSS sobre indicadores de salud en relación a la diabetes en Estados Unidos.
- **README.md**: Este archivo, que provee una descripción general del proyecto.

## Dataset

El dataset **diabetes_012_health_indicators_BRFSS2015.csv** proviene de la Encuesta de Factores de Riesgo de Comportamiento (BRFSS) de 2015 en Estados Unidos. Incluye variables relacionadas con la salud general, hábitos, y condiciones médicas, las cuales se utilizan para predecir el riesgo de diabetes.

## Modelo de Predicción

El modelo seleccionado para este proyecto es **XGBClassifier II**, el cual ha mostrado ser el más eficaz para nuestros objetivos. Aunque el F1-score es bajo para la clase de prediabetes, este modelo ofrece un buen balance entre recall y precisión para las clases de prediabetes y diabetes, permitiendo una identificación efectiva para intervenciones tempranas.

### Resultados Clave

- **Factores de riesgo identificados**: Peor salud general, hipertensión, alto IMC, dificultad para caminar, colesterol alto, mayor edad, enfermedades cardíacas y baja actividad física.
- **Desempeño del modelo**: El modelo XGBClassifier II proporciona el mejor recall para la clase 1 (prediabetes) y un mejor desempeño en la clase 2 (diabetes), lo cual es fundamental para la prevención y tratamiento.

## Instrucciones de Uso

1. Clonar el repositorio.
2. Instalar las dependencias necesarias.
3. Ejecutar el cuaderno Jupyter **Florencia_IFRPD+delaRosa_EntregaFinal.ipynb** para replicar el análisis y obtener los resultados.

## Contacto

Para preguntas o comentarios sobre el proyecto, por favor contactar a florg.dlr@gmail.com.
