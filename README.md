# RAG Chatbot LLaMa 2 avec Chroma et SQuAD

Ce projet implémente un chatbot utilisant le modèle **LLaMa 2** pour des tâches de **retrieval-augmented generation (RAG)**, combiné avec **ChromaDB** comme base de données vectorielle pour le stockage et la recherche d'informations. Le modèle est fine-tuné sur le dataset **SQuAD** afin d'améliorer sa capacité à répondre à des questions factuelles de manière précise et contextuelle.

## Fonctionnalités

- **RAG (Retrieval-Augmented Generation)** : Le chatbot génère des réponses en utilisant une combinaison de génération de texte et de récupération d'informations pertinentes depuis une base de données.
- **ChromaDB** : Base de données vectorielle utilisée pour stocker et rechercher des informations liées aux questions posées.
- **Fine-tuning de LLaMa 2** : Le modèle LLaMa 2 est fine-tuné sur le dataset SQuAD pour améliorer la précision des réponses dans un contexte de question-réponse.
- **Réponses précises et contextuelles** : Grâce à l'architecture RAG et à la recherche dans la base de données, le chatbot fournit des réponses détaillées et adaptées à chaque question.

## Prérequis

- Python 3.x
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
- [ChromaDB](https://www.trychroma.com/)
- PyTorch
- Datasets SQuAD

## Installation

1. Clonez ce repository :
   ```bash
   git clone https://github.com/OussamaNaya/Chatbot-LLaMa-2-RAG-avec-Chroma-et-SQuAD.git
