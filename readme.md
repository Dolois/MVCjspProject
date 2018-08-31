### Le 30 Aout 2018 - Démo d'un MVC dans JSP

#### MVC signifie Model View et Controller.
#### C'est un modèle de conception qui sépare la logique métier, 
#### la logique de présentation et les données.

#### Le contrôleur agit comme une interface entre View et Model.
#### Le contrôleur intercepte toutes les demandes entrantes.

#### Le modèle représente l'état de l'application, c'est à dire les données.
#### Il peut également avoir une logique métier.

#### View représente la présentation, 
#### c'est-à-dire l'interface utilisateur (User Interface).

![alt-text](https://github.com/Dolois/MVCjspProject/blob/master/ressources/MVC.JPG)

#### Exemple : MVC dans JSP
#### Dans cet exemple, nous utilisons servlet en tant que contrôleur, 
#### jsp en tant que composant de vue, classe Java Bean en tant que modèle.

#### Créations de 5 pages :

#### index.jsp une page qui reçoit des entrées de l'utilisateur.
#### ControllerServlet.java un servlet qui agit en tant que contrôleur.
#### login-success.jsp (composant d'affichage).
#### login-error.jsp (composant d'affichage).
#### fichier web.xml pour le mappage du servlet.

#### Réussir à ce logger (message de réussite)
