# 🧠 ONLINE_DS_THEBRIDGE_YanJun

Repositorio personal del itinerario de **Data Science** realizado en *The Bridge*.  
Incluye notebooks, ejercicios y proyectos organizados por módulos, abarcando desde fundamentos de programación hasta *Machine Learning* y *Data Engineering*.

---

## 📂 Estructura del repositorio

```
ONLINE_DS_THEBRIDGE_YanJun/
├── analytics/
│   └── EDA/                 # Análisis exploratorio de datos
├── Machine Learning/        # Modelado clásico y evaluación
├── Data Engineering/
│   └── LLM/                 # Experimentos con LLMs y data pipelines
├── fundamentals/
│   └── hundir la flota/     # Proyecto de fundamentos (Python)
└── CAPGEMINI/               # Caso práctico de empresa
```

---

## 🚀 Instalación y uso

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/yanjunchenye/ONLINE_DS_THEBRIDGE_YanJun.git
cd ONLINE_DS_THEBRIDGE_YanJun
```

### 2️⃣ Crear entorno virtual

```bash
python -m venv .venv
source .venv/bin/activate   # En Windows: .venv\Scripts\activate
```

### 3️⃣ Instalar dependencias

```bash
pip install -U pip wheel
pip install jupyterlab numpy pandas matplotlib seaborn scikit-learn plotly tqdm joblib
# Si trabajas con LLMs o Data Engineering:
# pip install openai langchain tiktoken sentence-transformers sqlalchemy
```

### 4️⃣ Iniciar Jupyter Lab

```bash
jupyter lab
```

---

## 📘 Descripción por carpetas

### 🧩 `analytics/EDA`
- Limpieza y exploración de datos  
- Visualizaciones y *profiling*  
- Análisis descriptivo de datasets

### 🤖 `Machine Learning`
- Modelado predictivo y clasificación  
- Evaluación con métricas y *cross-validation*  
- Construcción de *pipelines* en `scikit-learn`

### ⚙️ `Data Engineering/LLM`
- Experimentos con *Large Language Models* (LLMs)  
- Ingesta y transformación de datos  
- Ejercicios de automatización y orquestación ligera

### 🐍 `fundamentals/hundir la flota`
- Proyecto en Python: implementación del clásico juego *Hundir la flota*  
- Enfoque en lógica, control de flujo y diseño modular

### 🏢 `CAPGEMINI`
- Caso práctico aplicado a empresa  
- Documentación, análisis y notebooks específicos

---

## 🧪 Estructura recomendada de datos

```
data/
├── raw/         # Datos originales
├── interim/     # Procesados parcialmente
└── processed/   # Listos para modelar
```

> ⚠️ Los datasets no se incluyen en el repositorio. Añádelos localmente dentro de la carpeta `data/`.

---

## 🧭 Recomendaciones

- Usa nombres claros para notebooks:  
  `01_eda.ipynb`, `02_preprocessing.ipynb`, `03_model.ipynb`, etc.
- Guarda tus modelos con `joblib` (`model.joblib`).
- Añade un `.env` para tus claves API (si usas OpenAI o similares).

---

## 📜 Licencia

Este proyecto **no tiene una licencia pública**.  
Todos los derechos están reservados (© Yan Jun).  
No se permite la reproducción, distribución ni uso del código sin autorización expresa del autor.

---

## ✍️ Autor

**Yan Jun**  
Estudiante de Data Science  
GitHub: [@yanjunchenye](https://github.com/yanjunchenye)

---

## 🌟 Notas finales

Este repositorio refleja el aprendizaje progresivo durante la formación en *Data Science* con **The Bridge**, combinando teoría, práctica y proyectos aplicados.  
El objetivo es mostrar evolución, organización y capacidad técnica en el manejo del ciclo completo de datos.
