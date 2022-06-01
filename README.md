# Streamlit Demo

## Why Streamlit:
Le Pipeline classique de travail en Data Science est le suivant:

![Workflow_data_scientist](/assets/streamlit_1.png "Pipeline MLOPS")

Streamlit est une librairie python (on parle souvent de framework) qui permet de créer de très belles interfaces graphiques d’applications en très peu de temps.

Streamlit va agir comme une interface entre le langage Python et d’autres librairies \ langages (exemple  HTML, CSS, Javascript, etc).

A partir du moment où l’on va vouloir créer une interface graphique utilisateur on va pouvoir se servir de streamlit pour visuellement communiquer avec les différentes parties prenantes de l’entreprise.

## Généralités sur Streamlit:
Quelques possibilités avec streamlit:

![Fonctions de streamlit](/assets/streamlit_2.png)

## Installation de Streamlit:

Ce dont vous allez avoir besoin:
* Editeur de text
* Commande d’installation: 

``` python
Pip install streamlit 
#(pipenv install streamlit dans une environnement virtuel)
```

## Méthodologie de développement d’une application:

Une méthodologie de travail possible:

1. Design de la fenêtre de l’application

La première étape est le design de la fenêtre de l’application (voir ci-dessous).

![Visuel de l'application](/assets/streamlit_3.png)

→ Être imaginatif: Imaginer le ‘look’ de votre futur application (couleurs, dispositions, menus, contenu etc.)

## Design de l’architecture:

La deuxième étape **n’est pas l’écriture de lignes de code** mais le design de l’architecture de l’application.

Schématiser l’ensemble des fichiers et les relations entre ces derniers (design de l'architecture du répertoire du code).

*Ex:*
![Visuel de l'application](/assets/streamlit_4.png)

Une fois la fenêtre et l’architecture en tête, il est désormais plus facile d’écrire le code correspondant.


## Exploration de streamlit:
Go démo 👉

## Launch the demo:

1. Aller dans le répertoire app:

``` bash
# Change directory
cd app
```
2. lancer le script `app.py`:

``` python
# Run streamlit app
streamlit run app.py
```