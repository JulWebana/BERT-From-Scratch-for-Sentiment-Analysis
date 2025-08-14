# BERT-From-Scratch-for-Sentiment-Analysis

> 📌 **Note** : Ce dépôt est un **fork** du projet original [BERT-From-Scratch-for-Sentiment-Analysis](https://github.com/reouvenzana/BERT-From-Scratch-for-Sentiment-Analysis), réalisé en **groupe**. 
>  

---

## 🎬 Introduction  

L’analyse de sentiment est devenue un domaine de plus en plus important dans le traitement automatique du langage naturel (NLP), offrant des informations précieuses sur l’opinion publique dans divers secteurs.  

En dernière année de Master Data Science and Artificial Intelligence, nous avons entrepris un projet portant sur **l’analyse de sentiment des critiques d’utilisateurs issues de Rotten Tomatoes**, un site populaire d’agrégation de critiques de films.  
L’objectif de ce projet est de classer les critiques comme étant **positives** ou **négatives**, afin de fournir une compréhension approfondie des réactions du public vis-à-vis des films.  

En utilisant des techniques avancées d’apprentissage automatique — en particulier l’architecture **BERT** — nous avons cherché à capturer les nuances d’expression et les indices contextuels présents dans les critiques, afin d’obtenir des prédictions de sentiment plus précises.  

**Membres de l’équipe :**  
- Reouven Zana  
- Julien Webana  AGA
- Rhosane Silva dos Santos  
- Gilles Degue  

---

🚀 **Fonctionnalités :**

```
- Prétraitement et nettoyage des données textuelles
- Construction et entraînement d’un modèle BERT from scratch
- Évaluation avec métriques de classification (accuracy, F1-score…)
- Inférence sur de nouveaux textes
- Visualisation des performances avec courbes et graphiques

```

---

🛠️ **Technologies utilisées :**

```
- Langage : Python
- NLP & Deep Learning : PyTorch, Transformers (ou implémentation custom selon le repo)
- Traitement des données : pandas, NumPy
- Visualisation : Matplotlib, Seaborn
- Scripts :
  - 🎯 `train.py` → Entraînement du modèle  
  - 🔍 `inference.py` → Prédictions sur nouveaux échantillons  
  - 📊 `plot.py` → Visualisation des résultats

```
---

## 📂 Structure du projet  

```bash
BERT-From-Scratch-for-Sentiment-Analysis/
│
├── data/ # Jeux de données
├── models/ # Modèles sauvegardés
├── scripts/ # Scripts utilitaires
│       - train.py → Script d’entraînement
│       - inference.py → Script de prédiction
│       - plot.py → Visualisation des métriques
└── README.md

```


---

## 🚀 Exécution du projet  



1️⃣ **Cloner le dépôt**

```bash
git clone https://github.com/JulWebana/BERT-From-Scratch-for-Sentiment-Analysis.git
cd BERT-From-Scratch-for-Sentiment-Analysis

```

---


2️⃣ Installer les dépendances

```
pip install -r requirements.txt

```
---

3️⃣ Entraîner le modèle

```
python train.py

```

---

4️⃣ Faire une prédiction

```
python inference.py --text "I love this product!"

```

---


📄 Licence
```
Ce projet est sous licence MIT – utilisation libre et modification autorisée.

```


---
