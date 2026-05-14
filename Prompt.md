"Génère un jeu vidéo web complet en un seul composant React (TypeScript) avec Tailwind CSS. Le jeu est un Shoot 'em Up spatial 2D (horizontal), d'inspiration Star Wars avec une direction artistique Rétro / SNES 16-bit.

Instructions techniques principales :

Utiliser HTML5 Canvas (avec requestAnimationFrame dans un useEffect) pour un rendu fluide du jeu (60 FPS).

Gérer toute la logique (mouvements, collisions, tirs, particules) dans la boucle gameLoop.

Ajouter avec Tailwind et CSS un effet CRT / Scanlines par-dessus le rendu Canvas pour l'aspect rétro.

Design & HUD :

Fond noir avec un champ d'étoiles (3 couches de parallaxe simulée).

Un HUD fixe (hors du canvas, en HTML/Tailwind) affichant : Le Score au centre, la barre de santé des 2 joueurs (rouge et bleu), et le nombre de bombes (étoiles) pour chaque joueur.

Des menus esthétiques d'accueil et de Game Over.

Joueurs & Contrôles (Co-op locale à 2) :

Joueur 1 (Rouge type X-Wing) : Déplacement avec W/A/S/D (ou ZQSD), Tir avec Espace, Bombe avec C.

Joueur 2 (Bleu type A-Wing) : Déplacement avec les Flèches, Tir avec Entrée, Bombe avec Shift Droit.

Mécaniques d'Armement :

Tir chargé : Si le joueur maintient le bouton de tir, une jauge se remplit sous son vaisseau. Relâcher le bouton tire un projectile. Si chargé au maximum, le projectile est immense, rapide et inflige de lourds dégâts.

Bombes : Stock limité (3). Déclenche une attaque de zone géante qui détruit de multiples ennemis avec de grosses explosions (particules).

Ennemis & Combats :

Les ennemis (gris, design type TIE Fighter) apparaissent aléatoirement à droite et foncent vers la gauche.

Mini-boss : Apparition rare, taille double, design rouge foncé, possède sa propre barre de vie au-dessus de lui et oscille de haut en bas doucement.

Système de collision : Inflige de lourds dégâts destructeurs et génère un nuage de particules carrées lumineuses pour les explosions."
