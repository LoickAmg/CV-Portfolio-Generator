# AMG Generator — CV & Portfolio Builder

Générateur dynamique de CV et de portfolios en HTML, déployable sur GitHub Pages.

## ✨ Ce que c'est

Un outil web **100 % local** (un seul fichier HTML) qui permet de :
- **Créer des CV** en remplissant un formulaire → aperçu en direct
- **Créer des portfolios** avec ses projets, bio, compétences
- **Exporter en HTML** (fichier téléchargeable, standalone)
- **Exporter en PDF** via la boîte de dialogue d'impression du navigateur
- Choisir parmi **4 templates** (2 CV, 2 Portfolio)

## 🚀 Déploiement sur GitHub Pages

```bash
# 1. Créer un repo GitHub (ex: amg-generator)
git init
git add index.html README.md
git commit -m "Init AMG Generator"
git branch -M main
git remote add origin https://github.com/TON_USERNAME/amg-generator.git
git push -u origin main

# 2. Activer GitHub Pages
# → Settings > Pages > Branch: main > / (root) > Save
# URL: https://TON_USERNAME.github.io/amg-generator/
```

## 📄 Templates disponibles

### CV
| Template | Description |
|---|---|
| **AMG Classic** | Sidebar sombre (#111b26) + main clair, barres de compétences, style professionnel sombre |
| **Light Pro** | Header bleu gradient, 2 colonnes clair, minimaliste et lisible |

### Portfolio
| Template | Description |
|---|---|
| **AMG Dark** | Fond cinématique (#080c10), grille de projets filtrables, hero animé |
| **Minimal** | Fond blanc, typographie seule, maximaliste en contenu |

## 🛠 Utilisation

1. Ouvrir `index.html` dans n'importe quel navigateur
2. Remplir le formulaire (gauche)
3. L'aperçu (droite) se met à jour en temps réel
4. Cliquer **⬇ HTML** pour télécharger le fichier final
5. Cliquer **🖨 PDF** pour ouvrir dans un nouvel onglet et imprimer

> **Astuce PDF** : Dans la boîte d'impression, choisir « Enregistrer en PDF » et décocher les en-têtes/pieds de page.

## 📁 Structure

```
amg-generator/
└── index.html   ← Le générateur complet (auto-contenu)
└── README.md
```

## 🧩 Personnaliser les templates

Le fichier `index.html` contient 4 fonctions de rendu facilement modifiables :
- `renderCVAMGClassic()` — CV template 1
- `renderCVLightPro()` — CV template 2
- `renderPortfolioDark()` — Portfolio template 1
- `renderPortfolioMinimal()` — Portfolio template 2

Chaque fonction retourne une chaîne HTML complète et auto-contenue.

## Auteur

**AMOUSSOU-GUENOU Loïc Junior Mahouna** · [mahounaamg@gmail.com](mailto:mahounaamg@gmail.com)
