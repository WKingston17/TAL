# TAL - Traitement Automatique du Langage pour l'Analyse Financière

Ce dépôt contient une application d'analyse de textes financiers utilisant des techniques avancées de traitement du langage naturel (NLP).

## Structure du Projet

- **Notebook/** - Contient les notebooks Jupyter utilisés pour le développement et les tests
  - **Final Notebooks/** - Notebooks finalisés pour l'analyse de sentiment et la reconnaissance d'entités nommées
  - **Test (Other Analysis)/** - Notebooks d'expérimentation additionnels
  - **Projet_Financial_Analyse_Using_NLP/** - Application web principale pour l'analyse financière

## Fonctionnalités Principales

L'application intègre trois modèles BERT fine-tunés spécialisés dans l'analyse financière :
- **Analyse de sentiment** (3 classes : Positif, Neutre, Négatif)
- **Extraction de relation** (29 classes de relations financières)
- **Reconnaissance des entités nommées** (4 classes : PER, ORG, LOC, MISC)

## Interface Utilisateur

- Design responsive et moderne
- Mode clair/sombre pour un confort visuel optimal
- Navigation simple et intuitive
- Visualisation des résultats avec graphiques interactifs

## Modèles Utilisés

- `Wilbiz/financial-sentiment` - Analyse de sentiment financier
- `Wilbiz/financial-ner` - Reconnaissance d'entités nommées financières
- Modèle BERT personnalisé pour l'extraction de relations financières

## Prérequis

- Python 3.11 ou supérieur
- PyTorch 1.7+
- Transformers (Hugging Face) 4.0+
- Flask 2.0+
- Autres dépendances listées dans `requirements.txt`

## Installation et Utilisation

1. Clonez ce dépôt
2. Créez un environnement virtuel (recommandé)
3. Installez les dépendances : `pip install -r requirements.txt`
4. Lancez l'application : `python app.py`
5. Accédez à l'interface web : `http://127.0.0.1:5000`

## Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
1. Fork le projet
2. Créer une branche pour votre fonctionnalité
3. Commiter vos changements
4. Pousser vers la branche
5. Ouvrir une Pull Request

## Licence

Ce projet est sous licence MIT.