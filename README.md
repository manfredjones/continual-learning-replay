# Aprendizaje Continuo para la Simplificación de Texto en Español

Esta investigación explora el uso de técnicas de **Aprendizaje Continuo (Continual Learning)** para mitigar el *olvido catastrófico* al entrenar modelos de lenguaje de forma secuencial. Se utiliza el modelo **T5-small** y la técnica de **Replay** para mantener el rendimiento en tareas previamente aprendidas.

## 🧠 Descripción del proyecto

- 🧾 Modelo base: T5-small (Transformers de HuggingFace)  
- 🗂️ Tareas:
  - A: Simplificación automática de texto en español
  - B: Traducción como tarea NLP relacionada
- 🛠️ Técnica aplicada: Replay (almacenamiento y reutilización de ejemplos anteriores)
- 📊 Métricas utilizadas:
  - ROUGE para simplificación
  - BLEU para traducción

## 🧪 Herramientas

- Python, PyTorch, HuggingFace
- Jupyter Notebook (compatible con Google Colab)
- Google Drive para almacenamiento de modelos y datos

## 📁 Archivos

- `Forgetting_Mitigation_with_Replay.ipynb`: Notebook principal con entrenamiento y evaluación

- 📄 Reporte de investigación (PDF): [Mitigación del Olvido mediante Replay.pdf](https://github.com/user-attachments/files/20990721/Mitigacion.del.Olvido.mediante.Replay.pdf)

- 📘 [Ver en Colab](https://colab.research.google.com/drive/1-JQLwsWq12xFTrBg0jpH2B0Uckzi0_iB?usp=sharing)


## 🔎 Resultados

El uso de Replay ayuda a reducir significativamente el olvido catastrófico al incorporar nuevas tareas, manteniendo el rendimiento en tareas anteriores.



