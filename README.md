# Fine-tuning de modèles multilingues auto-supervisés pour la transcription de la parole en langue camerounaise : le Yemba

## 📌 Contexte du projet
Ce projet s’inscrit dans le cadre du hackathon **Aurore de la Recherche**, organisé à l’**Université de Yaoundé I**.  
L’objectif principal du hackathon était de promouvoir l’utilisation de l’intelligence artificielle et des méthodes modernes d’apprentissage automatique pour la valorisation des **langues locales camerounaises**, en particulier dans le domaine du traitement automatique de la parole.

## 🎯 Objectif
La tâche assignée consistait à réaliser le **fine-tuning d’un modèle multilingue auto-supervisé** pour la **transcription automatique de la parole** en langue **Yemba**, une langue camerounaise peu dotée en ressources numériques.

Plus précisément, il s’agissait de :
- sélectionner un modèle multilingue adapté à la reconnaissance automatique de la parole (ASR),
- l’adapter (fine-tuning) à un jeu de données spécifique au Yemba,
- évaluer sa capacité à transcrire correctement la parole en Yemba.

## 📊 Jeu de données
Le projet utilise le jeu de données **YembaEGRA**, disponible publiquement sur Mendeley Data :

🔗 **Lien du dataset** :  
https://data.mendeley.com/datasets/74p9d5frg3/1

Ce corpus contient des enregistrements audio annotés en langue Yemba, conçus pour des tâches de reconnaissance et de transcription de la parole.

## 🧠 Modèle utilisé
Après plusieurs expérimentations avec différents modèles multilingues, nous avons retenu le modèle **Whisper**, développé par OpenAI.

Les raisons de ce choix incluent :
- sa robustesse sur des langues peu dotées,
- sa capacité à gérer des données multilingues,
- ses performances élevées en reconnaissance automatique de la parole,
- sa facilité d’adaptation par fine-tuning.

## ⚙️ Méthodologie
Le travail présenté dans ce projet comprend :
1. La préparation et le prétraitement du jeu de données YembaEGRA  
2. L’adaptation du modèle Whisper au corpus Yemba  
3. Le fine-tuning du modèle sur les données audio annotées  
4. L’analyse des résultats obtenus en transcription automatique  

## 📒 Contenu du dépôt
Ce dépôt contient principalement :
- un **notebook Jupyter** détaillant toutes les étapes du travail,
- le code de préparation des données,
- les scripts de fine-tuning du modèle Whisper,
- ainsi que les analyses et résultats obtenus.


---

**Auteur :** Kamga Mawabo Ines, Nono Ngansoap Nahomie  

