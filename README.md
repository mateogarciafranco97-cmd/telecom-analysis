# ConnectaTel Analysis – Sprint 6

Este repositorio contiene el análisis realizado durante el Sprint 6 del caso ConnectaTel.

Fuentes de datos:
El dataset `plans.csv` contiene: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
El dataset `users_latam.csv` contiene: información de clientes: edad, ciudad, fecha de registro, plan contratado.
El dataset `usage.csv` contiene: el detalle de uso real: llamadas (duración) y mensajes (longitud).

Estos datasets incluyen 4,000 user id de clientes con valores faltantes, sentinels, outliers y problemas de calidad a excepción del dataset de plans que es una tabla pequeña sin problemas en los datos.

## 📂 Contenido del repositorio

- `S7 Project-ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers, agrupaciones, visualización distribuciones, segmentación de clientes y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mateogarciafranco97-cmd/telecom-analysis/blob/main/S7%20Project-ConnectaTel.ipynb) 


O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S7 Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga los datos desde el enlace/fuente que se utilizo originalmente (según corresponda)

## 🧠 Objetivo del análisis

- Integrar y limpiar bases de datos provenientes de tres fuentes distintas.

- Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes.

- Construir un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.

- Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales.

- Crear segmentaciones de clientes basadas en edad, país y comportamiento de uso.

- Visualizar diferencias entre segmentos y extraer insights comerciales relevantes.
