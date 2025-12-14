# 📘 Procesamiento de Lenguaje Natural

## 📌 Descripción

Este repositorio contiene implementaciones y experimentos relacionados con **Procesamiento de Lenguaje Natural (NLP)**, desarrollados en el marco de trabajos prácticos académicos y exploración personal en el área de **Inteligencia Artificial**.

El proyecto está abordado desde una **perspectiva de ingeniería**, priorizando la claridad conceptual, la correcta implementación de modelos y la evaluación rigurosa de resultados, utilizando Python y PyTorch.

---

## 🎯 Objetivos

- Aplicar técnicas fundamentales de NLP como limpieza de texto, tokenización y vectorización.
- Entrenar y evaluar modelos supervisados para tareas de clasificación de texto.
- Explorar enfoques basados en *deep learning* para el procesamiento del lenguaje.
- Documentar experimentos de forma clara y reproducible para uso académico y profesional.

---

## 🗂 Estructura del Repositorio

```
ProcesamientoLenguageNatural/
├── README.md
├── README.es.md
├── requirements.txt
├── torch_helpers.py
├── spa-eng/
│   └── spa.txt
├── TP1/
│   └── Desafio_1.ipynb
├── TP2/
│   ├── tp2.ipynb
│   └── songs_dataset/
├── TP3/
│   └── TP3.ipynb
└── TP4/
    ├── Tp4.ipynb
    ├── tp4.py
    └── graphics/
```

### Contenido

- **TP1/** - Introducción a word embeddings y vectorización
- **TP2/** - Modelos de lenguaje y generación de texto
- **TP3/** - Arquitecturas recurrentes (RNN/LSTM) para clasificación
- **TP4/** - Seq2Seq con atención y Transformers para traducción automática
- **torch_helpers.py** - Utilidades para tokenización, padding y entrenamiento
- **spa-eng/** - Dataset Tatoeba de traducción español-inglés

---

## ⚙️ Instalación y Configuración

### Requisitos

- Python 3.8 o superior  
- Jupyter Notebook  
- PyTorch  
- NumPy, Pandas  

### Clonar el repositorio

```bash
git clone https://github.com/sbiagiola/ProcesamientoLenguageNatural.git
cd ProcesamientoLenguageNatural
```

### (Opcional) Crear un entorno virtual

```bash
python3 -m venv .venv
source .venv/bin/activate    # Linux / macOS
.venv\Scripts\activate       # Windows
```

### Instalar dependencias

```bash
pip install -r requirements.txt
```

## ▶️ Uso

### Iniciar Jupyter Notebook

```bash
jupyter notebook
```

### Ejecutar trabajos prácticos

1. Navegar a la carpeta del TP deseado (TP1/, TP2/, TP3/, TP4/)
2. Abrir el notebook correspondiente
3. Ejecutar las celdas en orden

### Estructura de cada notebook

Cada trabajo práctico incluye:

- **Introducción**: Contexto y objetivos del ejercicio
- **Preparación de datos**: Carga, limpieza y tokenización
- **Implementación**: Definición de arquitecturas y modelos
- **Entrenamiento**: Configuración de hiperparámetros y optimización
- **Evaluación**: Métricas de rendimiento y análisis de resultados
- **Conclusiones**: Interpretación y lecciones aprendidas

## 🧪 Temas Abordados

### TP1 - Word Embeddings
- Vectorización de texto (Bag of Words, TF-IDF)
- Word2Vec y embeddings pre-entrenados
- Análisis de similitud semántica

### TP2 - Modelos de Lenguaje
- N-gramas y predicción de palabras
- Generación de texto
- Clasificación de textos por autor

### TP3 - Redes Recurrentes
- Arquitecturas RNN y LSTM
- Clasificación de secuencias
- Manejo de secuencias de longitud variable

### TP4 - Seq2Seq y Transformers
- Traducción automática inglés-español
- LSTM bidireccional con atención Bahdanau
- Arquitectura Transformer
- Comparación de modelos y análisis de rendimiento

## 🧰 Tecnologías Utilizadas

| Tecnología | Versión | Descripción |
|------------|---------|-------------|
| Python | 3.8+ | Lenguaje principal |
| PyTorch | 2.x | Framework de deep learning |
| Jupyter Notebook | - | Entorno de experimentación interactiva |
| NumPy | - | Operaciones numéricas y matriciales |
| Pandas | - | Manipulación y análisis de datos |
| Matplotlib / Seaborn | - | Visualización de resultados |
| NLTK / spaCy | - | Herramientas de procesamiento de texto |

## 📫 Contribuciones

Este es un repositorio académico, pero las contribuciones son bienvenidas:

1. **Fork** el repositorio
2. Crea una **rama** para tu feature (`git checkout -b feature/mejora`)
3. **Commit** tus cambios (`git commit -m 'Agregar nueva funcionalidad'`)
4. **Push** a la rama (`git push origin feature/mejora`)
5. Abre un **Pull Request**

También podés abrir un **issue** para reportar errores o sugerir mejoras.

---

## 📄 Licencia

Este proyecto se distribuye bajo licencia **MIT**, permitiendo su uso académico y comercial con la debida atribución.

---

## 👤 Autor

**Sebastián Biagiola**  
Ingeniero Electrónico — Especialización en Inteligencia Artificial  
Universidad Nacional de Córdoba

🔗 [GitHub](https://github.com/sbiagiola)

---

## 🌟 Agradecimientos

- Cátedra de Procesamiento de Lenguaje Natural - UNC
- Datasets: Tatoeba Project, Song Lyrics
- Pre-trained embeddings: GloVe (Stanford NLP)
