# HTML5

	

# DISPLAY : BLOCK
	
	Il occupe l'entierté de la largeur de son conteneur
	Il permet l'attribution de marges verticales
	Il permet la modification de sa hauteur et largeur

	<article>, <aside>, <nav>, <section>
	<h1> à <h6>, <hgroup>, <p>, <ul>, <ol>, <dl>, <table>, <blockquote>

# DISPLAY : INLINE

	<audio>, <video>, <iframe>, <canvas>, <img>
	<input>, <textarea>, <button>, <select>
	<strong>, <b>, <i>, <del>
	<a>, <img>, <strong>, <abbr>

# DISPLAY : INLINE-BLOCK

	<audio>, <canvas>, <embed>, <iframe>, <object>, <video>, <svg>, <math>
	
# BALISES SEMANTIQUES
	
	<header> : Qui indique que l’élément est une en-tête
	<footer> : Qui indique que l’élément est un pied-de-page
	<nav> : Qui indique un élément de navigation tel qu’un menu
	<aside> : Qui correspond à une zone secondaire non liée au contenu principal de la page
	<article> : Qui représente une portion de la page qui garde un sens même séparée de l’ensemble 
				de la page (comme un article de blog par exemple)
	
# LE LOCAL STORAGE

	Le Local Storage est une manière élégante de stocker dans le navigateur des informations facilement.
	La variable sera toujours disponible si l’utilisateur ferme puis ré-ouvre son navigateur. 
	L’utilisation du Local Storage est proche de celle des cookies, mais contrairement aux cookies, 
	ces informations ne sont jamais communiquées au serveur. Elles sont ainsi particulièrement adaptées 
	aux applications offline.
	
	localStorage.setItem("name", "John");    
	alert(localStorage.getItem("name"));

			


