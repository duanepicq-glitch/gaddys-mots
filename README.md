# Gaddy's Mots

Un Prop Hunt au bureau, jouable dans le navigateur : 10 cacheurs contre 1 chasseur.

- **Jouer** : une partie contre des bots.
- **Jouer entre amis** : crée une partie, donne le code à 5 caractères à tes amis, ils le saisissent pour rejoindre (11 joueurs max, les places libres sont prises par des bots).

## Commandes

- ZQSD / WASD : se déplacer · Maj : courir · Espace : sauter
- Cacheur : E pour se transformer en l'objet visé, F pour verrouiller la rotation (molette pour tourner), T pour provoquer
- Chasseur : clic pour tirer, R pour recharger. Tirer sur un vrai meuble coûte des points de vie.
- Tab : liste des joueurs · Échap : pause

## Technique

Un seul fichier `index.html` : Three.js pour la 3D, PeerJS pour le multijoueur (connexion directe entre navigateurs).
Pour tester en local sous Windows : `powershell -ExecutionPolicy Bypass -File serve.ps1`, puis ouvrir http://localhost:8080.
