# 🏠 Foncio — Gestion Locative

PWA mobile-first pour gérer votre parc locatif privé. **Aucun serveur. 100 % local.**

## 🚀 Déploiement GitHub Pages — 3 minutes

1. **Créez un dépôt GitHub** (n'importe quel nom)
2. **Uploadez `index.html`** à la racine (drag & drop)
3. **Settings → Pages** → Source : `Deploy from a branch` → Branch : `main` → folder : `/ (root)` → Save
4. Attendez 1 min, votre URL : `https://[pseudo].github.io/[repo]/`
5. **Sur iPhone** : ouvrez l'URL dans Safari → Partager ⬆ → Sur l'écran d'accueil

## 📱 Fonctionnalités

- **Logements** : ajout 3 étapes, fiche complète, IRL, DPE, conformité
- **Loyers & quittances** : appels auto le 20, encaissement, dette détectée auto
- **Dettes locatives** : paiements partiels suivis, mises en demeure, relances
- **Compta** : recettes/dépenses incluant compléments, bilan annuel
- **Fiscal** : aide formulaire 2044, comparaison réel/micro-foncier
- **Documents** : quittances + appels générés, partage email
- **Audit complet** : toutes les opérations tracées (création, paiement, modification, diagnostic, IRL)
- **Settings** : profil, export/import JSON, explorateur de données

## 🔒 Données

Stockées **uniquement sur votre appareil** dans `localStorage`. Pour mettre à jour sans perte : **Réglages → Exporter** (JSON) avant de pousser une nouvelle version, puis **Restaurer** après.

## 📋 Mises à jour de cette version

- ✅ PDF : bouton **Fermer** toujours accessible
- ✅ Quittance partielle : affiche **loyer appelé / encaissé / solde dû**
- ✅ Suppression "Signature du bailleur" et nom de l'app dans les PDFs
- ✅ Compta : recettes incluent désormais **paiements partiels + compléments**
- ✅ **Audit complet** : création, paiements, IRL, DPE, diagnostics, locataire — tout est tracé

## 🛠 Stack

HTML/CSS/JS vanilla, zéro dépendance externe. PWA installable iOS Safari 16.4+.
