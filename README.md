![Un cube de soufre qui a absorbé un bloc de magma dans une grande source sulfureuse située dans un biome des badlands, au coucher du soleil. Un geyser jaillit de la source.](https://github.com/EclairDeFeu360/Minecraft-Changelog-in-French/blob/26.2-snap6/image.png)
## [Minecraft 26.2 Snapshot 6](https://www.minecraft.net/en-us/article/minecraft-26-2-snapshot-6)
- Ajout de l'archétype de cube de soufre `Slow Bouncy` et `Hot`
- Ajout des langues Gallo, Ouzbek et Võro
- Ajout de l'avancement "Ho ho"
- Modification des sources suflureuses et des biomes de cavernes de soufre
- Les geysers émettent des vibrations
- DP version 105.0 :
  - Ajout du champ `is_3d` dans la règle de condition de surface `noise_threshold`, qui définit si le bruit doit être évalué en 3D
  - Suppresion de la règle de surface `noise_gradient`
  - Ajout de l'élément de terrain configuré `minecraft:weighted_random_selector`, qui sélectionne un élément de terrain aléatoire parmi une liste pondérée d'éléments de terrain
  - La valeur maximal du champ `column_radius` de l'élément de terrain configuré `minecraft:large_dripstone` est de 16
  - Ajout des champs `level_test_distance` et `max_level_deviation` dans l'élément de terrain configuré `minecraft:root_system`, qui définissent la distance maximale et la profondeur maximale qui seront testées pour placer des racines
  - Modification du processeur de structure `minecraft:block_rot`
  - Ajout des tags d'objet `#sulfur_cube_archetype/hot` et `#sulfur_cube_archetype/slow_bouncy`, qui definissent quels blocs absorbés par un cube de soufre donneront un archétype `hot` ou `slow_bouncy`
- RP version 86.2 :
  - Le son des éruptions de geysers a été modfié
- [41 bugs fixés](https://mojira.dev/?project=MC&fix_version=26.2%20Snapshot%206)