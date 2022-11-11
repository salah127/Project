# Project

PROJET WEB:

- avoir un minimum de point pour la reserver(chaque salle a un nb pts min).



Notre but est de créer une plate-forme de reservation de salle par des utilisateurs.
et chaque salle contienne des ressources differents des autres et aussi ella ont des consition de reservation.

chaque salle a un nb max d'inviter dont un nb d'organisateur.

Quand un  utilisateur souhaite reserver une salle, il peut les visiter toutes sans avoir faire une inscription sur le site,par contre pour reserver une salle il faut: 

- etres connecter.
- avoir lu et approuvé qu'il est responsable de la salle  et ses ressources pendant sa reservation.
- etres dans la cathegorie acceptable pour la reservation (DÉBUTANT, AMATEUR, INTERMÉDIAIRE, CONFIRMÉ, EXPERT).
- elle est disponible sur le planning.

une fois lutilisateur reserve une salle, sa donne 5pts


un utilisateur peut réagir à une salle, il peut rajouter la salle à ses favoris, ecrire une remarque sur la salle (apres l'utilisation de la salle).

+pts : reserver une salle, ramener des ressources à la salle, aide à l'organisation.
-pts : casser des ressources, 





À la fin de chaque reservation, on va utiliser un système de points qui choisira le meilleur poste (interactions avec les autres utilisateurs) de la journée(qui a le plus grand nombre des points dans la même journée), semaine, mois, année.
l'utilisateur qui à le meilleur score de la journée va gagner de plus sur des points (pts_user), 


Pts_post =  ( Nb_like + (Nb_commentaire * 2) + (Nb_partage * 3) ) / Total_Pos_prec



à faire pour les prochaines séances du projet:
Creation de compte (inscription/connexion/modifier/supprimer).avec base de donner.
Creation de salles (creer (+1)/modifier/supprimer (-2)). avec la base de donner.
L'affichage des salles.
Reagir les posts.
Gerer et afficher les pts de chaque utilisateurs (rajouter des pts/deduire des pts).
gerer et afficher le classement actuel des utilisateurs(mondial,locale)
choisir et afficher l'utilisateur du jour(+10 pts_user), de la semaine               (+100pts_user), du mois(+1000pts_user), de l'année(Cadeau à gagner) et rajouter le bonus à l'utilisateur .
