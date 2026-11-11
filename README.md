![Noor combat l'Ender Dragon à l'arbalète au milieu de son souffle.](https://www.minecraft.net/content/dam/minecraftnet/article-asset/2026/minecraft-26-4-snapshot-8/new-article-hero-image.jpg)
## [Minecraft 26.4 Snapshot 8](https://www.minecraft.net/en-us/article/minecraft-26-4-snapshot-8)
- Ajout du javanais et du chavacano de Zamboanga
- Correction des déplacements de l'Ender Dragon
- Regroupement de la neige et des blocs de neige avec les briques de neige dans l'inventaire Créatif
- Les morts-vivants sont immunisés au Gel
- Réduction des dégâts des glaçons
- L'archétype froid du cube de soufre ne flotte plus
- DP version 127.0 :
  - La plupart des problèmes de validation n'empêchent plus le chargement des éléments
  - Les appels récursifs et les valeurs contextuelles requises manquantes constituent des erreurs pouvant empêcher le chargement des packs ou la compilation des commandes
  - Séparation du contexte `minecraft:command` en `minecraft:command_predicate` pour les prédicats et `minecraft:command_modifier` pour les modificateurs d'objets
  - Ajout d'un argument de commande acceptant les expressions régulières
  - Ajout des tags de blocs `#triggers_ambient_ice_block_sounds` et `#triggers_ambient_ice_crystal_sounds`, déclenchant respectivement les sons ambiants de la glace et des cristaux de glace
- RP version 103.0 :
  - Ajout de la texture d'onglet sélectionné `friends/tab_focused.png` et du son `entity.frostbite.throw` des lancers de glaçons des Givrés
  - Adaptation des shaders de transparence et du masque d'eau des bateaux aux sous-passes
- La synchronisation des positions des entités transmet la rotation de tête en pleine précision
- [43 bugs fixés](https://mojira.dev/?project=MC&fix_version=26.4%20Snapshot%208)
