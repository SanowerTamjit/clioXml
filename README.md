# clioXml
Querying of XML Database 

Alain Dallo, Stéphane Lamassé, Laurent Frobert

### Présentation
ClioXML est un logiciel développé avec le soutien du projet de recherche Studium parisiense. Son objectif est de permettre aux chercheurs comme aux étudiants d'explorer, d'interroger, d'exploiter les données structurées dans un fichier ou ensemble de fichiers xml. 
Il s'agit donc essentiellement de manipuler des données dans un objectif de recherche afin de produire graphiques, tableaux. 
	Celui-ci a donc quatre objectifs principaux :
* création, modification d'un schéma à la volée
* coder des éléments ou des attributs
* explorer les données par une interface permettant à l'utilisateur de se représenter et de comprendre les jeux de données en explorant leurs natures, leurs relations et leurs distributions ainsi qu'en mettant en lumière les densités d'informations
* interroger les données en effectuant des requêtes de manière intuitive via une interface graphique ou par la rédaction assistée d'une requête 
* les exploiter par des requêtes de requêtes, des requêtes sur tables et requêtes associées ou via une exportation de résultats ou de jeux de données pour une utilisation dans d'autres logiciels d'exploitation de données.
* 
Nous espérons qu'il intéressera les étudiants et les chercheurs en sciences-humaines n'ayant pas une grande habitude de l'utilisation de l'ordinateur et une très faible connaissance des principes des bases de données xml, des schémas et de leurs interrogations.

### Le logiciel est développé en JAVA 
#### Version serveur
Elle doit permettre à  une communauté constituée autour d'un projet d'interroger une structure commune pour construire son propre rapport aux données. Elle peut-être utilisée comme une interface pédagogique, ou comme un service.  Ainsi nous l'utilisons, à Paris 1, pour permettre à nos étudiants d'interroger leurs données sans aucune installation de leur côté. 
#### Version locale
Celle-ci est plutôt destinée aux chercheurs
* Le public ciblé n'aura pas forcément connaissance de la structure des données qu'il souhaite interroger au moment où il commence son exploration.
* Ce public ayant des modes de travail variés, le logiciel peut être utilisé en situation de mobilité avec ou sans accès à internet sur une base de données à distance sur serveur web ou sur une copie en local d'une base ou d'une partie de celle-ci.


### Installation


#### Linux et MacOs
* Après avoir téléchargé le paquet 
* Il faut compiler avec ANT (version jdk 1.8)  qui utilise Build.xml 
* Sous Linux, ou MacOs dans une session 
```sh
$ ant
```
* un répertoire build est crée 
* dans ce répertoire vous pouvez lancer : **launch.sh**
```sh
$ ./launch.sh
```
* Vous pouvez accéder à ce logiciel en utilisant votre navigateur à l'adresse : **localhost:8090**. Evidemment le port peut-être changé 


### Utilisation de la version local 

#### Linux et MacOs 
* Définir un nouveau projet, donnez lui le nom que vous souhaitez, puis entrer dans le projet 
* Il faut alors :
	* importer votre fichier xml, qui doit être compressé (.zip)
	* créer/importer un schéma pour ce projet 
	```
	```
