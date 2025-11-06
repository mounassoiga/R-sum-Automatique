## 🧾  Résumé Automatique (Python)

Ce projet implémente un **système de résumé automatique extractif** en Python.  
Le système sélectionne les phrases les plus importantes d’un texte en se basant sur la **fréquence des mots**, après une étape de **lemmatisation**.

---

## 🚀 Fonctionnalités
- Lecture d’un fichier texte (`TexteATraiter.txt`)
- Nettoyage du texte et suppression des stopwords
- Lemmatisation avec **SpaCy**
- Calcul de la fréquence des mots
- Attribution d’un score à chaque phrase
- Extraction automatique des **5 phrases les plus pertinentes**

---

## 🧠 Principe de fonctionnement
Le système repose sur l’idée que les mots les plus fréquents sont les plus représentatifs du contenu du texte.  
Chaque phrase reçoit un score basé sur la somme des fréquences des mots qu’elle contient.  
Les phrases avec les scores les plus élevés composent le résumé final.


