# Digital Sovereignty Assessment Tool

Un questionnaire d'auto-évaluation de la souveraineté numérique, conçu pour **fonctionner 100 % en local dans le navigateur**.

## 🔒 Sécurité & confidentialité (point central)

Ce projet est volontairement conçu pour un usage local afin de protéger les informations sensibles :

- **Aucun backend requis**.
- **Aucun appel réseau nécessaire** pour compléter le questionnaire.
- **Aucune donnée n'est envoyée vers un serveur externe**.
- Les réponses sont conservées uniquement dans le navigateur de l'utilisateur (stockage local), sur sa machine.

En pratique : vos données restent sous votre contrôle, dans votre environnement.

## 🎯 Objectif

L'outil permet d'évaluer la maturité d'une organisation sur plusieurs axes de souveraineté numérique (cloud, données, identité, infrastructure, conformité, etc.), puis de restituer un score et une synthèse.

## 🧱 Stack technique

- HTML
- CSS
- JavaScript (vanilla)
- Application statique mono-page (`index.html`)

## ▶️ Lancer le questionnaire en local

### Option 1 — ouverture directe

1. Cloner le dépôt.
2. Ouvrir `index.html` dans votre navigateur.

### Option 2 — via un serveur local (recommandé pour un usage d'équipe)

Depuis la racine du projet :

```bash
python3 -m http.server 8000
```

Puis ouvrir : `http://localhost:8000`

## ✅ Cas d'usage recommandés

- Ateliers d'évaluation en interne.
- Contextes sensibles (RSSI, conformité, architecture, souveraineté des données).
- Démonstrations où l'on veut garantir qu'aucune information ne quitte le poste utilisateur.

## ⚠️ Bonnes pratiques

- Exécuter l'outil sur un poste de confiance.
- Éviter les extensions navigateur non maîtrisées dans les contextes sensibles.
- Purger le stockage navigateur après usage si nécessaire.

## 📄 Licence

Ce projet est distribué sous licence MIT. Voir le fichier `LICENSE`.
