# Análisis de Patrones Emocionales en Texto con NLP y Machine Learning

Este repositorio contiene un proyecto de análisis de sentimientos y emociones en texto en español utilizando técnicas de procesamiento de lenguaje natural (NLP), modelos de embeddings como BERT y modelos de clasificación tradicionales como SVM, KNN, Naive Bayes y Árboles de Decisión.

## Contenido
- Exploración y limpieza del dataset
- Preprocesamiento de texto (limpieza, tokenización, stopwords, lematización)
- Visualización (nubes de palabras, t-SNE, PCA)
- Generación de embeddings (TF-IDF y Transformers)
- Modelado con distintos clasificadores
- Evaluación con métricas de rendimiento y validación cruzada

## 🔧 Requisitos e instalación

### 1. Clonar el repositorio
```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
```

### 2. Crear un entorno virtual (opcional)
```bash
python -m venv venv
source venv/bin/activate  # en Linux/macOS
venv\Scripts\activate   # en Windows
```

### 3. Instalar dependencias
```bash
pip install -r requirements.txt
python -m spacy download es_core_news_sm
```

## 📂 Estructura esperada
- `Nuevo_Dataset_Patrones_Emocionales.csv` debe estar en el mismo directorio del script.

## 🚀 Ejecución
```bash
python copia_de_untitled2.py
```

## 📌 Funciones clave
- `limpiar_texto(texto)`: Limpieza básica del texto.
- `tokenizar(cell)`: Tokenización por palabra.
- `lemmatizar(text)`: Lematización con spaCy.
- `generar_embeddings_transformer(...)`: Embeddings con modelos de HuggingFace.
- `entrenar_y_evaluar_svm(...)`: Entrenamiento y métricas de SVM.
- `probar_modelo(texto)`: Predice la emoción de un texto.

## 📈 Visualizaciones
- Nubes de palabras por emoción
- Visualizaciones de embeddings: t-SNE y PCA
- Comparación gráfica de modelos y rendimiento

## 📚 Referencias
- Hugging Face: [dccuchile/bert-base-spanish-wwm-cased](https://huggingface.co/dccuchile/bert-base-spanish-wwm-cased)
- spaCy: `es_core_news_sm`
