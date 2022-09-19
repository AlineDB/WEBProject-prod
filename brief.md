# Cahier des charges

## Entreprise

HEPL bachelier techniques graphiques option web

## Besoins

Les besoins consistent en la promotion du cursus du bachelier en techniques graphiques option infographie orientation web.
Pour cela il est opportun de créer un site de présentation dit vitrine.

## Objectifs

Son objectif étant d'attirer des étudiants et d'informer ceux-ci un maximum et ce sur 4 volets:

 ### 1) Toutes les infos utiles qu'un (futur) étudiant à besoin !

Le campus, le cursus, les profs, les cours, la HEPL, les ECTS ... toutes les infos seront présentes avec des exemples.

 ### 2) Les débouchés, métiers grâce aux retours des anciens étudiants

Pour chaque cours, un exemple de projet réalisé par un étudiant afin d'avoir du concret mais aussi une page projets reprenant tous les projets année par année.
Des témoignages d'anciens étudiants, reprenant leur parcours, leurs travaux, mais aussi leur métier afin de faire le lien entre le cursus et un job.

 ### 3) L'échange via un forum et les actus 

Pouvoir poser des questions, échanger avec des (anciens ou futurs) étudiants et/ou les professeurs est une partie importante pour s'informer
et faire vivre le site. Cela permettrait de répondre à des questions plus spécifiques ou échanger des connaissances : le monde du web évolue !

 ### 4) Les tutos et glossaire

Afin d'aider ou de préparer les (futurs) étudiants, rien de tel que quelques tutos pour entamer leur apprentissage ou
quelques notions et mots spécifiques du métier.

## Public cible

(Jeunes) (futurs) étudiants à la recherche d'un cursus en web

Professionnels à la recherche d'informations sur le cursus ou de stagiaires

Entreprises cherchant stagiaires

## Stratégie

Les stratégies misent en place permettent d'atteindre les objectifs et le public cible.

Pour cela, le site doit être vivant et proposer du contenu concret comme :

- Montrer les réalisations des étudiants (fiche individuelle avec cahier des charges, étapes, liens GIT/XD/...). Ce qui permet de voir à quoi servent les cours et quel sont les compétences acquisent dans chacun de ceux-ci.


- Visibilité des anciens étudiants (fiche individuelle CV/interview/..., débouchés/métiers). Permet de mieux cerner les débouchés possibles, quelles compétences pour quel métier, ... Voir que tous les cours amène au monde du travail.


- Réseau entreprises (présentations + métiers + offre stage). Cette page permet de présenter les entreprises avec qui nous collaborons mais aussi de partager des offres de stage.


- Actualités (event) + possibilité d'épingler à la page d'accueil une actu. Les actus et événements du cursus afin de suivre presque en temps réel ce qui se passe.


- Forum/blog (filtre: catégories, auteurs, date). Intéragir, poser des questions, échanger sur une matière avec des étudiants ou des profs permet de montrer que le cursus est ouvert et accessible à tous.
On peut aussi l'utiliser afin de communiquer des notions de cours ou des infos utiles.


- Newsletters (inscription). Recevoir les dernières actus, derniers articles du cursus permet de garder ses utilisateurs informés et de les faire revenir sur le site.


- Présenter HEPL (présentation, FAQ, réglementation, ...). Beaucoup d'informations utile pour la HEPL et plutôt orienté structure : crédits, prix, services, ... Des informations de base et pertinentes.


- Form contact (structuré selon profil et demande -> étudiants/entreprises/autres). Le formulaire permet d'entrer en contact avec les admin. Il sera modulable selon le profil de l'utilisateur. Si c'est un étuidant qui souhaite juste plus d'information ou une entreprise qui souhaite
publier une offre de stage, il n'y aura pas les mêmes champs de formulaire affiché.


- Infos pratiques et valeurs. Des réponses à des questions plutôt d'organisation ou de méthodologie dans certaines pages comme les cours ou dans la fiche perso d'un professeur par exemple


