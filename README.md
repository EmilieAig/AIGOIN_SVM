# HAX907X - TP3 - Support Vector Machine (SVM)

Bonjour à tous et bienvenu sur la page du projet de travaux pratiques sur les machines à vecteurs de support (SVM) réalisés dans le cadre du cours HAX907X à l'Université de Montpellier (2025/2026).

### Description

Ce projet explore l'utilisation des SVM pour la classification binaire et multi-classe à travers trois cas d'étude :
1. **Classification sur le dataset Iris** : comparaison des noyaux linéaire et polynomial.
2. **Impact du déséquilibre des classes** : analyse du paramètre de régularisation C.
3. **Reconnaissance faciale** : classification de visages avec gestion du bruit et réduction de dimension (ACP).

### Lancement du projet

Les prérequis sont :
- Python (version supérieure à 3.8)
- Git

Pour lancer le projet :
- Cloner le dépôt.
- Lancer le fichier "requirements.txt" pour installer les dépendances (il faut penser à décommenter les premières lignes)
- Lancer le script "svm_script.py" pour le fichier Python / le script script.qmd pour un rendu en quarto ou en .html / ouvrir directement le fichier script.html

### Structure

L'arborescence du dépôt git est la suivante :

```AIGOIN_SVM/
├── graphiques/             # Figures générées et affichés dans le fichier script.html
│   ├── C1.png
│   ├── C01.png
│   ├── C001.png
│   └── C10.png
├── mise_en_page/           # Fichiers de styles et logos pour la page de garde dans le fichier script.hmtl
│   ├── Logo_SSD.png
│   ├── Logo_univMtp.png
│   └── page_garde.html
├── scripts_Python/         # Fichiers de style
│   ├── svm_gui.py          # Fichier à lancer pour répondre à la question numéro 3 du TP (source https://scikit-learn.org/1.2/auto_examples/applications/svm_gui.html)
│   ├── svm_script.py       # Fichier de code à lancer pour avoir les résultats des questions du TP sans explications (base de code de B.Bensaid, B. Charlier, J. Salmon)
│   └── svm_source.py       # Fichier utilisé dans svm_script.py et script.qmd contenant des fonctions nécessaires pour réaliser des travaux SVM (auteurs J. Salmon, A. Gramfort, C. Vernade)
├── .gitignore              # Fichier permettant d'ignorer les fichiers non utiles 
├── README.md
├── requirements.txt        # Fichier à lancer pour installer les packages nécessaire pour faire tourner le code
├── Compte-rendu.html             # Rendu final du TP avec le code et les explications
└── Compte-rendu.qmd              # Fichier à lancer pour re générer le rendu final script.html

```         

Bonne lecture !

AIGOIN Emilie
