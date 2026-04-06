=== BLOCKBEATS PWA - Instructions d'installation ===

OPTION 1 — Hébergement gratuit sur GitHub Pages (recommandé) :
1. Crée un compte sur github.com
2. Crée un nouveau dépôt public (ex: "blockbeats")
3. Upload tous les fichiers de ce dossier
4. Va dans Settings > Pages > Branch: main > Save
5. Ton app sera dispo sur : https://[ton-pseudo].github.io/blockbeats/
6. Ouvre ce lien sur Android avec Chrome
7. Chrome affiche "Ajouter à l'écran d'accueil" → Appuie !

OPTION 2 — Hébergement sur Netlify (encore plus simple) :
1. Va sur netlify.com et crée un compte
2. Glisse-dépose ce dossier entier dans l'interface
3. Netlify te donne une URL en quelques secondes
4. Ouvre l'URL sur Android avec Chrome > Installer

OPTION 3 — APK via PWABuilder :
1. Héberge d'abord l'app (option 1 ou 2)
2. Va sur pwabuilder.com
3. Entre ton URL → Génère un APK Android signé
4. Installe l'APK sur ton téléphone

=== Fichiers inclus ===
- index.html     → L'application complète
- manifest.json  → Config PWA (nom, icône, couleurs)
- sw.js          → Service Worker (mode hors-ligne)
- icon-192.png   → Icône Android (192x192)
- icon-512.png   → Icône Android HD (512x512)
