# modelo_clasificacion_NLP

## Proyecto 1: Clasificación Ética de Notas Clínicas (NLP)

### Descripción General:
* Este proyecto aborda la clasificación de notas clínicas simuladas para la detección temprana de afecciones por gravedad (leve/moderado/severo). El foco principal no solo está en la precisión predictiva, sino en la evaluación y mitigación de sesgos algorítmicos por variables sensibles (como género o rango etario), asegurando un enfoque ético en la IA aplicada a la salud.

### Objetivos del Proyecto:
* Desarrollar y comparar modelos de NLP (Naive Bayes y BERT) para clasificar textos médicos.
* Implementar un pipeline de preprocesamiento robusto (tokenización, lematización, TF-IDF, Word Embeddings).
* Evaluar el rendimiento predictivo utilizando métricas de clasificación por clase (Precision, Recall, F1-score).
* Realizar una evaluación estratificada de sesgos y proponer estrategias de mitigación.
* Asegurar la explicabilidad del modelo final mediante herramientas como LIME o SHAP, complementado con una reflexión ética documentada.

### Tecnologías Clave:
* Lenguaje Python
* NLP & ML scikit-learn, nltk, spacy, transformers (BERT)
* Análisis pandas, numpy
* Explicabilidad SHAP
* Deep Learning	torch

### Características Destacadas:
* Doble Enfoque de Modelado: Comparación directa entre un modelo tradicional (Multinomial Naive Bayes) y una arquitectura de vanguardia (BERT base).
* Gestión de Sesgos: Implementación de una metodología para la evaluación de sesgos por género y edad, generando un informe detallado con propuestas de mitigación.
* Transparencia (XAI): Uso de técnicas de explicabilidad (LIME/SHAP) para justificar las predicciones y entender la lógica del modelo.

### Reflexión: Desafíos y Aprendizaje:
* Este proyecto demostró la complejidad de un pipeline de clasificación de texto clínico, y sirvió como un laboratorio práctico de ética en IA. El desafío técnico de integrar modelos avanzados (BERT) con la necesidad de transparencia (SHAP) fue crucial. El principal aprendizaje fue que, si bien los resultados en datasets simulados pueden ser altos, el verdadero valor reside en el proceso de consideración ética y la justificación de cada paso técnico, asegurando que el sistema sea justo antes de ser desplegado en un contexto médico real.

[Ir al Código en Colab] → https://colab.research.google.com/drive/16WHdpX1a2nxlCc3s5IB5Y6vLwUV94khU?usp=sharing
