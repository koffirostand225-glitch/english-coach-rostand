ENGLISH COACH v0.3 — PWA pour iPhone

CONTENU
- english_coach.html : l'application
- manifest.webmanifest : paramètres d'installation PWA
- sw.js : cache de l'application (mode hors ligne pour le shell)
- icons/ : icônes de l'application
- splash/ : écran de démarrage pour iPhone 11 Pro

PUBLIER (Netlify Drop)
1. Dézippe english_coach_pwa.zip sur ton ordinateur.
2. Ouvre le dossier english_coach_pwa (il contient directement english_coach.html, manifest.webmanifest et sw.js).
3. Sur Netlify Drop, dépose le dossier de déploiement (ou sélectionne ses fichiers si demandé).
4. Vérifie que le site est public, sans protection par mot de passe.
5. Ouvre le lien netlify.app sur l'iPhone avec Safari.

INSTALLER SUR IPHONE 11 PRO
1. Dans Safari, ouvre le site publié.
2. Appuie sur Partager.
3. Choisis « Sur l'écran d'accueil ».
4. Laisse le nom English Coach, puis appuie sur Ajouter.

NOTES IMPORTANTES
- L'installation nécessite une URL HTTPS; l'ouverture directe du fichier HTML ne suffit pas pour la PWA.
- Après la première visite, le shell peut fonctionner hors connexion grâce au cache, mais certaines fonctionnalités peuvent nécessiter internet.
- Cette version n'a pas encore de notifications push iOS ni de rappel système. Les rappels dans l'app sont des réglages locaux, pas des notifications envoyées.
- Le service worker met en cache la page et les icônes. Pour mettre à jour plus tard, incrémenter CACHE_NAME dans sw.js.
