# BOT de Ventas — Agente Pandas + RAG + Mistral

Asistente inteligente para análisis de datos de ventas mediante **Agente de Pandas**, **RAG (Mistral AI + FAISS)** y una interfaz de chat interactiva.

## 🚀 Características
* **Análisis Conversacional:** Consultas en lenguaje natural sobre datasets (CSV).
* **RAG Contextual:** Recuperación inteligente de datos con embeddings de Mistral.
* **Interfaz Visual:** Chat integrado en Jupyter/Colab mediante `ipywidgets`.
* **Validación:** Panel automático de gráficos para verificar precisión y cobertura.

## 🛠 Instalación
```bash
pip install langchain==0.3.25 langchain-core==0.3.63 langchain-community==0.3.24 langchain-mistralai==0.2.10 langchain-experimental==0.3.4 faiss-cpu==1.11.0 tabulate
