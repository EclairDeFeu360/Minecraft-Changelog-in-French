![Ari est assis sur une balançoire avec un coussin sous un chêne près d'un village. À l'arrière-plan, Efe échange des émeraudes avec le cartographe sous la surveillance d'un golem de fer.](https://github.com/EclairDeFeu360/Minecraft-Changelog-in-French/blob/26.3-snap8/image.png)
## [Minecraft 26.3 Snapshot 8](https://www.minecraft.net/en-us/article/minecraft-26-3-snapshot-8)
- Les propriétaires de Realm peuvent maintenant créer et gérer jusqu'à 5 codes d'invitation
- Les cartes de cité antique enfouie, de puits de mine enfoui et de camp abandonné ont été renommées
- Les coussins sont maintenant détruits uniquement lorsqu'ils sont entièrement recouverts par des blocs causant la suffocation
- Les nouveaux échanges débloqués lorsqu'un villageois progresse dans sa profession sont maintenant actualisés pendant l'échange
- Modification de l'écran Options du monde :
  - Ajout du réglage Mode de jeu personnel, qui définit le mode de jeu du joueur actuel
  - Ajout du réglage Forcer le mode de jeu, qui impose aux autres joueurs le mode de jeu par défaut du monde
- DP version 116.0 :
  - Suppression du type d'élément de terrain `minecraft:desert_well`
  - Ajout du champ `processors` au type d'élément de terrain `minecraft:template`, qui applique une liste de processeurs de structure au modèle
  - Ajout du modificateur de placement `minecraft:randomly_selected`, qui sélectionne aléatoirement un modificateur dans une liste
  - Ajout du prédicat de bloc `minecraft:volume_match`, qui vérifie que tous les blocs d'un volume correspondent à un prédicat donné
- RP version 96.0 :
  - Suppression des shaders `core/text_background.fsh` et `core/text_background.vsh`, l'arrière-plan des entités d'affichage de texte utilisant maintenant les shaders de texte
  - Suppression de la définition `OIT_FORCE_ZERO_DEPTH`, devenue inutile pour le texte visible à travers les blocs
- [48 bugs fixés](https://mojira.dev/?project=MC&fix_version=26.3%20Snapshot%208)
