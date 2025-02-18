# 🛡️ Détection de Fraude aux Paiements avec Machine Learning  

## 📌 Description du Projet  
Ce projet vise à développer un modèle de machine learning capable de détecter les fraudes aux paiements bancaires.  
En utilisant des algorithmes comme **Random Forest** et **XGBoost**, nous analysons des transactions pour identifier les comportements frauduleux tout en minimisant les faux positifs.  

## 📊 Jeu de Données  
Nous utilisons le dataset **Bank Account Fraud (BAF)** de NeurIPS 2022, qui contient des transactions synthétiques avec :  
✅ Distribution temporelle  
✅ Biais et déséquilibre marqué entre cas de fraude et transactions légitimes  
✅ Aucune valeur manquante ni doublons  

## 🛠️ Technologies Utilisées  
- **Python** (Pandas, NumPy, Scikit-learn)  
- **Machine Learning** (Random Forest, XGBoost)  
- **Visualisation** (Matplotlib, Seaborn, Plotly)  

## 📈 Résultats et Évaluation  
- **Métrique principale :** ROC AUC Score  
- **Score obtenu :** `0.89`  
- **Autres métriques :** Précision, Recall, F1-score = 0.81 

## 🚀 Comment Exécuter le Projet  
1. Clonez le dépôt :  
   git clone https://github.com/amin-ghazzali/fraud-detection-ml.git

## 🔥 Améliorations Futures
- Intégration d’une détection en temps réel avec un déploiement via Flask/FastAPI
