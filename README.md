# API Gallica

## Démonstration #1 : *Les trois mousquetaires* ([vidéo](https://www.youtube.com/watch?v=SF0Yx0Tg8vA))
Introduction à l'utilisation des API Gallica :
- API de requêtage SRU du moteur d'indexation de Gallica

**Ouvrir le notebook avec [nbviewer](https://nbviewer.jupyter.org/github/Malichot/API/blob/main/Notebooks_demos/API_Gallica_SRU.ipynb).**

## Démonstration #2 : Titanic ([vidéo](https://www.youtube.com/watch?v=ukBr7qUZvww))
Introduction à l'utilisation des API Gallica :
- API de requêtage SRU du moteur d'indexation de Gallica
- API de facettage des résultats de la recherche
- API d'exploitation du calendrier des périodiques
- API d'accès aux occurrences de recherche
- API IIIF d'accès aux images des documents
 
**Ouvrir le notebook avec [nbviewer](https://nbviewer.jupyter.org/github/Malichot/API/blob/main/Notebooks_demos/API_Gallica_Titanic.ipynb)**

## Démonstration #2 : Maupassant 

### Notebook 1-Recuperation-OCR (R)

Introduction à l'utilisation de l'API Gallica pour la récupération des OCR :
- Recherche avancée dans Gallica.
- Récupération des résultats de toutes les pages.
- Récupération des métadonnées.
- Transformation en dataframe.
- Filtrage par un taux de nqa > 80 (nqa : taux   OCR   corrigé × coefficient d’étalonnage (= moyenne de qualité de toutes les pages)).
- Récupération de l'OCR.

### Notebook 2-Analyse-visualisation (R)

Exemples de quelques analyses simples menées sur les OCR récupérés :
- Nettoyage des données (expressions régulières).
- Analyse de certaines métadonnées (date, contributeurs).
- Tokénisation et fréquence des mots dans le corpus, fréquence absolue et relative (barplot + wordcloud).
- Implémentation de stopwords.
- Statistiques descriptives (nombre de mots par oeuvre, graphe de dispersion, boxplot).
