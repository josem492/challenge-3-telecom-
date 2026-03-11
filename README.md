# Challenge 2 - Predicción de Cancelación de Clientes - Telecom X

## Descripción
Este proyecto construye modelos de machine learning para predecir
la cancelación de clientes (Churn) en Telecom X, identificando
los factores de riesgo y proponiendo estrategias de retención.

## Estructura del proyecto
- TelecomX_LATAM_Parte2.ipynb → Notebook principal con el análisis
- TelecomX_datos_limpios.csv → Dataset procesado de la Parte 1
- README.md → Documentación del proyecto

## Tecnologías utilizadas
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Dependencias
No es necesario instalar ninguna librería adicional.
Todas las librerías están disponibles en Google Colab.

## Cómo ejecutar el proyecto
1. Abrir Google Colab (colab.research.google.com)
2. Subir el archivo TelecomX_LATAM_Parte2.ipynb
3. Subir el archivo TelecomX_datos_limpios.csv
4. Ejecutar las celdas en orden de arriba hacia abajo

## Etapas del análisis
- Preparación de datos: eliminación de columnas, encoding y normalización
- División del dataset: 80% entrenamiento y 20% prueba
- Modelos: Regresión Logística y Random Forest
- Evaluación: exactitud, precisión, recall, F1-score y matriz de confusión
- Análisis de variables más importantes por modelo

## Resultados
- Regresión Logística: 79.7% de exactitud
- Random Forest: 78.0% de exactitud
- La Regresión Logística detecta mejor las cancelaciones reales

## Principales factores de cancelación
- Servicio de fibra óptica
- Pago con cheque electrónico
- Contratos mes a mes
- Clientes con poca antigüedad

## Recomendaciones
- Incentivar contratos anuales o de dos años
- Programa de fidelización para clientes nuevos
- Revisar precio y calidad del servicio de fibra óptica
- Atención proactiva a clientes con cheque electrónico
