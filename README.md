# 🌿 Sistema de Registro de Fauna y Flora (IFN)

## 📌 Descripción

Este proyecto es una aplicación desarrollada en Python que permite registrar, organizar y visualizar información relacionada con inventarios de fauna y flora, siguiendo una estructura similar a la utilizada en el Inventario Forestal Nacional (IFN).

El sistema utiliza una interfaz interactiva basada en `ipywidgets`, permitiendo al usuario ingresar datos de manera sencilla sin necesidad de conocimientos avanzados en programación.

---

## 🎯 Objetivo

Facilitar el registro y gestión de información ambiental, incluyendo:

- Brigadas de trabajo
- Conglomerados (zonas de muestreo)
- Especies de flora
- Especies de fauna

Además, permite generar un reporte general de los datos registrados.

---

## ⚙️ Funcionalidades principales

### 🧑‍🤝‍🧑 Registro de Brigadas
- ID de brigada
- Líder profesional
- Coinvestigador local

### 📍 Registro de Conglomerados
- ID del conglomerado
- Coordenadas GPS
- Brigada asociada

### 🌳 Registro de Flora
- ID de muestra
- Conglomerado
- Nombre común
- Uso (Medicinal, Alimenticio, Maderable)
- DAP (Diámetro a la altura del pecho)

Clasificación automática:
- Brinzal: 2.5 – 9.9 cm  
- Latizal: 10 – 29.9 cm  
- Fustal: ≥ 30 cm  

### 🐾 Registro de Fauna
- ID de muestra
- Conglomerado
- Especie
- Grupo (Aves, Mamíferos, Reptiles)
- Estado de conservación

### 📊 Reporte Integral
Resumen de conglomerados con su flora y fauna registrada.

---

## 💾 Almacenamiento

Archivos CSV generados automáticamente:

- brigadas.csv
- conglomerados.csv
- flora.csv
- fauna.csv

---

## 🖥️ Requisitos

- Python 3.x
- ipywidgets

Instalación:
```bash
pip install ipywidgets
```

---

## ▶️ Uso

Ejecutar en:

- Google Colab
- Jupyter Notebook

Luego interactuar con la interfaz.

---

## 🚀 Mejoras futuras

- Validación de datos
- Edición/eliminación de registros
- Visualización gráfica
- Exportación a Excel o PDF

---

## 👨‍💻 Autor

Proyecto académico.
