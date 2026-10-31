# Sauve la reine : dessine ! 👑✏️

Jeu de réflexion et de physique gratuit. Trace **un seul trait** pour protéger la reine des abeilles, rochers, canons, flèches, eau et lave, et tiens 10 secondes.

**Jouer :** https://troplife56-source.github.io/sauve-la-reine-dessine/

## Contenu

- 35 niveaux, avec un mode Expert pour chacun
- 8 costumes pour la reine, à débloquer avec les étoiles
- Encres spéciales, chat royal à protéger, dangers qui bougent, clous, surprises
- 4 fins rares à découvrir
- Jouable au doigt sur téléphone et à la souris sur ordinateur
- Progression sauvegardée dans le navigateur

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | Le jeu complet (HTML, CSS et JavaScript dans un seul fichier) |
| `preview.png` | Image d'aperçu affichée quand on partage le lien (1200 × 630) |
| `README.md` | Ce fichier |

Le jeu utilise [Matter.js](https://brm.io/matter-js/) 0.19.0, chargé depuis cdnjs.

## Mettre en ligne sur GitHub Pages

1. Sur GitHub, crée un dépôt public nommé **`sauve-la-reine-dessine`**.
2. Clique sur **Add file → Upload files** et dépose `index.html`, `preview.png` et `README.md`. Valide avec **Commit changes**.
3. Va dans **Settings → Pages**. Sous *Build and deployment*, choisis **Deploy from a branch**, puis la branche **main** et le dossier **/ (root)**. Clique sur **Save**.
4. Attends 1 à 2 minutes : le jeu est en ligne à l'adresse
   `https://troplife56-source.github.io/sauve-la-reine-dessine/`

### Si tu choisis un autre nom de dépôt

L'adresse de l'image d'aperçu est écrite en entier dans `index.html`. Remplace `sauve-la-reine-dessine` par le nom de ton dépôt dans les lignes `og:url`, `og:image` et `twitter:image`. Sinon, l'image ne s'affichera pas quand tu partages le lien.

### Mettre à jour le jeu

Remplace `index.html` par la nouvelle version (même nom de fichier), puis valide. Les joueurs gardent leur progression.
