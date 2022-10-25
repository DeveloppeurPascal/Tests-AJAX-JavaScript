# Tests-AJAX-JavaScript

Exemples de solutions pour récupérer du JSON avec AJAX en JavaScript

L'API de [Delphi Books](https://delphi-books.com) a été utilisée pour sortir une liste de livres à afficher à l'écran. Les données sont
accessibles par GET et retournées en JSON.

Le développement de ces exemples a été effectué sur Twitch le 1 février 2022. [La rediffusion de cette session](https://serialstreameur.fr/comment-utiliser-ajax-depuis-javascript-pour-afficher-des-donnees-provenant-d-une-api-externe.html) est visible sur le site [Serial Streameur](https://serialstreameur.fr/). Des extraits sont également disponibles pour chaque exemple.

D'autres exemples ont été ajoutés depuis, hors stream, pour simplifier les copier/coller ou la création de projets simples sans devoir se taper la documentation "officielle" trop rarement limpide !

## jQuery (GET)

Récupération de la liste des livres en utilisant la commande $.ajax() de jQuery. L'affichage se fait par création de
HTML depuis jQuery.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-jquery.html)

## jQuery-with-HTML-Templates (GET)

Récupération de la liste des livres en utilisant la commande $.ajax() de jQuery. Affichage par clonage d'un template
HTML en jQuery.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-jquery-et-un-template-html.html)

## Web-Fetch-API (GET)

Utilisation de l'API Fetch JavaScript récente pour récupérer les données. Affichage par création de code HTML par
manipulation du DOM.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-fetchapi.html)

## Web-Fetch-API-Get (GET)

Utilise Fetch API pour faire une requête GET avec deux paramètres à [un programme de dump en PHP](https://github.com/DeveloppeurPascal/PHP-API-Dump) côté serveur.

## Web-Fetch-API-Post (POST)

Utilise Fetch API pour faire une requête POST avec deux paramètres à [un programme de dump en PHP](https://github.com/DeveloppeurPascal/PHP-API-Dump) côté serveur.

## Web-Fetch-API-VueJS (GET)

Utilisation de l'API Fetch JavaScript récente pour récupérer les données. Affichage des données en utilisant VueJS.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-fetch-api-et-vuejs-pour-l-affichage.html)

## XMLHttpRequest (GET)

Utilisation de XMLHttpRequest pour récupérer les données. L'affichage étant fait aussi par manipulation du DOM.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-xmlhttprequest.html)

## XMLHttpRequest-GET (GET)

Une requête en GET pour montrer comment simuler un envoi de valeurs comme l'aurait fait un formulaire HTML classique avec une méthode GET.

Utilise le programme [PHP API Dump](https://github.com/DeveloppeurPascal/PHP-API-Dump) comme destination des requêtes.

GET = QUERY_String => les paramètres sont envoyés dans l'URL.

## XMLHttpRequest-POST (POST)

Une requête en POST pour montrer comment simuler un envoi de valeurs comme l'aurait fait un formulaire HTML classique avec une méthode POST.

Utilise le programme [PHP API Dump](https://github.com/DeveloppeurPascal/PHP-API-Dump) comme destination des requêtes.

POST => les paramètes sont envoyés dans le corps de la demande, mais leur encapsulation dépend du content-Type ajouté dans le header de la requête.
