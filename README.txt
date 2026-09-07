SUIVI SPORTIF — CONTENEUR PWA
=============================

1. Ouvre index.html.
2. Remplace COLLE_ICI_TON_URL_GOOGLE_APPS_SCRIPT_SE_TERMINANT_PAR_EXEC
   par l'URL de déploiement de ta Web App Apps Script.
3. Publie ce dossier sur un hébergement HTTPS statique (GitHub Pages, Firebase Hosting,
   Cloudflare Pages, Netlify, etc.).
4. Ouvre l'URL HTTPS obtenue dans Chrome sur Android.
5. Menu ⋮ > Installer et créer un raccourci > Installer.

IMPORTANT
---------
- Ne remplace PAS ton Index.html Apps Script actuel par ce fichier : celui-ci est
  l'enveloppe PWA externe.
- Ton application Apps Script actuelle reste telle quelle et s'affiche dans une iframe.
- Code.gs contient déjà setXFrameOptionsMode(ALLOWALL), indispensable pour l'iframe.
- Le service worker ne rend pas les données Apps Script disponibles hors connexion.
