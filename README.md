# Gaddy's Mots

Un Prop Hunt au bureau, jouable dans le navigateur : 10 cacheurs contre 2 chasseurs.

- **Jouer** : une partie contre des bots.
- **Jouer entre amis** : crée une partie, donne le code à 5 caractères à tes amis, ils le saisissent pour rejoindre (12 joueurs max, les places libres sont prises par des bots). L'hôte choisit les 2 chasseurs (un joueur, un bot ou au hasard).
- **Skins du chasseur** : Classique, 6-7 (bleu), PROUT (marron), HAMRA (rouge et noir). Le skin se choisit dans le menu et apparaît sur le personnage et sur le fusil.
- Toutes les 45 s, tous les cacheurs tremblent pendant 1 s et font un petit bruit.
- Les vitres bloquent le passage mais pas la vue ni les balles.

## Commandes

- ZQSD / WASD : se déplacer · Maj : courir · Espace : sauter
- Cacheur : E pour se transformer en l'objet visé, F pour verrouiller la rotation (molette pour tourner), T pour provoquer
- Chasseur : clic pour tirer, R pour recharger. Tirer sur un vrai meuble coûte des points de vie.
- Tab : liste des joueurs · Échap : pause

## Technique

Un seul fichier `index.html` : Three.js pour la 3D, PeerJS pour le multijoueur (connexion directe entre navigateurs).
Pour tester en local sous Windows : `powershell -ExecutionPolicy Bypass -File serve.ps1`, puis ouvrir http://localhost:8080.
