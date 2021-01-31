# Fourmi de Langton

## A) Prérequis

- Une installation de JupyterHub
- Le module `ipythonblocks` [[Documentation](https://www.carnets.info/jupyter/ipythonblocks/)]

## B) Règles de l'automate :

- Si la case est Blanche, la fourmi avance et tourne de 90° vers la droite
- Si la case est Noire, la fourmi avance et tourne de 90° vers la gauche

## C) Exemple

-> Capture realisée après exécution de la fonction `fourmi_at(50,50,270,11500)`
![Exemple de la Fourmi de Langton](https://github.com/kurikawaii/automates_cellulaires/blob/main/Exemples/fourmi.png)

## D) Observation

La fourmi commence par tracer des motifs symétriques, puis cela devient plus chaotique avant de terminer par tracer une diagonale dans une direction. 

Pour creuser d'avantage : [Article Wikipédia](https://fr.wikipedia.org/wiki/Fourmi_de_Langton)