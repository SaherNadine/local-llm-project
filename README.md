# RAG Ollama + LangChain

Ce projet montre un **pipeline Retrieval-Augmented Generation (RAG)** utilisant **Ollama** pour les LLM locaux et **LangChain** pour la récupération et le traitement des documents.

## Fonctionnalités
- Charger et découper de grands documents en chunks
- Créer des embeddings avec OllamaEmbeddings
- Stocker et rechercher des vecteurs avec Chroma
- Récupérer les documents pertinents et générer des réponses contextualisées
- Intégration optionnelle d’agents pour combiner plusieurs outils et décisions

## Prérequis
- Python 3.10 ou supérieur
- Ollama installé et configuré avec un modèle LLaMA (ex : `llama3.1:8b`)
- Git

## Installation
1. Cloner le dépôt :
```bash
git clone https://github.com/ton_nom_utilisateur/nom_du_depot.git
cd nom_du_depot
