# 🏠 Foncio — Gestion Locative Privée

Application PWA mobile-first pour gérer votre parc locatif privé, conçue pour iPhone.  
**Aucun serveur. Aucune inscription. Données 100% locales sur votre appareil.**

## 🚀 Déploiement GitHub Pages

### Étapes

1. **Créez un dépôt GitHub** nommé `foncio` (ou le nom de votre choix)

2. **Uploadez les fichiers** :
   ```
   index.html   ← l'application complète
   README.md    ← ce fichier
   ```

3. **Activez GitHub Pages** :
   - Settings → Pages → Source : `Deploy from a branch`
   - Branch : `main` → folder : `/ (root)`
   - Save

4. **Accédez à votre app** : `https://[votre-pseudo].github.io/foncio/`

5. **Installez sur iPhone** :
   - Ouvrez l'URL dans Safari
   - Partager ⬆ → Sur l'écran d'accueil
   - L'app s'installe comme une appli native

---

## 📱 Fonctionnalités

| Module | Description |
|--------|-------------|
| 🏠 **Logements** | Ajout/édition, fiche complète, DPE, conformité |
| 💶 **Loyers** | Appels automatiques le 20, encaissement, quittances PDF |
| ⚠️ **Dettes** | Détection paiements partiels, mise en demeure, relances |
| 📊 **Compta** | Recettes/dépenses par logement, bilan annuel |
| ◈ **Fiscal** | Comparaison réel/micro-foncier, aide formulaire 2044 |
| 📁 **Documents** | Quittances et appels générés automatiquement |
| ⚙️ **Réglages** | Profil, export/import JSON, explorateur de données |
| ↩ **Migration** | Import depuis GérerSeul par copier-coller |

---

## 🔒 Données & Confidentialité

- Toutes les données sont stockées **uniquement dans le localStorage** de votre navigateur
- Aucune donnée n'est transmise à un serveur tiers
- Exportez régulièrement via **Réglages → Exporter mes données** (fichier JSON)
- En cas de changement d'appareil : importez votre JSON via **Réglages → Restaurer**

---

## 📄 Mise à jour sans perte de données

Pour mettre à jour l'app avec une nouvelle version :

1. **Exportez vos données** : Réglages → Exporter mes données → téléchargez le JSON
2. Remplacez `index.html` sur GitHub
3. **Restaurez vos données** : Réglages → Restaurer depuis un fichier → sélectionnez votre JSON

---

## 🛠️ Technologies

- HTML/CSS/JS vanilla — aucune dépendance
- PWA installable (iOS Safari 16.4+)
- localStorage pour la persistance des données
- CSS variables pour le thème bleu marine / or

---

## 📋 Version

**Foncio v1.0** — Testé sur iPhone 14 Pro, iOS 17, Safari  
95 tests automatisés ✅ — 0 erreur
