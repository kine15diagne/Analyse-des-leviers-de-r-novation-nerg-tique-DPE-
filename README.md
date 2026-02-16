# Analyse des leviers de rénovation énergétique (DPE)


**Objectif**

Identifier les variables prioritaires en cas de rénovation énergétique afin d’augmenter la probabilité d’atteindre les classes DPE A et B.

**Données utilisées**

Base publique DPE

Données de consommation énergétique

Fusion via join_key

Nettoyage, suppression des outliers, encodage

**Méthodologie**

Analyse exploratoire (FAMD, ANOVA)

Modèles Machine Learning :

Régression Logistique

Random Forest

XGBoost

Interprétation SHAP

Analyse d’impact (approche contre-factuelle)

**Résultats clés**

🔹 La qualité de l’isolation est le principal levier actionnable

🔹 L’année de construction est explicative mais non modifiable

🔹 +9.8 points de probabilité en moyenne après amélioration

🔹 ~1 logement sur 10 change réellement de classe

🔹 Classes D et E = cibles prioritaires

**Technologies**

Python

pandas

scikit-learn

XGBoost

SHAP

DuckDB

**Structure du projet**

notebooks : analyses complètes

presentation : support de présentation
