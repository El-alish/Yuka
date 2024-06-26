# Yuka
Etude de cas sur YUKA

## Analyser le dataset de Yuka pour répondre à la problématique du client : "Comment savoir si un aliment est sain ou non ?"

## On fait une analyse du df :
 <img src="./Yuka 01.png" style="border-radius: 15px">

### Cherchons les valeurs manquantes et le pourcentage de remplissage des colonnes
 <img src="./Yuka 02.png" style="border-radius: 15px">

### Calcul des quantiles pour donner une idée du dataset
 <img src="./Yuka 03.png" style="border-radius: 15px">

### On décide désormais de supprimer des colonnes non pertinentes pour notre projet. Et on se concentre également sur la partie France.
 <img src="./Yuka 04.png" style="border-radius: 15px">

### Suppression de colonnes qui ont moins de 60% de valeurs non nulles. On réintègre tout dans un nouveau df (df_cleaned)
 <img src="./Yuka 05.png" style="border-radius: 15px">

### On sauvegarde ce nouveau DF dans un CSV. Le même procédé sera fait pour la partie USA.
 <img src="./Yuka 06.png" style="border-radius: 15px">

### On supprime les lignes dont les valeurs sont manquantes afin de conserver un dataset plus précis
 <img src="./Yuka 07.png" style="border-radius: 15px">

### Utilisation de Seaborn pour illsutrer la distribution des produits en France et aux USA
 <img src="./Yuka 09.png" style="border-radius: 15px">

### Graphique en barre pour illustrer les meilleurs produits par score de -15 a -1 ( plus le score est négatif, plus sain est le produit )
 <img src="./Yuka 10.png" style="border-radius: 15px">

### Meme graphique, cette fois-ci pour les produits aux USA ( ici on remarque que le meilleur score aux USA est de -10, contrairement à -15 en France )
 <img src="./Yuka 11.png" style="border-radius: 15px">

### Graphique pour mettre en parallèle les deux pays et leurs produits considérés comme sain, par Yuka 
 <img src="./Yuka 12.png" style="border-radius: 15px">
