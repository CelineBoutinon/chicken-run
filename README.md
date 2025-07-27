![logo](https://github.com/CelineBoutinon/chicken-run/assets/143210563/4ee62da4-0ec7-4a96-8a34-c92366b12c1e)



# REALISER UNE ETUDE DE MARCHE AVEC PYTHON

Projet realisé en mai 2023 dans le cadre de ma formation Data Analyst avec l'ENSAE-ENSAI Formation Continue (Cepe)/OpenClassrooms.

## Objectif du projet

La Poule qui Chante est une entreprise française d’agroalimentaire specialisée dans la production de poulet qui souhaite se développer à l'international ; aucun pays particulier ni aucun continent ne sont pour le moment choisis, et l'objectif du projet est de proposer une première analyse des groupements de pays que l’entreprise pourra cibler pour exporter ses poulets en partant des données de la FAO (Food and Agriculture Organization), auxquelles on joindra les critères de l’analyse PESTEL et toutes les données en open data nécessaires pour l'analyse, qui devra comporter:
* une classification ascendante hiérarchique, avec un dendrogramme comme visualisation ;
* un clustering utilisant la méthode des k-means et analysant les centroïdes des classes;
* une Analyse en Composantes Principales; et
* une présentation qui récapitule le contexte, vulgarise la démarche et présente les résultats et recommandations concernant le groupe de pays-cibles.



## Liste des dossiers & fichiers

* **dossiers :**
  - **donnees-brutes :** fichiers téléchargés depuis les sources (format .csv) 
  - **donnees-nettoyees :** fichier de données retraité avec notebook_1.ipynb prêt à uploader pour les analyses dans notebook_2.ipynb
  - **market-intel :** ensemble de fichiers .pdf donnant une vision d'ensemble du marché national et international du poulet français


* **fichiers :**
	- **notebook_1.ipynb :** code Python permettant l'import des fichiers .xlsx, leur nettoyage et la production d'un fichier unique "clean" et complet
	- **notebook_2.ipynb :** code Python pour l'ACP et le clustering des pays
	- **presentation.pdf:** diapositives de présentation du projet
  - **presentation_notes.pdf :** notes d’accompagnement des diapositives de présentation du projet
  - **functions.py :** fichier de fonctions auxquelles les notebooks Jupyter font appel


## Compétences développées

* Explorer des données pour synthétiser des variables
* Effectuer un clustering simple



## Langages & software

* Python 3.9.13
  * matplotlib 3.6.2
  * missingno 0.5.1
  * numpy 1.24.1
  * pandas 1.5.2
  * plotly 5.14.1
  * scikit-learn 1.2.2
  * scipy 1.10.0
  * seaborn 0.12.2
  * statsmodels 0.13.5
 

* Jupyter Notebook 6.4.12








