# CV & Portfolio Generator 🚀

Générateur dynamique universel de CV professionnels et de portfolios créatifs en HTML, entièrement hébergé côté client et déployable instantanément sur GitHub Pages.

## ✨ Fonctionnalités majeures (Mise à jour)

- **Générateur 100 % Local & RGPD** : Un seul fichier autonome compilant l'interface et les moteurs.
- **Anonymisation Directe** : Injection automatique de faux profils réalistes à chaque chargement pour protéger vos informations privées lors de démonstrations.
- **Modification Directe Cross-Modèle** : Un nouveau panneau d'interopérabilité permet de modifier l'axe de couleur principal, d'altérer la structure (inversion des colonnes) et de modifier les paires typographiques à chaud sur n'importe quel modèle.
- **Export Hybride instantané** : Téléchargement du fichier de code `.html` ou ouverture de la boîte système pour impression PDF A4.

## 📄 Liste des Modèles (Templates) inclus

### 1. Section Curriculum Vitae (CV)
| Modèle | Style & Description |
|---|---|
| **Classic** | Barre latérale sombre, graphiques de niveaux épurés, structure corporate solide. |
| **Light Pro** | En-tête dégradé sombre, corps double colonne blanc, lisibilité maximale. |
| **Creative Emerald** | Grille asymétrique moderne, puces d'expertises encapsulées, idéal profils tech. |
| **Editorial Serif** | Mode chic, haute typographie centrée (Playfair), idéal métiers littéraires/artistiques. |

### 2. Section Portfolios Écran
| Modèle | Style & Description |
|---|---|
| **Dark Cinematic** | Mode sombre enveloppant, filtres dynamiques par onglets, idéal monteurs vidéo. |
| **Minimal** | Fond blanc mat texturé, focus absolu sur les délivrables techniques. |
| **Masonry Visual** | Disposition en tuiles imbriquées asymétriques pour un impact visuel lourd. |
| **Adobe Left-Sidebar** | Réplique structurelle des sites vitrines épurés de la plateforme Adobe Portfolio. |

## 🛠️ Instructions de synchronisation Git & GitHub Pages

Pour envoyer ces modifications sur ton dépôt en ligne et écraser l'ancienne version, ouvre ton terminal dans le dossier du projet et exécute la suite de commandes suivante:

```bash
# 1. Vérifier le statut des fichiers modifiés
git status

# 2. Indexer la mise à jour globale
git add index.html README.md

# 3. Enregistrer les modifications avec un message explicite
git commit -m "Feat: Update renamings, randomized profile data, and added 6 new templates"

# 4. Propulser le code sur la branche principale en ligne
git push origin main
