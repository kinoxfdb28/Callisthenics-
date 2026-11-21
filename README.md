# Calisthenics Tracker

Application web progressive (PWA) en français, pensée pour mobile.

## Contenu
- Séances A et B avec cases à cocher et saisie des répétitions/durées
- Programme de 12 semaines
- Chronomètre de repos
- Historique des séances
- Tests de progression
- Export/import de sauvegarde JSON
- Stockage local et fonctionnement hors connexion après première visite

## Installation
Pour installer comme une application sur Android, les fichiers doivent être publiés sur une adresse HTTPS.
1. Décompresser l'archive.
2. Publier le contenu du dossier sur un hébergement HTTPS (par exemple GitHub Pages ou Netlify).
3. Ouvrir l'adresse dans Chrome sur Android.
4. Menu ⋮ > « Installer l'application » ou « Ajouter à l'écran d'accueil ».

Le service worker ne fonctionne pas depuis un simple fichier local `file://`. Les données sont stockées dans le navigateur de l'appareil ; utiliser « Exporter ma sauvegarde » avant de changer de navigateur ou de téléphone.
