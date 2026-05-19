# 🤖 BOT de Ventas — RAG + Agentes + Mistral

Proyecto de Inteligencia Artificial que implementa un chatbot conversacional
para análisis de datos de ventas utilizando RAG, Agentes y Mistral AI.

## 📁 Estructura del Proyecto

| Archivo | Descripción |
|---|---|
| `1_normalizacion.ipynb` | Limpieza y normalización del dataset |
| `2_bot_rag_agente.ipynb` | BOT principal con RAG + Agentes + Mistral |
| `ventas_normalizado.csv` | Dataset limpio listo para usar |

## 🛠️ Tecnologías utilizadas

- **Mistral AI** — LLM y Embeddings
- **LangChain** — Framework de IA
- **LangGraph** — Agente ReAct
- **FAISS** — Base vectorial para RAG
- **Google Colab** — Entorno de ejecución
- **Python / Pandas** — Procesamiento de datos

## 🚀 ¿Cómo funciona?
Dataset CSV
↓
Normalización (Notebook 1)
↓
Conversión a documentos + Embeddings Mistral
↓
Base vectorial FAISS (RAG)
↓
Agente ReAct con Tools
↓
BOT conversacional en español
## 🔧 Herramientas del Agente

- `ventas_por_pais` — Total de ventas por país
- `top_clientes` — Ranking de mejores clientes
- `ventas_por_producto` — Ventas por línea de producto
- `ordenes_por_estado` — Conteo de órdenes por estado
- `resumen_general` — Resumen completo del dataset

## ⚙️ Configuración

1. Crear cuenta en [Mistral AI](https://console.mistral.ai)
2. Generar API Key
3. En Google Colab ir a **Secrets** y agregar:
   - Nombre: `bot-ventas`
   - Valor: `tu_api_key_de_mistral`
4. Ejecutar `1_normalizacion.ipynb` primero
5. Ejecutar `2_bot_rag_agente.ipynb`

## 💬 Ejemplos de preguntas al BOT
Dame un resumen general del dataset
¿Cuánto suman las ventas de USA?
Mostrame el top 3 de clientes
¿Cuántas órdenes están canceladas?
¿Cuál es el total de ventas de Classic Cars?

## 📊 Dataset

- **Fuente:** Kaggle — Sales Data Sample
- **Registros:** 2823 filas
- **Columnas:** 24 variables de ventas
