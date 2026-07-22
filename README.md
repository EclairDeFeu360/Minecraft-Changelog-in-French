![Un mouton noir, dans une forêt tachetée, contemple l'horizon.](https://github.com/EclairDeFeu360/Minecraft-Changelog-in-French/blob/26.3-snap5/image.png)
## [Minecraft 26.3 Snapshot 5](https://www.minecraft.net/en-us/article/minecraft-26-3-snapshot-5)
- DP version 112.0 :
  - Les listes d'éléments et les tags peuvent maintenant mélanger les valeurs directes et les références
  - Suppression des champs `extra_rare_growths` et `catalyst_chance` du type d'élément de terrain `minecraft:sculk_patch`
- RP version 93.0 :
  - La définition `B3D_IS_ZERO_TO_ONE` a été renommée en `RENDERPEARL_IS_ZERO_TO_ONE`
  - Les shaders OpenGL sont maintenant compilés par ShaderC, comme ceux utilisant Vulkan
  - Les inclusions de shaders utilisent maintenant `#include` à la place de `#moj_import`
  - Les entrées et sorties de shaders doivent maintenant préciser leur emplacement, utilisé pour faire correspondre les sorties de vertex aux entrées de fragment
  - Ajout de la définition `RENDERPEARL_INSTANCE_INDEX_INCLUDES_BASE_INSTANCE`, qui indique si `gl_InstanceIndex` inclut l'instance de base selon le fonctionnement de Vulkan ou d'OpenGL
- [22 bugs fixés](https://mojira.dev/?project=MC&fix_version=26.3%20Snapshot%205)
