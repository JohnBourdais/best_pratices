#Grille Responsive


## Librairies :

	http://dbmwebdesign.fr/Tutos/rwd/outils-script.html#

	- html5shiv.js

	  	Permet de gérer la comptibilité avec HTML5 sur les anciens navigateurs.

	- modernizr.js

	  	Framework javascript de détection de compatibilité, contient déjà le script html5shiv.

		Inclusion :

		<!--[if lt IE 7]>      <html class="no-js lt-ie9 lt-ie8 lt-ie7"> <![endif]-->
		<!--[if IE 7]>         <html class="no-js lt-ie9 lt-ie8"> <![endif]-->
		<!--[if IE 8]>         <html class="no-js lt-ie9"> <![endif]-->
		<!--[if gt IE 8]><!--> <html class="no-js"> <!--<![endif]-->

		<head>
			...
			<script src="js/vendor/modernizr.min.js" type="text/javascript"></script>
		</head>

	- respond.js

		Gestion de la compatibilité des @media-query pour IE7 et IE8 sur les max-width et min-width uniquement.

		Inclusion :

		<!--[if lt IE 9]>
			<script scr="js/respond.js"></script>
		<![endif]--> 


	- jquery.js
	  Framework javascript.


## SMACCS :

## ACCESIBILITE :

	- Skip navigation

	Lien dévitement permettant d'accèder directement au contenu de la page.
	


