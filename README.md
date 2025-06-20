# Projet : Prédiction du niveau d’obésité

Ce projet vise à prédire le niveau d’obésité (`Insufficient_Weight`, `Normal_Weight`, `Obesity_Type_I`, ...) en fonction de divers facteurs alimentaires, physiques et comportementaux.

## Modèle sélectionné
✅ **RandomForestClassifier()** – Précision : **90%**

## Dépendances
- pandas
- scikit-learn
- matplotlib/seaborn
- joblib
- streamlit (optionnel)

## Fichiers inclus
- `models/obesity_risk_model.pkl` – Meilleur modèle entraîné
- `data/train_data(New_data).csv` – Données nettoyées
- `notebooks/Obesity_Risk_Classification.ipynb` – Notebook complet

## Pour exécuter l’application Streamlit :
```bash
streamlit run app.py
