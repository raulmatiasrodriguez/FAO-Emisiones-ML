# 🌍 Análisis y Predicción de Emisiones GEI – FAO

Este proyecto analiza el dataset **“Totales de las Emisiones”** de la FAO, que contiene información global sobre emisiones agrícolas de gases de efecto invernadero (GEI) entre 1961 y 2020.  
El objetivo es identificar patrones, tendencias históricas y realizar **modelos predictivos basados en regresión lineal**.

El análisis completo se encuentra en el notebook:

📄 `notebooks/TP3_Practica.ipynb`

---

## 🔍 Objetivos del Proyecto

- Explorar tendencias globales de emisiones agrícolas.
- Comparar continentes, categorías y elementos contaminantes.
- Detectar relaciones entre variables mediante correlaciones.
- Identificar los productos que más contribuyen a las emisiones.
- Construir un modelo de **regresión lineal** para proyección futura.

---

## 🧠 Técnicas y Herramientas Utilizadas

**Python**
- Pandas  
- NumPy  
- Matplotlib / Seaborn  

**Machine Learning**
- Regresión lineal (scikit-learn)

**Análisis**
- EDA completo  
- Limpieza y transformación de datos  
- Matrices de correlación  
- Tendencias por continente y categoría  
- Detección de outliers  
- Comparaciones interregionales  

---

## 📊 Visualizaciones Principales

### 🔹 Boxplot de valores de emisiones
<img width="1919" height="1638" alt="boxplot_valor" src="https://github.com/user-attachments/assets/565ca2df-15eb-4e08-8d0d-627059578f19" />

### 🔹 Top 5 productos con mayor emisión acumulada
<img width="4027" height="1640" alt="top5_emisiones" src="https://github.com/user-attachments/assets/cf3fe5d4-67b5-4486-bbb3-dc95daa11e12" />

### 🔹 Matriz de correlaciones
<img width="2714" height="2461" alt="correlaciones" src="https://github.com/user-attachments/assets/e150e50a-dfcd-441a-8cd0-f5c1ea172413" />

### 🔹 Evolución de emisiones por continente
<img width="4930" height="1703" alt="evolucion_continentes" src="https://github.com/user-attachments/assets/ced3747e-d2f4-48ba-92fb-a8b1453babc0" />

### 🔹 Evolución por tipo de elemento
<img width="4930" height="1703" alt="evolucion_elementos" src="https://github.com/user-attachments/assets/44322ea4-7015-4be7-a159-6f89d6f13c31" />

### 🔹 Regresión lineal — Asia
<img width="1768" height="1363" alt="regresion_asia" src="https://github.com/user-attachments/assets/2f9e6a02-e1f0-4e23-bd60-b4e7b1fe6205" />

### 🔹 Regresión — Elemento 723113 (CO₂eq AR5)
<img width="1768" height="1363" alt="regresion_elemento_723113" src="https://github.com/user-attachments/assets/fea4e9a5-b7d4-461c-9093-6e4401577f4d" />

---

## 📈 Resultados Destacados

- **Asia** presenta la tendencia más pronunciada de crecimiento en emisiones agrícolas.
- El elemento **723113 (CO₂ equivalente – AR5)** es el de mayor impacto global.
- La matriz de correlación evidencia relaciones fuertes entre ciertos grupos de emisiones.
- Los **5 productos más contaminantes** concentran una proporción significativa del total.
- El modelo de regresión lineal permite realizar **proyecciones hacia 2030**, mostrando una tendencia alcista moderada.

---

## 📁 Estructura del Repositorio

```text
FAO-Emisiones-ML/
│
├── data/
│   └── raw/                 # Dataset original
│
├── notebooks/
│   └── TP3_Practica.ipynb   # Notebook principal
│
└── README.md
```

---

## 📌 Sobre los Datos Utilizados

El dataset principal de FAO no está incluido en este repositorio porque supera el límite de 25 MB impuesto por GitHub.

Dataset principal (NO incluido)

FAO — Emisiones Totales (Todos los Datos Normalizado)
Fuente oficial: https://www.fao.org/faostat/es/#data/GT

→ Pesa más de 16 MB pero descomprimido supera los 25 MB, por lo que no puede subirse directamente.

Cómo obtenerlo

Descargar desde el link oficial.

Guardarlo en:
```text
data/raw/
```
Con el nombre recomendado:
```text
FAO_Emisiones_Totales.csv
```
Si es necesario, ajustar en el notebook:
```text
file_path = '../data/raw/FAO_Emisiones_Totales.csv'
```

Archivo auxiliar incluido

✔ UNSD — Methodology.csv
Este archivo sí está disponible en data/raw/.

---

## ▶️ Cómo Ejecutar el Proyecto

1. Clonar el repositorio  
2. Colocar el dataset principal en data/raw/ (si corresponde)
3. Abrir el notebook desde Jupyter o Google Colab
4. Ejecutar las celdas en orden

---

## ✨ Autores

Este proyecto fue realizado en el marco de presentación de ultimo Trabajo Practico de la Materia Ciencia de Datos de la Licenciatura en Ciencia de Datos.

- **Acevedo, David**  
- **Contato, Juan Pablo**  
- **Galeano, Mónica Inés**  
- **Rodriguez, Raúl Matías**

Año: 2024 — Universidad del Gran Rosario  

