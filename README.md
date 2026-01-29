# Series_de_tiempo
📈 Series de Tiempo — Repositorio Académico

Este repositorio contiene material teórico, notebooks prácticos y ejemplos aplicados para el estudio y análisis de series de tiempo, con énfasis en modelos clásicos, modelos estacionales y aplicaciones financieras.

El objetivo principal es proporcionar una base sólida tanto conceptual como computacional para la modelación, análisis, pronóstico y evaluación de series temporales, utilizando herramientas modernas de análisis estadístico y programación.

📌 Contenido
1. Introducción a las Series de Tiempo

Se presenta el marco teórico fundamental para comprender la estructura y el comportamiento de una serie temporal.

Temas:

Definición y componentes de una serie de tiempo

Tendencia

Estacionalidad

Ciclo

Componente irregular

Estacionariedad

Transformaciones:

Diferenciación

Logaritmos

Normalización

Descomposición clásica y STL

Visualización y análisis exploratorio

2. Modelos ARIMA y SARIMA — Autocorrelación y Autocorrelación Parcial

Se estudian los modelos lineales clásicos para la modelación y pronóstico de series temporales estacionarias y estacionales.

Temas:

Procesos:

AR (Autorregresivos)

MA (Media móvil)

ARMA

ARIMA

Estacionalidad y modelo SARIMA

Función de autocorrelación (ACF)

Función de autocorrelación parcial (PACF)

Identificación de modelos

Estimación de parámetros

Diagnóstico de residuos

Validación de modelos

Pronóstico

3. Series de Tiempo Financieras — Volatilidad y Modelos ARCH/GARCH

Análisis avanzado de series financieras con énfasis en modelación de volatilidad, heterocedasticidad condicional y gestión del riesgo.

Temas:

Características de series financieras:

Rendimientos

Clustering de volatilidad

Colas pesadas

Leverage effect

Modelos:

ARCH

GARCH

EGARCH

TGARCH

GJR-GARCH

Distribuciones no normales

Pronóstico de volatilidad

Value at Risk (VaR)

Aplicaciones en finanzas cuantitativas

🛠️ Tecnologías Utilizadas

Python

NumPy

Pandas

Matplotlib

Seaborn

statsmodels

arch

📂 Estructura del Repositorio
📁 time-series/
│
├── 01_introduccion/
├── 02_arima_sarima/
├── 03_series_financieras/
│   ├── garch/
│   ├── egarch/
│   └── var/
│
├── datasets/
├── notebooks/
└── README.md

🎯 Objetivo del Repositorio

Proporcionar una guía integral para:

Comprender la teoría de series de tiempo.

Implementar modelos clásicos y avanzados.

Aplicar técnicas modernas en contextos financieros reales.

Desarrollar habilidades prácticas en análisis temporal y pronóstico.

📊 Ejemplos Aplicados

Pronóstico de demanda

Series macroeconómicas

Series financieras (acciones, índices, volatilidad)

Evaluación de riesgo financiero
