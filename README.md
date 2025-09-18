Journal de bord 
Étape 1
1- J’ai cloné le projet depuis GitHub sur mon PC pour pouvoir le démarrer.(https://github.com/OpenClassrooms-Student-Center/booki-starter-code.git)

2- J'ai lié mon dépôt Git local à un dépôt distant sur GitHub en utilisant la commande git remote add origin (git@github.com:magniermickael/CreezLaPageAccueilPourAgenceDeVoyageAvecHTMLetCSS.git)

3- J'ai ajouté les fichiers et fait mon premier enregistrement sur la branche develop, en utilisant les commandes (git add .) et (git commit -m "Initialisation du projet").

4- J'ai poussé avec succès le contenu de ma branche de main sur GitHub en utilisant la commande (git push -u origin main).

5- J'ai créé ma branche de développement "develop" pour adopter le style de travail Gitflow avec la commande (git checkout -b develop).

6- J'ai poussé la branche de développement "develop" sur GitHub pour m'aligner sur la méthodologie Gitflow, en utilisant la commande (git push -u origin develop).

Étape 2
1- J'ai découpé la maquette Figma en sections et en blocs logiques, afin de pouvoir la traduire en structure HTML et en styles CSS.

Étape 3
1- J'ai créé une branche dédiée pour le développement du header en utilisant la commande (git checkout -b feature/header). 

2- J'ai intégré le header du projet en HTML et en CSS, en m'assurant que le code était propre et que la mise en page correspondait à la maquette. 

3- J'ai enregistré mes modifications pour le header en utilisant les commandes (git add .) et (git commit -m "feat: création du header").

4- J'ai soumis mon travail à mon mentor pour validation, et j'ai poussé la branche 'feature/header' sur GitHub (git push -u origin feature/header) en vue de notre rendez-vous


5-J'ai fusionné la branche feature/header sur la branche develop en utilisant les commandes (git checkout develop) et (git merge feature/header)

Étape 4
1- J'ai créé une nouvelle branche de développement afin d'isoler la création de la prochaine fonctionnalité (le formulaire de recherche), en utilisant la commande (git checkout -b feature/search-formulaire).

2- J'ai développé le formulaire de recherche en HTML et en CSS, en m'assurant que la structure et les styles correspondaient à la maquette.

3- J'ai enregistré mes modifications pour le formulaire de recherche, en utilisant les commandes (git add .) et (git commit -m "feat: création du formulaire de recherche") pour créer un nouveau point de contrôle dans l'historique de mon projet.

4- J'ai soumis mon travail à mon mentor pour validation, et j'ai poussé la branche feature/search-formulaire sur GitHub (git push -u origin feature/search-formulaire) en vue de notre rendez-vous.

5-J'ai fusionné la branche feature/header sur la branche develop en utilisant les commandes (git checkout develop) et (git merge feature/search-formulaire)

Étape 5
1- J'ai créé une nouvelle branche de développement (feature/filters) pour isoler la création de la prochaine fonctionnalité (la partie Filtres), en utilisant la commande (git checkout -b feature/filters)

2- J'ai développé le formulaire de recherche en HTML et en CSS, en m'assurant que la structure et les styles correspondaient à la maquette.

3- J'ai perfectionné l'icône d'information en ajustant sa couleur et ses dimensions et en créant un cercle autour avec un contour en CSS. Pour une harmonie visuelle parfaite et un résultat fidèle à la maquette.

4- J'ai enregistré mes modifications pour la partie Filtres, en utilisant les commandes (git add .) et (git commit -m "feat: création de la section des filtres").
5- J'ai soumis mon travail à mon mentor pour validation, et j'ai poussé la branche feature/filters sur GitHub (git push -u origin feature/filters) en vue de notre rendez-vous.

Étape 6
1- J'ai créé une nouvelle branche de développement (feature/card-hebergement) pour isoler la création de la prochaine fonctionnalité (la carte d'hébergement), en utilisant la commande (git checkout -b feature/card-hebergement)

2- J'ai développé la carte "hébergement" en HTML et en CSS, en m'assurant que le code était propre et que le rendu visuel correspondait aux maquettes.

Étape 7
1- J'ai ensuite dupliqué la carte pour en avoir six, comme sur la maquette, et j'ai remplacé le contenu pour le rendre conforme.

2- J'ai enregistré mes modifications pour la création des cartes d'hébergement, en utilisant les commandes (git add .) et (git commit -m "feat: création des cartes d'hébergement").

3- J'ai soumis mon travail à mon mentor pour validation, et j'ai poussé la branche feature/card-hebergement sur GitHub (git push -u origin feature/card-hebergement) 

4- J'ai fusionné la branche feature/card-hebergement sur la branche develop en utilisant les commandes (git checkout develop) et (git merge feature/card-hebergement).

