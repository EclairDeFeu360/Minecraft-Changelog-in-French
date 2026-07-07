# Guide de traduction des changelogs

## Objectif

Le `README.md` est un résumé français fidèle du changelog officiel de Minecraft Java Edition. Il ne s'agit pas d'une traduction exhaustive ligne par ligne : retenir les changements utiles, regrouper les détails proches et rester concis.

## Ton et rédaction

- Employer un ton neutre, direct et factuel, sans introduction promotionnelle ni commentaire éditorial.
- Privilégier des puces courtes comme `Ajout de...`, `Modification de...` ou une phrase simple au présent/passé composé.
- Conserver une formulation assez proche de la source. Ne pas embellir le texte et ne pas ajouter d'explications absentes du changelog.
- Regrouper dans une seule puce les changements très proches lorsque cela améliore la lisibilité.
- Résumer chaque changement par son effet principal. Omettre les comparaisons avec l'ancien comportement, les justifications techniques, les conséquences secondaires et les remarques sur les performances lorsqu'elles ne sont pas indispensables.
- Éviter les sous-puces explicatives pour un changement qui tient clairement en une phrase.
- Ne pas inclure la section `Known Issues` de l'article officiel.
- Ne pas mettre de point final aux puces.
- Pour l'image du changelog, baser la description française sur le texte `alt` officiel lorsqu'il est disponible.
- Corriger soigneusement l'orthographe, les accents, les accords et la ponctuation françaises.

## Choix de traduction

- Conserver les noms de commandes, champs, composants, types, tags, chemins et identifiants techniques en anglais et entre backticks.
- Traduire en français naturel les réglages et concepts destinés aux joueurs ou aux administrateurs lorsqu'ils ne sont pas cités comme identifiants techniques, par exemple `white-list` devient `liste blanche`.
- Conserver les libellés `DP version`, `RP version` et les numéros de version.
- Employer les termes techniques déjà utilisés dans le dépôt, notamment `data pack`, `pack de ressources`, `source de slots`, `élément de terrain`, `règle de matériau`, `placeur de feuillage`, `placeur de tronc` et `décorateur d'arbre`.
- Garder les noms officiels ou communautaires de Minecraft lorsqu'une traduction française établie existe.
- Utiliser `bugs fixés` dans le lien final, conformément au style historique du dépôt.
- Ne pas traduire le titre de version, par exemple `Minecraft 26.3 Snapshot 1`.

## Structure habituelle

1. Image du changelog avec une description française factuelle.
2. Titre lié à l'article officiel.
3. Changements de gameplay et de contenu.
4. Section `DP version`.
5. Section `RP version`.
6. Autres versions de protocole, si nécessaire.
7. Lien final indiquant le nombre de bugs fixés.

Les sous-puces servent aux ensembles techniques ou aux changements qui partagent un même sujet. Les identifiants techniques restent en Markdown inline code.

Dans les sections techniques, indiquer la fonction d'un nouveau composant ou champ sans énumérer tous ses paramètres, sauf si ceux-ci constituent le changement principal. Quand un identifiant technique entre backticks est ajouté, toujours préciser brièvement ce qu'il fait. Omettre les modifications de rapports internes ou de formats secondaires qui n'apportent rien au résumé. À l'inverse, accompagner les tags ou identifiants peu explicites d'une courte description française de leur rôle.

## Méthode pour les prochains changelogs

- Consulter l'article officiel et vérifier le nombre de bugs au moment de la rédaction, car ce total peut être corrigé après la publication.
- Examiner quelques changelogs précédents dans l'historique Git avant de rédiger.
- Respecter les choix déjà présents dans le brouillon de l'utilisateur; ne reformuler que pour corriger une faute, lever une ambiguïté ou harmoniser le style.
- Ne modifier ni remplacer `image.png` sauf demande explicite.
- Avant de terminer, relire le français et exécuter `git diff --check`.
