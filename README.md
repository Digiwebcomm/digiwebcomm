# Digiwebcomm

Site vitrine statique pour Digiwebcomm, prêt pour Cloudflare Pages.

## Fichiers
- `index.html` : page d'accueil
- `assets/style.css` : styles adaptatifs
- `assets/main.js` : menu mobile et année du pied de page

## Avant publication
1. Remplacer `contact@digiwebcomm.be` par votre adresse e-mail réelle.
2. Vérifier les services, les textes et les coordonnées.
3. Ajouter les pages légales nécessaires à votre activité (mentions légales, politique de confidentialité, cookies si nécessaire).

## Publication Cloudflare Pages
Dans Cloudflare : Workers & Pages → Create → Pages → Connect to Git. Choisir le dépôt `digiwebcomm`. Pour ce site HTML statique, ne pas définir de commande de build et laisser le répertoire de sortie à `/` si l'interface le demande; sinon utiliser le réglage adapté à la méthode de déploiement choisie.

## CMS
Ce dossier est le site vitrine initial. Pour l'édition visuelle et la création de nouvelles pages sans coder, une configuration CMS doit encore être ajoutée et testée avant de compter dessus en production.
