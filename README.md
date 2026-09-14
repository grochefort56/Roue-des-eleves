# Roue des élèves — application web installable

Ce dossier contient la PWA. Elle ne nécessite aucun serveur applicatif : les classes, les élèves et l'historique sont enregistrés localement dans le navigateur de chaque utilisateur.

## Publication

Publiez **le contenu de ce dossier** sur un hébergement HTTPS (GitHub Pages, Netlify, Cloudflare Pages, ou le serveur web de votre établissement). Ouvrez ensuite l'URL avec Chrome ou ChromeOS.

Dans ChromeOS, ouvrez le menu Chrome puis choisissez **Installer Roue des élèves**. L'application apparaîtra alors dans le lanceur, comme une application native.

> Ne double-cliquez pas sur `index.html` : une PWA doit être ouverte depuis une adresse `https://` (ou `http://localhost` pendant les tests) pour que l'installation et le mode hors connexion soient activés.

## Données

Les données ne sont pas partagées entre ordinateurs : chaque navigateur possède sa propre base locale. Pour une version partagée entre plusieurs enseignants ou appareils, il faudra ajouter un serveur de synchronisation et une authentification.
