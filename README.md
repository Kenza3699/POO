Introduction :
En réalisant ce mini projet, on a essayé d’employé tous les concepts de PROGRAMMATION ORIENTEE OBJET  qu’on apprit. Le code source est muni des commentaires qui précisent le concept utilisé dans chaque partie.
En redéfinissons les méthodes on a utilisé les règles données dans la notion de ce projet .
Hiérarchie :
1-Package :
On a crée un package nommé (mini_projet).  
2-Interface :
On a choisi d’introduire la prime d’un seul enfant dans une interface (PrimeUnEnfant) car elle est fixe et commun entre tous les employés.
3-Les classes abstraites :
On a crée une classe abstraite (Prime) qui contient deux méthodes abstraites ‘primeAdministratif’et ‘primeEnfant’ (seront redéfinies dans toutes les classes filles car tous les employés ont le droit d’avoir ces primes, mais chaque entreprise a sa façon de les calculer.)  Et deux autres méthodes fixes.
4-L’héritage : 
On a crée une classe (Employe) qui hérite de la classe (Prime) et implémente l’interface (PrimeUnEnfant). Cette dernière est munie des attributs nécessaires (nom, prénom, Date de naissance, fonction, salaire de base), des méthodes (SalaireBrut , toString) et d’un constructeur paramétré. 
- Dans cette classe on a reformulé les méthodes abstraites de la classe parente en introduisent les règles de cette entreprise national. 
Schéma explicative

5-L’encapsulation :
On a introduit ce concept dans toutes les classes et les méthodes créent en utilisant les niveaux de visibilité.
-Dans la classe Employe :
Les attributs ont la visibilité (private) privé et on a met des getters et setters (public) pour récupérer ces derniers.
-Dans la classe Prime :
On a met (protected), ça veut dire visible seulement dans le package mini-projet.
6-Création des objets et appelle au constructeur :
Afin d’atteindre  le but de ce programme (calcule de salaire de brut), on a crée une classe main (mini-projet).
La première étape a effectué dans ce dernier est la récupération des informations de l’employé et la création d’un objet de classe Employe. 
En utilisant cette objet on fait un appelle aux méthodes de classe parente pour obtenir toutes les sommes des primes.
Ses primes seront utilisées comme des paramètres d’entrée en faisons un appelle aux méthodes de la classe Employe.
(SalaireBrut) pour le calcule et (toString) pour l’affichage des résultats.





