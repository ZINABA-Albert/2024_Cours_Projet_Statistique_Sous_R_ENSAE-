# 📊 Projet de Statistique sous R, ENSAE Dakar (2024)

> Travaux pratiques et projet réalisés dans le cadre du cours de **Statistique sous R** à l'École Nationale de la Statistique et de l'Analyse Économique Pierre Ndiaye (ENSAE Dakar), année académique 2024.

---

## 🎯 Objectifs pédagogiques

Ce dépôt regroupe les travaux pratiques du cours de statistique appliquée sous R. Les objectifs principaux sont :

- Maîtriser la **manipulation et le nettoyage de données** avec les packages du tidyverse
- Réaliser des **analyses statistiques descriptives** et inférentielles
- Produire des **visualisations** claires et informatives avec ggplot2
- Rédiger des **rapports reproductibles** avec R Markdown

---

## 📁 Contenu du dépôt

```
2024_Cours_Projet_Statistique_Sous_R_ENSAE/
│
├── TP_3_ZINABA_Albert.zip   # Travaux pratiques n°3 (scripts R + rapport)
└── README.md
```

> Les travaux pratiques incluent les scripts R commentés, les données utilisées (si libres de droits) et les rapports R Markdown compilés en HTML/PDF.

---

## 🛠️ Technologies & Packages R utilisés

| Catégorie | Packages |
|---|---|
| Manipulation de données | `dplyr`, `tidyr`, `readr` |
| Visualisation | `ggplot2`, `ggcorrplot` |
| Statistiques descriptives | `gtsummary`, `gt`, `summarytools` |
| Rapports | `rmarkdown`, `knitr` |
| Divers | `lubridate`, `stringr` |

---

## 🚀 Comment utiliser ce dépôt

### Prérequis

- **R** version 4.0 ou supérieure — [Télécharger R](https://www.r-project.org/)
- **RStudio** (recommandé) — [Télécharger RStudio](https://www.rstudio.com/)

### Installation

```r
# Cloner le dépôt
git clone https://github.com/ZINABA-Albert/2024_Cours_Projet_Statistique_Sous_R_ENSAE-.git

# Installer les packages nécessaires
packages <- c("dplyr", "tidyr", "readr", "ggplot2", "gtsummary",
              "gt", "rmarkdown", "knitr", "summarytools")

for (pkg in packages) {
  if (!requireNamespace(pkg, quietly = TRUE)) install.packages(pkg)
  library(pkg, character.only = TRUE)
}
```

### Exécution

1. Décompresser `TP_3_ZINABA_Albert.zip`
2. Ouvrir le fichier `.Rmd` dans RStudio
3. Exécuter les chunks séquentiellement ou compiler le rapport complet via **Knit to HTML**

---

## 📚 Thèmes abordés

- Statistiques descriptives univariées et bivariées
- Tests d'hypothèses (test t, chi², ANOVA)
- Régression linéaire simple et multiple
- Visualisation de distributions, corrélations et résidus
- Rédaction de rapports statistiques reproductibles avec R Markdown

---

## 🏫 Contexte académique

| | |
|---|---|
| **Institution** | ENSAE Dakar (École Nationale de la Statistique et de l'Analyse Économique Pierre Ndiaye) |
| **Programme** | Ingénieur Statisticien Économiste (ISE) |
| **Cours** | Statistique appliquée sous R |
| **Année** | 2024 |
| **Pays** | Sénégal |

---

## ✍️ Auteur

**Albert ZINABA**
Élève Ingénieur Statisticien Économiste — ENSAE Dakar

[![LinkedIn](https://img.shields.io/badge/LinkedIn-albertzinaba-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/albertzinaba)
[![GitHub](https://img.shields.io/badge/GitHub-ZINABA--Albert-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ZINABA-Albert)
[![Email](https://img.shields.io/badge/Email-albertzinaba@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:albertzinaba@gmail.com)

---

## 📄 Licence

Ce projet est partagé à des fins éducatives. Les données utilisées appartiennent à leurs sources respectives.
