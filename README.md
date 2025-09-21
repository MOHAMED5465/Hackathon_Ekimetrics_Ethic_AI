# Hackathon – Responsible AI for HR

##  Contexte  
Ce projet a été développé dans le cadre du *Hackathon by Ekimetrics* autour de la thématique *Responsible AI & Fairness appliquée aux ressources humaines*.  
L’objectif est de proposer des solutions responsables et équitables afin de réduire les biais dans les modèles d’IA appliqués au recrutement et à la gestion des talents.

Ekimetrics est un leader européen en data science et accompagne les entreprises dans leur transformation durable grâce à l’IA. Ce hackathon met l’accent sur la *responsabilité, la transparence et la robustesse des algorithmes*.

##  Objectifs du projet  
- Étudier les biais présents dans les données RH.  
- Concevoir et évaluer des modèles prédictifs responsables.  
- Mettre en place des méthodes de mitigation des biais pour assurer l’équité des résultats.  
- Comparer la performance classique (accuracy, recall, etc.) et la performance en termes d’équité (fairness metrics).  

## 📂 Contenu du dépôt  
- notebook_hackathon_final_version.ipynb : Notebook principal contenant l’analyse, la modélisation et les résultats.  
- Hackathon by Ekimetrics Presentation.pdf : Présentation officielle du hackathon et du contexte.  
- README.md : Ce fichier de documentation.  

## 🛠 Méthodologie  
1. *Exploration des données*  
   - Analyse exploratoire.  
   - Identification des biais potentiels (genre, âge, etc.).  

2. *Modélisation*  
   - Entraînement de modèles supervisés.  
   - Intégration de librairies de fairness (ex: AIF360, Fairlearn).  

3. *Évaluation*  
   - Mesures de performance : accuracy, precision, recall.  
   - Mesures d’équité : demographic parity, equal opportunity, disparate impact.  

4. *Mitigation*  
   - Techniques de pré-traitement (rééquilibrage des données).  
   - Méthodes en-in-training (réglages de contraintes).
   - Méthodes post-traitement (calibration équitable des scores).  