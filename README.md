
# 🌍 Analyse des catastrophes naturelles dans le monde

Ce projet présente une **analyse exploratoire des catastrophes naturelles**, avec un focus sur les inondations en Asie. L’étude compare trois pays aux contextes contrastés : Chine, Inde et Yémen.

---

## 📝 Description

### Pays étudiés
   Pays   | Statut de développement | Contexte politique                |
 |--------|------------------------|------------------------------------|
 | 🇨🇳 Chine | Développé              | Pas de guerre déclarée            |
 | 🇮🇳 Inde  | Émergent               | Conflit frontalier (Cachemire)     |
 | 🇾🇪 Yémen | En développement       | Guerre civile                     |

### Objectifs
- Comprendre l’impact des catastrophes naturelles selon le contexte **politique, économique et social**.
- Créer un **indice de vulnérabilité** basé sur l’IDH et la stabilité politique.
- Visualiser les données pour identifier des tendances globales.

### Méthodologie
- **Nettoyage et analyse** : Python (Pandas, NumPy)
- **Visualisation** : Looker (tableaux de bord interactifs)
- **Données** : [Préciser la source et la période si possible]

---

## 📊 Résultats clés

### Corrélations
- Aucune corrélation significative entre le taux d’impact (personnes affectées/population) et les indicateurs socio-économiques (IDH, PIB/habitant, urbanisation).

### Tendances
- 📈 **Augmentation** du nombre de catastrophes naturelles dans le monde.
- 📉 **Diminution** globale du nombre de personnes affectées, **sauf** dans les pays instables ou en difficulté socio-économique.

### Conclusion
**Les pays en développement et politiquement instables sont les plus vulnérables.**
→ Nécessité d’une **coopération internationale** pour la prévention et la gestion des crises.

---

## 📂 Structure du projet

catastrophes_naturelles
│
├── data/
│   ├── raw/             # Données brutes (ex : EM-DAT, Banque Mondiale)
│   ├── processed/       # Données nettoyées et prêtes à l'analyse
│   └── external/        # Données externes (ex : IDH, PIB)
│
├── notebooks/
│   ├── 1_nettoyage.ipynb       # Nettoyage et préparation des données
│   ├── 2_analyse.ipynb         # Analyse statistique et corrélations
│   └── 3_visualisation.ipynb   # Création des graphiques et tableaux de bord
│
├── scripts/
│   ├── utils.py         # Fonctions utilitaires (calculs, indicateurs, etc.)
│   └── config.py        # Variables globales et chemins
│
├── outputs/
│   ├── figures/         # Graphiques exportés
│   └── reports/         # Rapports, présentations, synthèses
│
├── README.md            # Le README du projet
└── requirements.txt     # Liste des dépendances Python


---

## 📌 Remarques
- Ce projet est **clos** et partagé à titre informatif.
- Pour toute question ou réutilisation des données, contacter : [ton email ou lien].

---



