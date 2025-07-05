
# 📈 Proyecto de Análisis de Evasión de Clientes – Telecom X

## 🧠 Descripción General

Este repositorio contiene un proyecto de análisis de datos centrado en entender y reducir la tasa de cancelación de clientes (churn) de **Telecom X**, una empresa ficticia del sector telecomunicaciones. En el rol de Asistente de Análisis de Datos, el objetivo fue recopilar, limpiar y analizar la información de clientes para detectar los factores que impulsan la pérdida de usuarios.

El análisis exploratorio de datos (EDA) realizado sirve como punto de partida para futuros modelos predictivos y para diseñar estrategias efectivas de retención de clientes.

---

## 🎯 Propósito del Proyecto

Telecom X enfrenta un problema crítico: muchos clientes están abandonando sus servicios. Este análisis busca:

- Detectar patrones de comportamiento comunes entre los clientes que se dan de baja.
- Identificar variables clave (como datos demográficos, tipo de servicio, tipo de contrato y comportamiento de consumo) relacionadas con el churn.
- Extraer conclusiones útiles que permitan al equipo de Ciencia de Datos y a la dirección de la empresa tomar decisiones informadas para reducir la evasión.

---

## 🗂️ Contenido del Repositorio

- `README.md`: Este archivo, con información general del proyecto.
- `Challenge Telecom X: análisis de evasión de clientes.ipynb`: Notebook principal con todo el código, análisis y visualizaciones del proyecto.
- `df_final.csv`: Archivo CSV con los datos finales ya transformados y listos para análisis o modelado.

---

## 🛠️ Herramientas Utilizadas

El análisis fue desarrollado usando **Python** junto con las siguientes librerías:

- `pandas`: para manipulación y transformación de datos.
- `numpy`: para operaciones numéricas.
- `matplotlib`: para visualizaciones básicas.
- `seaborn`: para gráficos estadísticos más detallados y atractivos.

---

## 🚀 Fases del Proyecto

1. **Carga de Datos**
   - Se importó el archivo `.json` desde GitHub y se convirtió en un DataFrame para trabajar con él fácilmente.

2. **Limpieza y Procesamiento**
   - Se normalizó la estructura del JSON.
   - Se gestionaron valores faltantes y errores en los datos.
   - Se ajustaron los tipos de datos.
   - Se transformaron columnas categóricas (por ejemplo, ‘Yes’/‘No’ a 1/0).
   - Se combinaron diferentes estructuras en un solo DataFrame consolidado.

3. **Análisis Exploratorio (EDA)**
   - Se calculó la tasa general de churn.
   - Se analizaron variables categóricas y su relación con el churn (ej. tipo de contrato, método de pago).
   - Se exploraron variables numéricas (como duración del contrato o total facturado) con estadísticas descriptivas y gráficos como histogramas y boxplots para detectar tendencias relevantes.
