# 🧪 A/B Testing — Analyse de taux de conversion

## 📌 Description
Analyse statistique complète d'un test A/B comparant deux versions 
d'une landing page (old_page vs new_page) sur un dataset de 294 478 
utilisateurs afin de déterminer laquelle convertit le mieux.

## ❓ Problématique
Quelle version d'une landing page convertit le mieux les utilisateurs ?
La différence observée est-elle réelle ou due au hasard ?

## 🗂️ Dataset
- 294 478 utilisateurs
- Source : (https://www.kaggle.com/datasets/zhangluyuan/ab-testing)
- Colonnes : user_id, timestamp, group, landing_page, converted

## 🛠️ Technologies
- Python
- Pandas
- Matplotlib / Seaborn
- Scipy / Numpy

## ⚙️ Installation
# Cloner le projet
git clone https://github.com/bazbamba8-maker/ab-testing

# Installer les dépendances
pip install -r requirements.txt

## 📊 Résultats

- taux de conversion_control (old_page) : 12.04%
- taux de conversion_treatment (new_page) : 11.88%
- Différence observée : 0.16%
- P-value : 0.1897
- Conclusion : différence non significative (p > 0.05)

## 💡 Recommandation
La new_page ne performe pas mieux que l'old_page.
Le vrai enjeu identifié : 88% des utilisateurs ne convertissent pas,
quelle que soit la page. Des données supplémentaires (temps passé,
scroll depth, device, source de trafic) seraient nécessaires pour
diagnostiquer et résoudre ce problème de conversion.

## 🔗 Auteur
Bamba Baz — github.com/bazbamba8-maker