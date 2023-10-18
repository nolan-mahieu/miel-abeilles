Introduction
Ce projet, intitulé "Le Miel et les Abeilles", est une simulation informatique basée sur l'évolution des connaissances d'une colonie d'abeilles à travers des générations. La simulation se déroule dans un environnement comprenant un arbre, des fleurs et des abeilles. La colonie d'abeilles s'est installée dans un arbre au milieu d'un champ de fleurs mellifères composé de pissenlits et de sauges des prés.

Contexte
Au début de la simulation, la colonie est constituée de 101 abeilles, y compris leur reine. Pour se nourrir, les abeilles doivent quitter la ruche à la recherche de nectar. Le champ de fleurs qui les entoure semble prometteur. Cependant, étant donné que les abeilles ne sont pas familières avec ce nouveau territoire, elles explorent le champ au hasard, butinent les fleurs et retournent à la ruche.

La reine de la ruche, connue pour son désir de prospérité et son élitisme, souhaite améliorer l'efficacité de sa colonie au fil du temps. Les abeilles les plus rapides à butiner l'ensemble des pissenlits et des sauges devront transmettre leur connaissance du champ de fleurs à leurs descendants. Les abeilles plus lentes seront remplacées par les nouvelles générations pour maintenir la colonie à 100 individus, y compris la reine.

Objectif du Projet
L'objectif de ce projet est de simuler l'évolution des connaissances des abeilles sur le champ de fleurs au fil des générations en utilisant un algorithme génétique. Le paramétrage de l'algorithme sera ajusté et justifié en fonction de différentes configurations, telles que le taux de mutation, le taux de reproduction, le système de reproduction, la métrique de calcul de la forme physique, etc.

De plus, la reine des abeilles, Maya, désire visualiser et présenter les résultats. Pour répondre à cette demande, le projet inclura la possibilité de générer des graphiques, notamment un graphique représentant le chemin de l'abeille la plus performante de la dernière génération, un arbre généalogique, et un graphique représentant l'évolution du temps de parcours moyen d'une génération d'abeilles au fil du temps.

Classes du Projet
Le projet est composé de deux classes principales :

Bee (Abeille)
La classe Bee représente une abeille.
Attributs :
route: Liste des coordonnées des fleurs à visiter.
HQ: Localisation de la ruche.
Méthodes :
d(ta, tb): Calcule la distance de Manhattan entre deux points.
get_score(): Calcule le score de l'abeille en fonction de la distance parcourue.
Hive (Ruche)
La classe Hive représente la colonie d'abeilles.
Attributs :
roster: Tableau de 100 abeilles.
Méthodes :
d(ta, tb): Calcule la distance de Manhattan entre deux points.
get_best_score(): Retourne le score de l'abeille la plus performante.
get_best_bee(): Retourne l'abeille la plus performante.
select(): Sélectionne les 50 meilleures abeilles.
crossover(bee_1, bee_2): Effectue le croisement de deux abeilles.
mutate(bee): Effectue une mutation d'une abeille.
evolve(): Gère l'évolution de la colonie.
Visualisation des Résultats
Le projet inclura des fonctionnalités permettant de visualiser les résultats de la simulation, y compris le chemin de la meilleure abeille, l'arbre généalogique, et l'évolution du temps de parcours moyen.

Exécution du Projet
Pour exécuter ce projet, suivez les instructions suivantes :

Assurez-vous d'avoir Python installé sur votre système.

Clonez le référentiel depuis GitHub : https://github.com/nolan-mahieu/miel-abeilles

Exécutez le fichier main.py pour lancer la simulation.

Paramétrage de l'Algorithme
L'efficacité de l'évolution des abeilles dépend de plusieurs paramètres. Le paramétrage final de l'algorithme sera justifié en fonction des performances et des résultats obtenus. Des expériences ont été menées avec différentes configurations, notamment le taux de mutation, le taux de reproduction, le système de reproduction et la métrique de calcul de la forme physique.

Conclusion
Ce projet explore le concept d'évolution des connaissances au sein d'une colonie d'abeilles à l'aide d'un algorithme génétique. Il permet également de visualiser les résultats à travers différents graphiques. En ajustant les paramètres de l'algorithme, il est possible d'optimiser l'efficacité de la colonie, ce qui présente un intérêt pour la compréhension de l'évolution et de l'adaptation.

Merci d'avoir pris le temps de consulter ce projet. Pour toute question ou suggestion, n'hésitez pas à nous contacter.

