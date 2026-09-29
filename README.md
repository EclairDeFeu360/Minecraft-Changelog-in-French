![Steve chevauche un cheval au soleil couchant.](https://github.com/EclairDeFeu360/Minecraft-Changelog-in-French/blob/26.4-snap2/image.png)
## [Minecraft 26.4 Snapshot 2](https://www.minecraft.net/en-us/article/minecraft-26-4-snapshot-2)
- Lorsque Transparence améliorée est activée, le ciel et les nuages situés derrière le terrain se fondent maintenant dans le brouillard de distance d'affichage, masquant la limite entre le ciel et le terrain
- Dans l'Overworld, la moitié inférieure du ciel masque maintenant les astres, comme le soleil, la lune et les étoiles
- L'écran de débogage F3 a été remanié pour être plus lisible et compréhensible
- DP version 122.1 :
  - Ajout de l'attribut d'environnement `minecraft:visual/has_sky_occluder`, qui détermine si une partie du ciel doit être masquée par la couleur du brouillard ; il est activé par défaut dans l'Overworld et désactivé dans le Nether et l'End
  - Ajout du prédicat `below_heightmap`, qui vérifie si une position est située sous la valeur de la carte de hauteur indiquée par le champ `heightmap`
- RP version 99.0 :
  - Le shader `screenquad.vsh` a été renommé en `screentriangle.vsh` afin d'indiquer qu'il représente un triangle
  - Le shader `clouds.fsh` ne prend plus directement en charge la transparence indépendante de l'ordre ; ajout de `blit_clouds.fsh`, qui transfère les nuages depuis une cible hors écran vers les cibles de transparence
  - Ajout des shaders `sky_occluder.vsh` et `sky_occluder.fsh`, qui masquent une partie du ciel avec la couleur du brouillard selon l'environnement
- [53 bugs fixés](https://mojira.dev/?project=MC&fix_version=26.4%20Snapshot%202)
