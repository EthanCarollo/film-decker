# FilmDecker Doc

## FilmDecker est une plateforme de partage et de notation de films en tout genre, connecté à une api faite par "TheDropIndustry".
## Le slider en bas à gauche permet de switch entre le mode Offline et Online de l'api (+100 films).

### Les films - Comment ca marche
####   - Un film contient : un nom, une description, un auteur, une catégorie, une image, une vidéo youtube (bande annonce)
####   - Cliquer sur un film pour en savoir plus sur lui
####   - Cliquer sur l'un des deux boutons (like ou dislike) pour liker ou disliker le film
####   - Cliquer sur la poubelle fera apparaitre un menu qui vous demandera si vous voulez supprimer ou non le film en question
####  - Cliquer sur le crayon ouvrira le menu sur la droite qui vous permet de modifier le film (toutes les informations se remplissent par le film en question)
####   - Cliquer sur la croix permet d'ajouter le film dans la "User Collection"

### Les outils - Comment ca marche
####   - Les outils sont ceux qui sont en bas à droite de l'application, ils comprennent (de bas en haut):
####       - Rechercher spécifiquement : Recherche à partir de paramètre spécifique, et permet de trier de manière plus spécifique
####           - L'outil recherche spécifique permet de trier et de chercher par catégorie (choix pris pour avoir une meilleure et plus propre UI)
####       - Ajouter un film : Ajoute un film (nécessite un url pour l'image et un url youtube pour la vidéo)
####       - Modifier un film : Modifie un film à partir de son ID (Se fait automatiquement en cliquant sur le crayon dans un film)
####       - Ajouter une catégorie : Ajoute une catégorie en choisissant son nom.
####       - Supprimer une catégorie : Supprime la catégorie choisie.
####       - Modifier une catégorie : Modifie le nom de la catégorie de films de la catégorie choisie.

### User Collection - Comment ca marche
####   - La collection s'ouvre avec la petite fleche présente sur la gauche de l'écran
####   - Ajouter un film à la collection via l'icone + qui apparait lorsque l'on clique sur une affiche en bas à droite
####   - Cliquer sur le film dans la naviguation de collection sur la gauche pour le rechercher et acceder à ses informations
####  - Passer la souris sur un film pour voir apparaitre une croix et le supprimer

### Recommandations - Comment ca marche
####   - Au lancement, si vous n'avez rien dans votre "User Collection", les "Recommandations" seront purement aléatoire
####   - Lorsque vous avez des films dans votre "User Collection", les "Recommandations" se baseront sur la catégorie dominante de votre "User Collection"
####   - Si les "Recommandations" ne vous plaisent pas, vous pouvez toujours les actualisé avec l'icon en haut à droite qui se mettra à tourner au clic
####   - Appuyer sur le bouton rechercher pour obtenir la case du film apparaissant dans les recommandations

### Divers
####   - La barre de recherche permet de mettre en évidence le premier element qui a été trouvé dans les films (c'est le texte au dessus des affiches)
####   - La flèche tout en bas permet de remonter en haut de la page, elle apparait uniquement si + de 10 films sont affiché.
####   - Le offline et online mode peuvent etre considérer comme un light et un dark mode.
####       - PS : la div des Recommandations possède un before qui permet de faire un effet glow qui se à une animation infini qui tourne
####   - Au hover, sur desktop, les films changent rotation dans l'espace (pas de three.js juste du css perspective)
####   - Il y a une petite lumière en haut à droite avec des particules pour combler le vide, elle est marrante
####   - Au changement de mode le logo change et on peut voir apparaitre un ".online" sur la version en ligne.
