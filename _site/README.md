justbridou.github.io
====================

<h2> Fichier de procédure </h2>

<p> Lancer la machine virtuel «VirtualBox» </p>
<p> Dans le menu démarrer, lancer l'émulateur de Terminal </p>

<h3> Commande de procédure pour: </h3>

<!-- Lancer Apache -->
    sudo service apache2 start

<!-- Relancer Apache -->
  	sudo service apache2 restart

<!-- Installer Ruby -->
  	sudo apt-get install ruby (version de ruby normal)

<!-- Installer Git -->
  	sudo apt-get install git

<!-- Installer Jekyll 2.4 -->
  	sudo apt-get install ruby ruby-dev make (version de ruby développeur)
  	sudo gem install jekyll --no-rdoc –no-ri
  	sudo apt-get install nodejs
  	jekyll - v (vérifier la version de jekyll)

<!-- Créer un répertoire site -->
	mkdir site 


<h3> GITHUB </h3>


Sur le site Github, après avoir créé un compte :
<ul>
	<li> Barre de menu > icône « + » > new repository </li>
	<li> Dans repository name = username.github.io </li>
	<li> Laisser en public </li>
	<li> Selectionner « initialize this repository with a README » </li>
	<li> Create </li>
</ul>


Retourner dans le Terminal :
<ul>
	<li> cd site (pour rentrer dans le répertoire site, créé avant) </li>
	<li> git clone https://github.com/username/username.github.io </li>
	
	<li> cd username.github.io </li>
	<li> echo "Hello World" > index.html </li>
	
	<li> git add --all </li>
	<li> git commit -m "Initial commit" </li>
		<ul>
		  <li> git config --global user.email «morgane_betend@netcourrier.com» </li>
		  <li> git config –global user.name «justbridou» </li>
		</ul>
	<li> git add --all </li>
	<li> git commit -m "Initial commit" </li>
	<li> git push </li>
</ul>


Pour vérifier que la procédure est correcte :

	regarder dans le «Gestionnaire de fichiers» > «Xubuntu» > «Site» > «justbridou.github.io» > voir si il y a les 2 fichiers «Index.html» et «README.md»
	recharger la page du compte gitbuh > vérifier si on a les 2 fichiers