- Présenter programme (tableau, fiche ECTS). Cela était déjà compliqué de comprendre les crédits, le fonctionnement ect ... mais avec le décret paysage, il vaut mieux bien expliquer comment fonctionne le bachelier et les moments clés.


- Présentation profs (fiche perso). Que serait le cursus sans ses profs ? Les présenter autrement que comme de "simple" prof avec leur ligne conductrice, leur savoir-faire, ...


- Partager certains contenus. Les utilisateurs aiment partager ce qu'ils trouvent intéressants, pertinents ou encore amusants, importants, ... On doit intégrer la notion de partage sur les réseaux.


- Apprendre (glossaire et tutos). Outre informer il est important aussi de soutenir et d'aider. Proposer quelques tutos ou un glossaire afin de soutenir mais aussi de montrer à quoi s'attendre lors du cursus me semble pertinent.
On pourrait également imaginer des formulaires de test à la fin d'un tuto avec un score enregistré dans le profil. Cela permet de voir les progrès et peut-être par la suite un suivi.


## Techniques

Le site doit :

- être multilingue (EN, FR, ALL, NL)
- disposer des Standarts SEO
- utiliser différents médias (vidéos, photos, API, ...)
- Etre compatible avec tous navigateurs + version mobile
- avoir un test d'Accessibilité AA minimum, si possible AAA
- Avoir des Images responsive (optimisation, taille, ...)
- Contenir un Champs de recherche
- Avoir une Pagination
- Pouvoir Filtrer quand il y a beaucoup de contenu d'un même type (articles, projets, ...)
- Contenir les RGPD, conditions d'utilisation, ... les aspects légaux en somme.
- Avoir une console d'Administration et des rôles
- Utiliser Laravel (framework)
- Contenir du CSS (à voir)
- Contenir du Javascript (à voir)
- Profil utilisateur (page profil avec edit/delete)

## Graphisme

- Libre
- Utilisation du logo HEPL

## Arborescence

    Accueil ->
            Cursus ->
                      Présentation ->
                                      Grille cours ->
                                                       Cours ->
                                                                 Présentation
                                                                 Méthodologie
                                                                 Projets étudiants -> 
                                                                                        Fiche individuelle (présentation, photos, étapes)
                                                                 Programmes utilisés
                      Nos anciens ->
                                    Fiche individuelle (présentation, projets, métiers, anecdotes cursus, conseil)
                                    Fiche par année scolaire (diplômés, travaux choisis projets clients (lien vers le projet), actus cette année-là (lien), ...)
                      Nos profs ->
                                    Fiche individuelle (présentation, cours donnés, citations/phrases fétiche)
            HEPL/Campus ->
                      Présentation HEPL
                      Présentation Campus Parc Marêts (salles, organisation sandwich, bibli, ...)
                      Réglement
                      Explication ECTS
                      Services (CE, service étudiants, qualité de vie, aides financières, salle études vacances)
                      FAQ
                        !!certaines infos sont directement sur le site HEPl, faire un résumé et faire un lien vers la page concernés poiur + d'infos
            Blog ->
                      Forum d'échanges (lecture pour tous -> connecté pour poster/commenter/modif/delete)
                        !! Modération page spécifique post en attente, new post, ...
            Actus ->
                      Event , Articles
            Réseaux ->
                      Entreprises ->
                                    Fiche individuelle (présentation, métiers)
                      Offre stage
            Contact ->
                      Formulaire
            Tutos ->
                    Glossaire
                    CSS
                    HTML
                    JS
                    GitHub
                    PHP
                    Liens utiles (Behance, Alsacreation, W3C, ...)
            Compte -> 
                    Connexion
                    Déconnexion
                    Profil (update/delete) nom, mail,photo profil, mdp
                    Selon rôle voir si ajoute page administration avec contact entre modérateurs/admin/autres et notifications directement via cette page ou pas
                    


## Mots-clés

bachelier, web, école, design, études supérieures, 


## Dates-clés

19/09 cahier des charges
26/09 wireframe texte navigation
3/10 Wireframe
10/10 Design

Jury janvier 2023 : présentation du projet terminé

