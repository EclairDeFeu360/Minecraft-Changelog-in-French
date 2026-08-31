![Noor est assis sur un coussin orange dans un camp abandonné de la forêt tachetée.](https://github.com/EclairDeFeu360/Minecraft-Changelog-in-French/blob/26.3-snap9/image.png)
## [Minecraft 26.3 Snapshot 9](https://www.minecraft.net/en-us/article/minecraft-26-3-snapshot-9)
- Ajout de réglages distincts pour la distance d'affichage et la distance de simulation des Realms, avec une distance d'affichage maximale de 25 chunks
- Les Endermen subissent maintenant les dégâts des projectiles lorsqu'ils chevauchent une entité
- Les Endermen et les Shulkers ne peuvent plus se téléporter sur la bedrock
- Sur macOS, ajout de l'option Émulation du clic droit, qui permet d'utiliser Contrôle + clic gauche comme un clic droit
- DP version 117.0 :
  - Les progrès racines visibles doivent maintenant définir un arrière-plan, qui ne peut être utilisé que par ces progrès
  - La source de slots `minecraft:group` et la fonction de butin `minecraft:sequence` ne peuvent utiliser une définition directe que dans un fichier de premier niveau
  - Le champ `summands` du fournisseur de nombres `minecraft:sum` a été renommé en `operands` et doit contenir au moins une valeur
  - Ajout des fournisseurs de nombres `minecraft:product`, `minecraft:minimum`, `minecraft:maximum` et `minecraft:average`, qui renvoient respectivement le produit, la valeur minimale, la valeur maximale et la moyenne de leurs opérandes
  - Ajout du tag de blocs `#uncarvable`, qui définit les blocs que les sculpteurs ne peuvent jamais creuser
  - Ajout des tags de blocs `#dangerous_for_teleportation`, `#cat_does_not_teleport_to`, `#enderman_does_not_teleport_to`, `#shulker_does_not_teleport_to` et `#consumable_does_not_teleport_to`, qui contrôlent les blocs interdits ou dangereux selon le type de téléportation
  - Ajout du tag d'objets `#brewing_potion_inputs`, qui définit les objets pouvant être placés dans les emplacements de potions de l'alambic
  - Ajout des tags de potions `#douses_fire`, `#hurts_water_sensitive_entities`, `#extinguishes_entities` et `#rehydrates_axolotls`, qui définissent respectivement les potions éteignant le feu, blessant les entités sensibles à l'eau, éteignant les entités et réhydratant les axolotls
- [50 bugs fixés](https://mojira.dev/?project=MC&fix_version=26.3%20Snapshot%209)