5- J'ai poussé la branche develop mise à jour sur GitHub avec la commande (git push origin develop).

6- J'ai nettoyé les branches de fonctionnalités fusionnées en les supprimant à la fois en local et sur GitHub, en utilisant les commandes (git branch -d feature/header, git branch -d feature/search-formulaire, git branch -d feature/filters, git branch -d feature/card-hebergement ) et (git push origin --delete feature/header,git push origin --delete feature/search-formulaire, git push origin --delete feature/filters, git push origin --delete feature/card-hebergement).




Étape 8 

1- J'ai créé une nouvelle branche de développement (feature/activities) pour isoler la création de la prochaine fonctionnalité (la section "Activités"), en utilisant la commande (git checkout -b feature/activities).

2- J'ai développé la section "Activités à Marseille" en HTML et en CSS en m'assurant que la structure et les styles correspondaient à la maquette.

3- J'ai enregistré mes modifications pour la section "Activités", en utilisant les commandes (git add .) et (git commit -m "feat: création de la section des activités").

4- J'ai poussé la branche feature/activities sur GitHub (git push -u origin feature/activities).

4- J'ai fusionné la branche feature/card-hebergement sur la branche develop en utilisant les commandes (git checkout develop) et (git merge feature/activities).

5- J'ai poussé la branche develop mise à jour sur GitHub avec la commande (git push origin develop).

6- J'ai supprimé la branche de fonctionnalité feature/activities en local et sur GitHub en utilisant les commandes (git branch -d feature/activities) et (git push origin --delete feature/activities).


Étape 9 

1- J'ai créé une nouvelle branche de développement (feature/footer) pour isoler la création de la dernière fonctionnalité du projet (le footer), en utilisant la commande (git checkout -b feature/footer).

2- J'ai développé la section du footer en HTML et en CSS, en m'assurant que la structure et les styles correspondaient à la maquette.

3- J'ai enregistré mes modifications pour le footer, en utilisant les commandes( git add .) et (git commit -m "feat: création du footer").

4- J'ai soumis mon travail à mon mentor pour validation, et j'ai poussé la branche feature/footer sur GitHub (git push -u origin feature/footer) en vue de notre rendez-vous.

5- J'ai fusionné la branche feature/footer sur la branche develop en utilisant les commandes (git checkout develop) et ( git merge feature/footer).

6- J'ai poussé la branche develop mise à jour sur GitHub avec la commande (git push origin develop).

7- J'ai supprimé la branche de fonctionnalité feature/footer en local et sur GitHub en utilisant les commandes (git branch -d feature/footer) et (git push origin --delete feature/footer).



Étape 10

1- J'ai créé une nouvelle branche de développement (feature/responsive-fix) afin de corriger le dépassement des cartes d'hébergement pour les écrans de 1024px, en utilisant la commande (git checkout -b feature/responsive-fix).

2- J'ai mis à jour le code CSS pour ajuster la mise en page des cartes d'hébergement et des sections "Hébergements" pour qu'elles s'affichent correctement, en m'assurant que la maquette était respectée.

3- J'ai enregistré mes modifications avec les commandes  (git add .)  et (git commit -m "fix: ajustement responsive pour les écrans de 1024px").
4- J'ai poussé ma branche de correction sur GitHub avec la commande (git push -u origin feature/responsive-fix).
5- J'ai fusionné la branche feature/responsive-fix sur la branche develop pour intégrer mes corrections au projet principal avec les commandes (git checkout develop) et (git merge feature/responsive-fix).
6- J'ai poussé la branche develop mise à jour sur GitHub avec la commande (git push origin develop).
7- J'ai supprimé la branche de fonctionnalité feature/responsive-fix en local et sur GitHub pour maintenir la propreté de mon dépôt avec les commandes (git branch -d feature/responsive-fix) et (git push origin --delete feature/responsive-fix).

Étape 11

1- Le projet étant maintenant entièrement fonctionnel et responsive, j'ai créé une nouvelle branche de fusion (feature/fusion-final) pour préparer le projet final.(git checkout -b feature/fusion-final).
2- J'ai fusionné ma branche develop dans la nouvelle branche feature/fusion-final pour m'assurer que toutes mes modifications sont bien présentes et à jour.
3- J'ai ensuite fusionné la branche feature/fusion-final dans la branche main de mon dépôt local, afin de préparer le code final pour la publication.(git checkout main) et (git merge feature/fusion-final)
4- J'ai poussé la branche main mise à jour sur GitHub avec la commande (git push origin main), pour marquer la version finale du projet.
5- Pour finir, j'ai supprimé les branches de travail en local et sur GitHub pour ne garder que la branche main et la develop pour les prochaines évolutions, (git branch -d feature/fusion-final) et (git push origin --delete feature/fusion-final).


