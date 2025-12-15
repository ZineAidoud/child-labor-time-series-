- Analyse de l’évolution du travail des enfants (Séries temporelles)

Ce dépôt contient le projet de Master 1 Mathématiques et Data Science (Université de Haute-Alsace), portant sur l’analyse dynamique du travail des enfants dans le monde entre 2010 et 2023.

L’étude s’appuie sur des données harmonisées de l’Organisation Internationale du Travail (OIT) et utilise des méthodes de séries temporelles afin d’identifier les tendances, les ruptures et l’impact des crises mondiales.

- Contenu du dépôt

analyse_series_temporelles.ipynb
Notebook Python contenant l’intégralité du code :
nettoyage des données, visualisation et décomposition saisonnière (Statsmodels).

Rapport_Projet_M1.pdf
Rapport technique détaillé présentant la méthodologie, l’analyse et les résultats.

dataset_test_2.csv
Jeu de données utilisé pour l’analyse.

- Objectifs de l’étude

Identifier les tendances
Analyse de l’évolution globale et par sous-groupes (âge, sexe).

Détecter les ruptures temporelles
Étude de l’impact des événements mondiaux (ex. : pics observés en 2015 et 2022).

Analyser la scolarisation
Mise en évidence de la corrélation entre le travail des enfants et la déscolarisation.

- Méthodologie technique

Langage : Python 3

Bibliothèques principales :

Pandas : manipulation et nettoyage des données.

Statsmodels : décomposition de séries temporelles
(modèle additif : Tendance + Saisonnalité + Résidus).

Matplotlib / Seaborn : visualisation des données.

- Résultats marquants

Mise en évidence d’une tendance à la hausse du travail des enfants sur la période récente.

Les garçons et la tranche d’âge 15–17 ans sont les plus touchés.

Forte corrélation entre les périodes de crise et l’augmentation des abandons scolaires chez les enfants travailleurs.

git clone https://github.com/ZineAidoud/child-labor-time-series-.git

pip install -r requirements.txt

jupyter notebook analyse_series_temporelles.ipynb

👥 Auteurs

Hocine Rayane ARHAB

Zine Elabidine AIDOUD

Encadrante : Mme Suzy MADDAH

Projet réalisé dans le cadre du Master 1 Mathématiques et Data Science – Année universitaire 2024–2025
