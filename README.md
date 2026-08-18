# ⚡ Potencial Energético Renovable de Antioquia

## 📌 Descripción

Este proyecto analiza el **potencial energético renovable del departamento de Antioquia, Colombia**, utilizando información histórica y datos disponibles desde **2016 hasta la actualidad**.

El objetivo es explorar y visualizar el comportamiento de diferentes fuentes de energía renovable, identificar tendencias y facilitar la interpretación de la información mediante herramientas de análisis de datos y visualización.

El proyecto fue desarrollado como parte de un proceso de formación en **análisis de datos con Python**.

---

## 🎯 Objetivos

* Analizar la evolución del potencial energético renovable de Antioquia.
* Explorar diferentes fuentes de generación y aprovechamiento energético.
* Identificar tendencias y patrones presentes en los datos.
* Transformar y limpiar los datos para facilitar su análisis.
* Construir visualizaciones que permitan interpretar los resultados.
* Presentar los principales hallazgos de manera clara y accesible.

---

## 🔋 Fuentes de energía analizadas

El proyecto contempla diferentes fuentes de energía renovable:

### ☀️ Energía solar

* Radiación solar.
* Evolución y distribución del recurso solar.
* Capacidad instalada asociada a generación solar.

### 💨 Energía eólica

* Análisis del recurso eólico disponible.
* Comportamiento y distribución de los datos relacionados con el potencial eólico.

### 💧 Energía hidráulica

* Análisis de la generación y el potencial hidroeléctrico.
* Comportamiento histórico de la fuente hidráulica.

### 🌱 Biomasa

* Exploración del potencial energético asociado a recursos de biomasa.

---

## 🧪 Metodología

El desarrollo del proyecto sigue un flujo general de análisis de datos:

1. **Recolección de información**

   * Obtención y organización de los datos utilizados en el estudio.

2. **Limpieza y preparación**

   * Tratamiento de valores faltantes.
   * Corrección y transformación de variables.
   * Preparación de los datos para el análisis.

3. **Análisis exploratorio**

   * Identificación de tendencias.
   * Comparación entre fuentes de energía.
   * Análisis temporal y geográfico cuando la información disponible lo permite.

4. **Visualización**

   * Elaboración de gráficos y representaciones visuales.
   * Comparación de resultados.
   * Presentación de los principales patrones encontrados.

5. **Interpretación**

   * Análisis de los resultados obtenidos.
   * Identificación de hallazgos relevantes sobre el potencial energético renovable de Antioquia.

---

## 🛠️ Tecnologías utilizadas

El proyecto está desarrollado principalmente con **Python**.

Entre las principales herramientas y librerías utilizadas se encuentran:

* 🐍 Python
* 🐼 Pandas
* 📊 Matplotlib
* 📈 Seaborn
* 🎨 Streamlit
* 🔢 NumPy

Las dependencias necesarias para ejecutar el proyecto se encuentran en:

```text
requirements.txt
```

---

## 📁 Estructura del proyecto

```text
Potencial_energia/
│
├── .devcontainer/          # Configuración del entorno de desarrollo
├── .streamlit/             # Configuración de Streamlit
│
├── data/                   # Datos utilizados en el proyecto
├── media/                  # Recursos multimedia y visualizaciones
├── pages/                  # Páginas adicionales de la aplicación Streamlit
│
├── app.py                  # Aplicación principal
├── utilidades.py           # Funciones auxiliares
├── retomando.py            # Script auxiliar
│
├── requirements.txt        # Dependencias del proyecto
├── Informe ejecutivo.pdf   # Informe con los resultados del proyecto
├── .gitignore              # Archivos excluidos del control de versiones
└── README.md               # Documentación del proyecto
```

---

## 🚀 Instalación y ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/dhduquea/Potencial_energia.git
```

Ingresar a la carpeta:

```bash
cd Potencial_energia
```

### 2. Crear el entorno virtual

En Windows:

```bash
python -m venv .venv
```

Activar el entorno:

```powershell
.\.venv\Scripts\Activate.ps1
```

En macOS/Linux:

```bash
source .venv/bin/activate
```

### 3. Instalar las dependencias

```bash
pip install -r requirements.txt
```

### 4. Ejecutar la aplicación

El proyecto cuenta con una aplicación desarrollada con Streamlit. Para ejecutarla:

```bash
streamlit run app.py
```

Una vez iniciada, Streamlit proporcionará una dirección local desde la cual se podrá consultar la aplicación y explorar los resultados.

---

## 📊 Resultados

El proyecto permite explorar información relacionada con el potencial energético renovable de Antioquia mediante diferentes visualizaciones y análisis.

Entre los principales aspectos estudiados se encuentran:

* Evolución temporal de las fuentes de energía.
* Comparación entre diferentes fuentes renovables.
* Comportamiento de la radiación solar.
* Capacidad instalada.
* Indicadores relacionados con generación y potencial energético.
* Distribución de los recursos energéticos disponibles.

Los resultados detallados y las conclusiones del estudio se encuentran en el documento:

📄 **[Informe ejecutivo](./Informe%20ejecutivo.pdf)**

---

## 📚 Datos y fuentes

Los datos utilizados en el proyecto corresponden a información relacionada con el sector energético y el potencial de recursos renovables de Antioquia.

Para una correcta interpretación de los resultados, se recomienda consultar las fuentes originales y la documentación asociada a los conjuntos de datos utilizados.

---

## 👤 Autor

**David Duque**

Proyecto desarrollado como parte del proceso de formación en **Análisis de Datos — Talento Tech**.

---

## 📄 Licencia

Este proyecto fue desarrollado con fines **académicos y educativos**.

---

## ⭐ Sobre el proyecto

Este repositorio reúne el código, los datos, las visualizaciones y los resultados utilizados para estudiar el potencial energético renovable de Antioquia.

El proyecto puede continuar evolucionando mediante la incorporación de nuevos datos, indicadores, fuentes de energía y herramientas de análisis.

