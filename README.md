
# Proyecto Sprint 01 – Análisis de Datos con Interfaz Interactiva

Este repositorio contiene el desarrollo del Sprint 1 del curso **Proyecto de Análisis de Datos**, incluyendo un análisis exploratorio de datos (EDA) y una interfaz interactiva con `ipywidgets`.

---

## 📁 Estructura del repositorio

```
proyecto_sprint01/
├── Data/                  
│   └── Sales.xlsx         # Dataset principal cargado y analizado
│
├── Notebooks/            
│   └── Sprint1_Grupo3_PAD.ipynb   # Notebook unificado con EDA e interfaz interactiva
│
├── Sprint01.pdf           # Enunciado del Sprint (para referencia)
├── requirements.txt       # Lista de librerías necesarias
├── .gitignore             # Archivos y carpetas a ignorar por Git
└── README.md              # Este archivo
```

---

## 🚀 ¿Cómo ejecutar el proyecto?

1. Clona este repositorio:

```bash
git clone https://github.com/milkreator/proyecto_sprint01.git
cd proyecto_sprint01
```

2. Crea un entorno virtual:

```bash
python3 -m venv venv_sprint01
source venv_sprint01/bin/activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Abre el notebook principal:

```bash
jupyter notebook Notebooks/Sprint1_Grupo3_PAD.ipynb
```

---

## 📦 Librerías requeridas

- pandas
- numpy
- matplotlib
- seaborn
- ipywidgets
- pymongo

---

## 🌐 Funcionalidad principal

- Subida de archivos `.csv` o `.xlsx`
- Visualización de los primeros registros
- Migración de datos a MongoDB
- Exploración de datos con widgets:
  - Dimensiones, tipos, nulos, resumen
  - Histogramas, boxplots, dispersión, outliers
  - Filtros dinámicos por columna

---

## 👥 Integrantes del equipo

- Jorge Alberto Alzamora Escobar
- Milko César Rodríguez Arellano
- Ernesto Franco Silva Barra
- Anthony Abel Talavera Carranza

---

## 🕒 Fecha de entrega

**Viernes 2 de mayo – 7:00 PM**
