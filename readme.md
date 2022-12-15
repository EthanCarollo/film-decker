# FilmDecker Doc

# FilmDecker est une plateforme de partage et de notation de films en tout genre, connecté à une api faite par "TheDropIndustry".
# Le slider en bas à gauche permet de switch entre le mode Offline et Online de l'api.

# Les films - Comment ca marche
#   - Un film contient : un nom, une description, un auteur, une catégorie, une image, une vidéo youtube (bande annonce)
#   - Cliquer sur un film pour en savoir plus sur lui
#   - Cliquer sur l'un des deux boutons (like ou dislike) pour liker ou disliker le film
#   - Cliquer sur la poubelle fera apparaitre un menu qui vous demandera si vous voulez supprimer ou non le film en question
#   - Cliquer sur le crayon ouvrira le menu sur la droite qui vous permet de modifier le film (toutes les informations se remplissent par le film en question)
#   - Cliquer sur la croix permet d'ajouter le film dans la "User Collection"

# Les outils - Comment ca marche
#   - Les outils sont ceux qui sont en bas à droite de l'application, ils comprennent (de bas en haut):
#       - Rechercher spécifiquement : Recherche à partir de paramètre spécifique, et permet de trier de manière plus spécifique
#           - L'outil recherche spécifique permet de trier et de chercher par catégorie (choix pris pour avoir une meilleure et plus propre UI)
#       - Ajouter un film : Ajoute un film (nécessite un url pour l'image et un url youtube pour la vidéo)
#       - Modifier un film : Modifie un film à partir de son ID (Se fait automatiquement en cliquant sur le crayon dans un film)
#       - Ajouter une catégorie : Ajoute une catégorie en choisissant son nom.
#       - Supprimer une catégorie : Supprime la catégorie choisie.
#       - Modifier une catégorie : Modifie le nom de la catégorie de films de la catégorie choisie.

# User Collection - Comment ca marche
#   - La collection s'ouvre avec la petite fleche présente sur la gauche de l'écran
#   - Ajouter un film à la collection via l'icone + qui apparait lorsque l'on clique sur une affiche en bas à droite
#   - Cliquer sur le film dans la naviguation de collection sur la gauche pour le rechercher et acceder à ses informations
#   - Passer la souris sur un film pour voir apparaitre une croix et le supprimer

# Recommandations - Comment ca marche
#   - Au lancement, si vous n'avez rien dans votre "User Collection", les "Recommandations" seront purement aléatoire
#   - Lorsque vous avez des films dans votre "User Collection", les "Recommandations" se baseront sur la catégorie dominante de votre "User Collection"
#   - Si les "Recommandations" ne vous plaisent pas, vous pouvez toujours les actualisé avec l'icon en haut à droite qui se mettra à tourner au clic