![Une vue des grottes de soufre, où des cubes de soufre rebondissent autour des speleotheme de soufre.](https://github.com/EclairDeFeu360/Minecraft-Changelog-in-French/blob/26.2-snap3/image.png)
## [Minecraft 26.2 Snapshot 3](https://www.minecraft.net/en-us/article/minecraft-26-2-snapshot-3)
- Ajout des spéléothèmes de soufre
- DP version 102.0 :
  - Les lits sont désormais des blocs uniquement, et non plus des entités de blocs
  - Le champ `type` des prédicats d'entité a été renommé en `minecraft:entity_type`
  - Les champs `minecraft:lightning`, `minecraft:fishing_hook`, `minecraft:player`, `minecraft:raider`, et `minecraft:sheep` ont été déplacés dans le sous-chemin `minecraft:type_specific/`
  - Le champ `minecraft:slime` a été remplacer par `minecraft:cube_mob`
  - Ajout du sous-prédicat d'entité `minecraft:entity_tags` qui détecte un ou plusieurs tag
  - Les champ `can_place_feature`, `can_replace_with_air_or_fluid` et `can_replace_with_barrier` ont été ajoutés à l'élément de terrain `lake`, ils définissent quels blocs l'élément peut remplacer, quels blocs l'élément va remplacer par de l'air ou un fluide, et quels blocs l'élément va remplacer par un blocs de contour
  - Ajout du tag de blocs `#speleothems` qui définit les blocs qui sont des spéléothèmes
- RP version 86.0 :
  - Les textures des blocs de soufre, de cinabre et de leurs variantes ont été modifiées
  - Les sons des nautiles ont été modifiés
  - Les lits ont désormais leurs propre modèles et textures de blocs
  - Le modèles spécial d'objet `minecraft:bed` a été retiré
- [19 bugs fixés](https://mojira.dev/?project=MC&fix_version=26.2%20Snapshot%203)