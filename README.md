# Project Fishing Rogue-Lite

## **Résumé en une phrase du jeu** 
Jeu de pêche en VR avec des éléments de roguelike.

## Description écrite
Pour notre projet final, nous sommes partis de l'idée de créer un jeu de pêche, mais comme je trouvais l'idée trop simple, j'ai décidé que ce serait intéressant si notre jeu aurait des éléments de jeux rogue-lite afin d'en faire une expérience rejouable.

### Gameplay loop
Le gameplay loop du jeu tournerai autours des appats, le joueur commence avec un nombre fix d'appats, et lorsqu'il pêche un poisson, il y a des chances que le poisson consomme l'appat ou non, lorsque le joueur pêche un poisson, il reçoit des points d'expérience et il finit par monter de niveau, monter de niveau donne un choix au joueur entre 3 bonus passifs ou instantanés, les bonus passifs sont des amélioration statistiques des abilitées du joueur, par exemple une réduction des chances qu'un poisson consomme un appat ou bien une augmentation des chances d'avoir un poisson rare. Les bonus instantanés de leurs côtés sont plus quelque chose comme des appats ou de l'argent bonus que le joueur reçoit instantanément. L'argent est obtenue en vendant les poissons pêchés à un vendeur, et peut être utilisée pour acheter des appats, le prix des appats augmente à chaque jour, la durée des jours est une donnée qui risque de changer pendant le développement, mais pour le moment je pense que 5 minutes est une durée acceptable. Le but du jeu est donc de réussir à pêcher le plus de poissons possible avant de tomber à cours d'appats.

### Actions du joueur
Le joueur sera dans une barque dans un lac, une canne à pêche sera présente dans cette barque, le joueur peut la prendre pour tenter de pêcher un poisson en lançant sa ligne, pour le moment nous pensons utiliser l'engine de physique de unity pour déterminé la force du lancer, la canne à pêche elle-même ne sera pas un objet physique, lorsque le joueur la lâche, elle va simplement retourner à sa position originale, de cette manière on peut éviter une situation où le joueur est softlocked parce qu'il a lancé sa canne à pêche dans le lac. Pour les déplacements, des rames seront présentes dans le bateau, le joueur pourra intéragir avec celles-ci pour se déplacer en ramant physiquement, pour que ce soit convaincant, nous allons utiliser un mix des physiques de unity et de contrôles, si la barque était entièrement gérée par des physiques, il pourrait avoir une situation où elle chavire ou commence à secouer violement, ce qui causerait de la nausée pour le joueur cela n'est pas voulu dans notre jeu. Le joueur pourra également intéragir avec les menus pour vente et achats par le biais d'un pointeur.

### La pêche en elle-même
Pour l'action de pêcher en elle-même, je ne suis pas encore certain de ce que nous allons faire, mais mon idée en ce moment serait d'avoir à un bouton avec un certain tempo, lorsque l'on appui au bon moment, le poisson se rapproche, sinon il s'éloigne. Le jeu devienderai plus compliqué plus le poisson est rare.

## Moodboards

### Moodboard poissons
