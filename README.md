# Hackathon – Responsible AI for HR

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Contexte
Ce projet a été développé dans le cadre du *Hackathon by Ekimetrics* autour de la thématique *Responsible AI & Fairness appliquée aux ressources humaines*.  
L’objectif est de proposer des solutions responsables et équitables afin de réduire les biais dans les modèles d’IA appliqués au recrutement et à la gestion des talents.

Ekimetrics est un leader européen en data science et accompagne les entreprises dans leur transformation durable grâce à l’IA. Ce hackathon met l’accent sur la *responsabilité, la transparence et la robustesse des algorithmes*.

## Objectifs du projet
- Étudier les biais présents dans les données RH.
- Concevoir et évaluer des modèles prédictifs responsables.
- Mettre en place des méthodes de mitigation des biais pour assurer l’équité des résultats.
- Comparer la performance classique (accuracy, recall, etc.) et la performance en termes d’équité (fairness metrics).

## 📂 Contenu du dépôt
- [`notebook_hackathon_final_version.ipynb`](notebook_hackathon_final_version.ipynb) : Notebook principal contenant l’analyse, la modélisation et les résultats.  
- [`Hackathon by Ekimetrics Presentation.pdf`](Hackathon%20by%20Ekimetrics%20Presentation.pdf) : Présentation officielle du hackathon et du contexte.  
- [`FairHire_Group6.pdf`](FairHire_Group6.pdf) : Présentation finale du groupe, jouant le rôle de consultants, présentant une solution de recrutement intégrant des critères de fairness devant le jury.  
- `README.md` : Ce fichier de documentation.

## 🛠 Technologies et techniques utilisées

- **Langages et librairies :**
  - Python 
  - Jupyter Notebook
  - Librairies : pandas, numpy, scikit-learn, AIF360, Fairlearn, matplotlib, seaborn

- **Pré-traitement (Pre-processing) :**
  - Nettoyage des données
  - Gestion des valeurs manquantes
  - Encodage des variables catégorielles
  - Rééchantillonnage des classes (Resampling) pour équilibrer le dataset

- **Modélisation :**
  - Modèles supervisés classiques (RandomForest, Decision Tree, etc.)
  - Intégration de contraintes de fairness in-training

- **Post-traitement (Post-processing) :**
  - Calibration équitable des scores
  - Ajustement pour réduire les biais sur les populations protégées

- **Évaluation :**
  - Mesures de performance : Accuracy, Precision, Recall, ROC / AUC
  - Mesures d’équité : Demographic Parity, Equal Opportunity, Disparate Impact

## License
Ce projet est sous **[MIT License](LICENSE)**.
 