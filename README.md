# ghizlene.github.io
Portfolio personnel d'ingénieure junior IA

# 📊 Analyse de Sentiment sur Tweets Dépressifs | Sentiment Analysis on Depressive Tweets
## 🇫🇷 Description

Ce projet vise à construire un modèle d’analyse automatique des sentiments dans des tweets liés à la dépression.

Le notebook Colab effectue les étapes suivantes :

* 📥 Chargement et exploration d’un dataset de tweets dépressifs prétraités
* 🧹 Nettoyage et prétraitement des textes (minuscules, suppression des mentions, hashtags, URLs, ponctuation, stopwords, lemmatisation)
* 🧠 Analyse de polarité avec TextBlob pour créer des labels de sentiment (positif, négatif, neutre)
* 🔤 Vectorisation TF-IDF des textes
* 🤖 Entraînement d’un modèle de régression logistique
* 📈 Évaluation du modèle avec rapport de classification et matrice de confusion
* 💬 Tests de prédiction sur des exemples personnalisés

Ce projet est une base solide pour des applications de détection automatique d’émotions et peut être étendu à la surveillance de la santé mentale sur les réseaux sociaux.

---

## 🇬🇧 Description

This project aims to build an automatic sentiment analysis model on tweets related to depression.

The Colab notebook performs the following steps:

* 📥 Loading and exploring a preprocessed depressive tweets dataset
* 🧹 Text cleaning and preprocessing (lowercasing, removing mentions, hashtags, URLs, punctuation, stopwords, lemmatization)
* 🧠 Polarity analysis with TextBlob to create sentiment labels (positive, negative, neutral)
* 🔤 TF-IDF vectorization of texts
* 🤖 Training a logistic regression model
* 📈 Model evaluation with classification report and confusion matrix
* 💬 Prediction tests on custom examples

This project serves as a strong foundation for automatic emotion detection applications and can be extended for mental health monitoring on social media.

---

## 🇫🇷 Utilisation / Usage

1. Ouvrir le notebook dans [Google Colab](https://colab.research.google.com/)
2. Exécuter toutes les cellules dans l’ordre
3. Explorer les visualisations et les résultats d’évaluation
4. Modifier ou ajouter des phrases de test pour vérifier les prédictions

---

## 🇫🇷 Prérequis / Requirements

* Python 3.x
* Librairies Python :
  `pandas`, `numpy`, `scikit-learn`, `nltk`, `textblob`, `matplotlib`, `seaborn`, `wordcloud`

Installer via pip :

```bash
pip install pandas numpy scikit-learn nltk textblob matplotlib seaborn wordcloud
```

---

## 🇫🇷 Dataset

Chargé directement depuis ce dépôt public GitHub :
[https://github.com/peijoy/DetectDepressionInTwitterPosts](https://github.com/peijoy/DetectDepressionInTwitterPosts)

---

## 🇫🇷 Structure du projet / Project Structure

* `Sentiment_Analysis_Depressive_Tweets.ipynb` — Notebook principal
* `README.md` — Ce fichier

---

## 🇫🇷 Licence / License

À préciser selon ton choix (exemple : MIT License)

---

## 🇫🇷 Contact

Pour toute question ou suggestion, merci de me contacter : \[ton e-mail ou GitHub]

---

## 🇫🇷 Remarque importante / Disclaimer

*Ce projet est uniquement à des fins éducatives et ne remplace pas un avis professionnel en santé mentale.*
