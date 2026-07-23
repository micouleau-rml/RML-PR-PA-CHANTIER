# RML Préparation Chantier — PWA

Cette version est prête pour GitHub Pages et peut être installée sur Mac, iPhone et iPad.

## Publication sur GitHub Pages

1. Créez un nouveau dépôt GitHub, par exemple `rml-preparation-chantier`.
2. Déposez à la racine du dépôt tous les fichiers et dossiers contenus dans ce ZIP :
   - `index.html`
   - `manifest.webmanifest`
   - `service-worker.js`
   - `logo-rml.png`
   - le dossier `icons`
3. Dans GitHub, ouvrez **Settings > Pages**.
4. Dans **Build and deployment**, choisissez :
   - Source : **Deploy from a branch**
   - Branch : **main**
   - Dossier : **/(root)**
5. Enregistrez et attendez l’adresse GitHub Pages.

## Installation sur iPhone/iPad

1. Ouvrez l’adresse GitHub Pages dans Safari.
2. Touchez **Partager**.
3. Touchez **Sur l’écran d’accueil**.
4. Touchez **Ajouter**.

## Installation sur Mac

- Safari : **Fichier > Ajouter au Dock**.
- Chrome/Edge : utilisez l’icône d’installation dans la barre d’adresse.

## Mise à jour

Après une modification importante, changez la valeur `CACHE_NAME` dans `service-worker.js`
(par exemple `rml-preparation-chantier-v10-2`) afin de forcer le renouvellement du cache.
