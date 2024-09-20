# clap_ai_RAG

## Information de projet

L'architecture RAG pour le projet CLAP combine un modèle de génération de texte avec un module de recherche.
🚧

📁 [Repository](https://github.com/clap-esp/clap_ai_RAG)  
📁 [Mirror pour le changelog](https://github.com/EpitechMscProPromo2025/T-AIA-901-NAN_3/clap_ai_RAG)

### Contribuer

-> Guide de [contribution](CONTRIBUTING.md)

## Fonctionnalités

🚧 modules en construction ...

1. Module [Speech to Text](#un-module-speech-to-text)
2. Module [NLP (Natural Language Processing)](#un-module-de-nlp)
3. Module [Retriever](#un-module-de-retriever)

## Architerture RAG
🚧


## Specifications

#### 📦 Un module Speech to Text

- Extrait l'audio et lit la piste
- Retourne un str

```
# Algo - Transcription
return : {}
```

#### 📦 Un module de NLP

...🚧

#### 📦 Un module de Retriever

...🚧

## Dataset

...🚧


## Prerequis

- Python ≥ 3.11
- Poetry -> [install](https://python-poetry.org/docs/#installation)

## Setup

```bash
poetry install
poetry shell
cd aia-script/2_module_NLP/
poetry run script-NLP.py
```

## Configuration des secrets

Dupliquez le fichier `env.example` et renommez la copie en `.env`. Ce fichier contient les secrets (clé d'API). Il ne doit jamais être push sur le repo.

## Lint

Lancer le script suivant pour lancer pylint  
(🕶 pylint est basé sur les normes PEP 8 et bien +)

```bash
./lint.sh
```
