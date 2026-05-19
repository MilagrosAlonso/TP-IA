# TP-IA - Chatbot Inteligente con RAG y Mistral Small

## Descripción del Proyecto

Este proyecto consiste en el desarrollo de un chatbot inteligente capaz de responder preguntas utilizando información contenida dentro de un dataset previamente cargado.

El sistema fue desarrollado en Google Colab utilizando técnicas de Inteligencia Artificial y procesamiento de lenguaje natural (NLP). El objetivo principal es permitir que el usuario interactúe con el chatbot realizando consultas relacionadas específicamente con los datos proporcionados al sistema.

El chatbot analiza la pregunta del usuario, busca información relevante dentro del dataset y genera respuestas coherentes y contextualizadas.

---

## Objetivo

Desarrollar un asistente conversacional que:

- Responda preguntas de manera automática.
- Utilice información almacenada en un dataset.
- Genere respuestas precisas y contextualizadas.
- Implemente modelos modernos de lenguaje.
- Facilite la interacción entre usuarios y datos mediante IA.

---

## Tecnologías Utilizadas

- Python
- Google Colab
- NLP (Procesamiento de Lenguaje Natural)
- RAG (Retrieval-Augmented Generation)
- Modelo Mistral Small
- Pandas
- LangChain
- Embeddings

---

## ¿Qué es RAG?

RAG (Retrieval-Augmented Generation) es una técnica que combina:

1. Recuperación de información desde una base de datos o dataset.
2. Generación de respuestas mediante un modelo de lenguaje.

Gracias a esto, el chatbot puede responder utilizando información específica del dataset cargado y no solamente conocimiento general del modelo.

---

## Modelo Utilizado: Mistral Small

Para este proyecto se seleccionó el modelo **Mistral Small** debido a sus excelentes capacidades en tareas conversacionales y de comprensión de texto.

### Motivos de la elección

#### 1. Buen rendimiento en procesamiento de lenguaje natural
Mistral Small posee una gran capacidad para interpretar preguntas y generar respuestas coherentes y naturales.

#### 2. Rapidez de respuesta
El modelo ofrece tiempos de respuesta rápidos, algo importante para la experiencia del usuario en un chatbot interactivo.

#### 3. Menor consumo de recursos
Comparado con modelos más grandes, Mistral Small requiere menos memoria y procesamiento, permitiendo ejecutarlo de forma más eficiente en entornos como Google Colab.

#### 4. Excelente relación calidad/rendimiento
Ofrece resultados muy buenos sin necesidad de utilizar modelos extremadamente pesados o costosos.

#### 5. Ideal para proyectos académicos y prototipos
Su equilibrio entre velocidad, precisión y eficiencia lo convierte en una excelente opción para trabajos prácticos y proyectos educativos.

---

## Funcionamiento General

1. Se carga un dataset con información específica.
2. El sistema procesa y vectoriza los datos.
3. El usuario realiza preguntas al chatbot.
4. El modelo busca información relevante.
5. Se genera una respuesta basada en el contenido del dataset.

---

## Ejemplo de Uso

Usuario:
> ¿Qué información contiene el dataset?

Chatbot:
> El dataset contiene información relacionada con ...

---

## Conclusión

Este proyecto demuestra cómo la Inteligencia Artificial puede utilizarse para crear asistentes conversacionales capaces de responder preguntas utilizando información personalizada.

La implementación de RAG junto con el modelo Mistral Small permitió desarrollar un chatbot eficiente, rápido y capaz de generar respuestas contextualizadas de manera precisa.

---

## Autor

Milagros Alonso
