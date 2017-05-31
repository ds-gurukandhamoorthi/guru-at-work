1e semaine. (17-21 mai) : 35 heures

* Rapport de la mission OUIBUS
* Mise en place d'outils (STS, postgres ..) dans le premier et deuxieme ordinateur.
* Familiarisation avec le projet EAVEST.
* Faire fonctionnel l'etape de verification mail par utilisateur.
* Charger fichier csv CAC 40
* Utilisation des Streams pour rendre efficace la lecture du CSV.
* Choisir methode de webscraping (Jsoup vs Jaunt)


2e semaine. (02-05 mai) : 28 heures
* Webscraping avec Jsoup (utilisation de CSS selectors) pour obtenir prix.
* Essai Webscraping avec HtmlUnit pour obtenir prix de STOXX.
* Ajout champ URL pour Produit.
* Junit Tests et Gestions d'exceptions
* Benchmarking differentes valeurs.
* Recherche de raison de difference de performance entre Boursorama et Bloomberg.
* Mettre une taille limite pour les fichiers qu'on peut uploader.
* Creer une tache planifiée pour l'obtention des valeurs journalieres.
* Choisir une méthode de infinite scrolling

3e semaine (08-11 may) : 24 heures 
(friday, Guru worked only until 14:30, RTT)

* Infinite scrolling : jquery jscroll
* Externalize Exceptions string in a special file
* Thymeleaf filter made to work as intended (eavest products only vs All)
* Json produce from get controller between two dates
(a view model class just for producing the fore-mentioned json)

4th week (15-19 may) : 35 hours (-2 hours of job interview Webmanity )
* Tests for the service added last week
* Move methods to the right place, move some files to the right place
* Draw jqplot graph by consuming the generated json
* Add webscraping for OPCVM from morningstar website
* Zoom to the right level for jqplot graph (dates only)
* Investigate into the mysterious vanishing of some products and their neighbours positioning themselves chaotically
(Firefox specific correction)
(Css fixing height solution brought by Teddy Couriol)

5th dwarf week (22-23 may) : 24 hours (-2 -4 hours of job interview Aubay, Agap2IT)
* Draw the graph for barrieres.
* Fruitlessy tried to calculate the window-zoom for the graph ... which was later solved by Teddy Couriol by drawing the barrieres as graph instead of overlay
* Barriere Airbag

6th dwarf week (29-31 may) : 24 hours
* Add Currency for products and show them with thymeleaf when present
* Correct the hard coding of URL so as to not have error when deployed to the VPS
* When Data Not Available on any of the sites throw EavException
