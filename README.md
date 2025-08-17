# Kawoukeravore GP — Site statique (GitHub Pages)

Site vitrine pour la mise en relation des entreprises et clients en Guadeloupe, avec page d’invitation WhatsApp (QR dynamique).

## 🚀 Déploiement sur GitHub Pages

1. **Créer un dépôt** sur GitHub (ex: `kawoukeravore-gp-site`).
2. **Pousser** ce code :
   ```bash
   git init
   git add .
   git commit -m "Initial commit: site Kawoukeravore GP"
   git branch -M main
   git remote add origin https://github.com/<VOTRE-ORG-OU-USER>/kawoukeravore-gp-site.git
   git push -u origin main
   ```
3. **Activer GitHub Pages** : Settings → Pages → Branch: `gh-pages` (sera créé automatiquement par le workflow) ou `main`/root si vous préférez sans workflow.
4. L’URL de prod sera du type `https://<VOTRE-ORG-OU-USER>.github.io/kawoukeravore-gp-site/`.

## 🔧 Configuration

- Modifiez la constante `GROUP_LINK` dans `index.html` (ou déportez-la dans `assets/js/main.js` si souhaité).
- Remplacez les URLs OpenGraph et les favicons par vos vraies ressources.

## 🧱 Arborescence

```
.
├─ index.html
├─ assets/
│  ├─ css/        # Feuilles de style optionnelles
│  ├─ js/         # Scripts personnalisés
│  └─ img/        # Images et logos
├─ .github/
│  └─ workflows/
│     └─ pages.yml  # Déploiement GitHub Pages (branche gh-pages)
├─ .gitignore
├─ LICENSE
├─ SECURITY.md
└─ CONTRIBUTING.md
```

## 🛡️ Sécurité
Voir `SECURITY.md` pour signaler une vulnérabilité.

## 🤝 Contributions
Voir `CONTRIBUTING.md` pour les règles de contribution.
