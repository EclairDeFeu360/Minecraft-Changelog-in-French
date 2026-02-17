![Deux pandas, un adulte et un bébé, se tiennent sur une colline herbeuse avec, en fond, le soleil couchant.](https://github.com/EclairDeFeu360/Minecraft-Changelog-in-French/blob/26.1-snap8/image.png)
## [Minecraft 26.1 Snapshot 8](https://www.minecraft.net/en-us/article/minecraft-26-1-snapshot-8)
- L’ardoise des abîmes peut être directement transformée en pierre, ardoise polie, ardoise taillée et ardoise carrelée dans le tailleur de pierre
- La roche peut être directement transformée en pierre dans le tailleur de pierre
- Le raccourci clavier Ctrl + Récupérer, sur un joueur ou un mannequin, affiche le même résultat que la commande `/fetchprofile` sur cette même entité
- L’IME est désormais affiché en jeu au-dessus de tous les champs de texte
- Le mode plein écran n’est plus en mode exclusif
- Ajout du champ `detailed_memory` sur l’écran de débogage pour afficher des informations sur la mémoire utilisée
- La taille du tas initiale, dans les options de la JVM, est par défaut à 2 Go
- DP version 99.2 :
  - Ajout de la sous-commande `entity` dans la commande `/fetchprofile` pour récupérer les informations du profil du joueur ou du mannequin
  - Le composant de texte `minecraft:nbt` a été modifié :  
    - Les tags résolus sans interprétation sont décorés
    - Le contenu des champs `nbt` et `block` n’est pas silencieusement ignoré lorsque la résolution échoue
    - Ajout du champ `plain` pour retirer la décoration d’un texte
- RP version 81.1 :
  - Les textures des chevaux au dos noir ont été modifiées
  - Les modèles et les textures des bébés panda, hoglin, zoglin, arpenteur et renifleur ont été modifiés
  - Ajout du sprite `gui/sprites/widget/preedit.png` pour l’IME
- [21 bugs fixés](https://mojira.dev/?project=MC&fix_version=26.1%20Snapshot%208)