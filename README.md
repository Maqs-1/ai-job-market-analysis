# ai-job-market-analysis
"Analyse des tendances de l'emploi en intelligence artificielle (2025)"

## 🎯 Objectif du projet

Ce projet a pour but de **comprendre les dynamiques du marché de l’emploi en IA à l’échelle mondiale** à travers plus de **15 000 offres d’emploi** collectées en 2024-2025.

Nous avons structuré notre démarche autour de **4 axes principaux** :

1. **Analyser les salaires et les inégalités**
2. **Comprendre l’impact des compétences, de l’éducation et de l’expérience**
3. **Modéliser la rémunération à partir des caractéristiques des offres**
4. **Raconter une histoire métier pour recruteurs, RH ou professionnels en reconversion IA**

---

## 📊 Contenu du projet

| Fichier                          | Description |
|----------------------------------|-------------|
| `notebook_analysis.ipynb`        | Analyse exploratoire et storytelling visuel complet |
| `model_salary_prediction.ipynb`  | Modélisation du salaire via régression linéaire & random forest |
| `data/ai_job_dataset.csv`        | Données brutes nettoyées (issues de Kaggle) |
| `outputs/graphs/`                | Graphiques et visualisations générées |

---

## 🧠 Axes d’analyse

### 💰 1. **Analyse salariale globale**
- Salaires par pays, par secteur, par taille d’entreprise
- Impact du télétravail sur les rémunérations
- Écarts selon le niveau d’études et d’expérience

### 🧠 2. **Compétences et profils recherchés**
- Quelles compétences font le plus monter les salaires ? (ex : GCP, NLP, Deep Learning)
- Compétences les plus fréquentes selon le niveau d’études (PhD vs Bac+3)
- Profils à bas salaires : quelles compétences dominent ?

### 🔍 3. **Modélisation du salaire**
- Modèle de régression linéaire interprétable (R² ≈ 0.64)
- Modèle Random Forest (R² ≈ 0.63)
- Analyse des variables les plus influentes :
  - 🔝 `années_experience_requises`
  - `niveau_experience`, `taille_entreprise`, certaines compétences

---

## 📚 Enseignements clés

- 📈 L’**expérience professionnelle** est le facteur le plus déterminant sur la rémunération
- 🧠 Les **compétences avancées** (Deep Learning, GCP, Computer Vision) boostent les salaires
- 💼 Les grandes entreprises paient significativement plus que les petites
- 🌍 Le **télétravail** a un effet modéré mais croissant selon le pays

---

## 🛠️ Tech Stack
- `Python`, `pandas`, `matplotlib`, `seaborn`
- `scikit-learn`, `CountVectorizer`, `RandomForest`
- `SHAP` (à intégrer pour interprétation avancée)
- `Jupyter Notebooks`

---

## 👨‍💻 Auteur

> **Nom / Pseudo GitHub**  
> 💼 Data Analyst Junior passionné par les marchés, la visualisation et l’IA.  
> 📫 Contact : [lien LinkedIn ou mail]
