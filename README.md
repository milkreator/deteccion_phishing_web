
# Proyecto Sprint 01 – Análisis de Datos con Interfaz Interactiva

Este repositorio contiene el desarrollo del Sprint 1 del curso **Proyecto de Análisis de Datos**, incluyendo un análisis exploratorio de datos (EDA) y una interfaz interactiva con `ipywidgets`.

---

## 📁 Estructura del repositorio

```
proyecto_sprint01/
├── Data/                  # Archivos de datos CSV provistos
│   ├── train.csv
│   ├── test.csv
│   └── Diccionario.csv
│
├── Notebooks/            # Notebooks Jupyter desarrollados
│   ├── EDA.ipynb         # Análisis exploratorio de datos
│   └── Interfaz.ipynb    # Interfaz interactiva con ipywidgets y MongoDB
│
├── Utils/                # Funciones auxiliares (limpieza, etc.)
│   └── limpieza.py
│
├── Sprint01.pdf          # Enunciado del Sprint (para referencia)
├── requirements.txt      # Lista de librerías necesarias
├── .gitignore            # Archivos y carpetas a ignorar por Git
└── README.md             # Este archivo
```

---

## 🚀 ¿Cómo ejecutar el proyecto?

1. Clona este repositorio:

```bash
git clone https://github.com/tu_usuario/proyecto_sprint01.git
cd proyecto_sprint01
```

2. Crea un entorno virtual (opcional pero recomendado):

```bash
python -m venv env
source env/bin/activate  # En Windows: env\Scripts\activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Abre los notebooks:

```bash
jupyter notebook
```

---

## 📦 Librerías requeridas

Incluyen, pero no se limitan a:

- pandas
- numpy
- matplotlib
- seaborn
- ipywidgets
- pymongo

> Todas están listadas en `requirements.txt`.

---

## 🌐 Conexión a MongoDB

La interfaz interactiva permite:
- Subir archivos CSV (`train.csv`, `test.csv`)
- Cargar los datos en MongoDB Atlas (colecciones: `prestamo_train`, `prestamo_test`)
- Realizar análisis exploratorio y visualización interactiva

---

## 👥 Integrantes del equipo

- Jorge Alberto Alzamora Escobar
- Milko César Rodríguez Arellano
- Ernesto Franco Silva Barra
- Anthony Abel Talavera Carranza

---

## 🕒 Fecha de entrega

**Viernes 2 de mayo – 7:00 PM**
