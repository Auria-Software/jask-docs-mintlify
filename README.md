# Jask Documentation

Documentation produit et référence API de Jask, construite avec
[Mintlify](https://www.mintlify.com/).

## Développement local

Prérequis : Node.js 20 ou une version ultérieure.

```bash
npm install
npm run dev
```

La prévisualisation locale est disponible sur `http://localhost:3000`.

## Vérifications

```bash
npm run validate
npm run check:links
npm run check:a11y
```

La commande `npm run check` exécute les trois vérifications.

## Structure

- `docs.json` : configuration, navigation, intégrations et redirections.
- `docs/` : documentation produit.
- `api/` : référence API rédigée manuellement.
- `changelog/` : notes de version.
- `images/` : captures d'écran, GIF et identité visuelle.

Les chemins historiques `/docs`, `/api` et `/changelog` sont conservés.

## Déploiement

Connectez ce dépôt au projet depuis le tableau de bord Mintlify, puis
sélectionnez la branche de production. Chaque push sur cette branche déclenche
un déploiement et les pull requests reçoivent une prévisualisation.
