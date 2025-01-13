# Utilisation d'AJAX en JavaScript

[This page in English.](README.md)

Exemples de solutions pour récupérer du JSON avec AJAX en JavaScript

L'API de [Delphi Books](https://delphi-books.com) a été utilisée pour sortir une liste de livres à afficher à l'écran. Les données sont accessibles par GET et retournées en JSON.

Le développement de ces exemples a été effectué sur Twitch le 1 février 2022. [La rediffusion de cette session](https://serialstreameur.fr/comment-utiliser-ajax-depuis-javascript-pour-afficher-des-donnees-provenant-d-une-api-externe.html) est visible sur le site [Serial Streameur](https://serialstreameur.fr/). Des extraits sont également disponibles pour chaque exemple.

D'autres exemples ont été ajoutés depuis, hors stream, pour simplifier les copier/coller ou la création de projets simples sans devoir se taper la documentation "officielle" trop rarement limpide !

J'ai rédigé quelques explications sur l'[utilisation d'Ajax en JavaScript](https://trucs-de-developpeur-web.fr/ajax.html) sur [ce blog](https://trucs-de-developpeur-web.fr).

## Liste des exemples

### jQuery (GET)

Récupération de la liste des livres en utilisant la commande $.ajax() de jQuery. L'affichage se fait par création de HTML depuis jQuery.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-jquery.html)

### jQuery-with-HTML-Templates (GET)

Récupération de la liste des livres en utilisant la commande $.ajax() de jQuery. Affichage par clonage d'un template HTML en jQuery.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-jquery-et-un-template-html.html)

### Web-Fetch-API (GET)

Utilisation de l'API Fetch JavaScript récente pour récupérer les données. Affichage par création de code HTML par manipulation du DOM.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-fetchapi.html)

### Web-Fetch-API-Get (GET)

Utilise Fetch API pour faire une requête GET avec deux paramètres à [un programme de dump en PHP](https://github.com/DeveloppeurPascal/PHP-API-Dump) côté serveur.

### Web-Fetch-API-Post (POST)

Utilise Fetch API pour faire une requête POST avec deux paramètres à [un programme de dump en PHP](https://github.com/DeveloppeurPascal/PHP-API-Dump) côté serveur.

### Web-Fetch-API-VueJS (GET)

Utilisation de l'API Fetch JavaScript récente pour récupérer les données. Affichage des données en utilisant VueJS.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-fetch-api-et-vuejs-pour-l-affichage.html)

### XMLHttpRequest (GET)

Utilisation de XMLHttpRequest pour récupérer les données. L'affichage étant fait aussi par manipulation du DOM.

[Voir la vidéo et les explications](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-xmlhttprequest.html)

### XMLHttpRequest-GET (GET)

Une requête en GET pour montrer comment simuler un envoi de valeurs comme l'aurait fait un formulaire HTML classique avec une méthode GET.

Utilise le programme [PHP API Dump](https://github.com/DeveloppeurPascal/PHP-API-Dump) comme destination des requêtes.

GET = QUERY_String => les paramètres sont envoyés dans l'URL.

### XMLHttpRequest-POST (POST)

Une requête en POST pour montrer comment simuler un envoi de valeurs comme l'aurait fait un formulaire HTML classique avec une méthode POST.

Utilise le programme [PHP API Dump](https://github.com/DeveloppeurPascal/PHP-API-Dump) comme destination des requêtes.

POST => les paramètes sont envoyés dans le corps de la demande, mais leur encapsulation dépend du Content-Type ajouté dans le header de la requête.

## Présentations et conférences

### Twitch

Suivez mes streams de développement de logiciels, jeux vidéo, applications mobiles et sites web sur [ma chaîne Twitch](https://www.twitch.tv/patrickpremartin) ou en rediffusion sur [Serial Streameur](https://serialstreameur.fr) la plupart du temps en français.

## Installation des codes sources

Pour télécharger ce dépôt de code il est recommandé de passer par "git" mais vous pouvez aussi télécharger un ZIP directement depuis [son dépôt GitHub](https://github.com/DeveloppeurPascal/Tests-AJAX-JavaScript).

## Compatibilité

When I code, I work locally with XAMPP on Windows. My projects work for this stack.

There's no guarantee of compatibility with other versions, even though I try to keep my code clean and avoid using too many specific things.

Quand je développe, je travaille localement avec XAMPP sur Windows. Mes projets fonctionnent avec cette stack.

Aucune garantie de compatibilité avec d'autres logiciels ou versions n'est fournie même si je m'efforce de faire du code propre et ne pas trop utiliser de trucs spécifiques.

Si vous détectez des anomalies sur des versions antérieures n'hésitez pas à [les rapporter](https://github.com/DeveloppeurPascal/Tests-AJAX-JavaScript/issues) pour que je teste et tente de corriger ou fournir un contournement.

## Licence d'utilisation de ce dépôt de code et de son contenu

Ces codes sources sont distribués sous licence [AGPL 3.0 ou ultérieure](https://choosealicense.com/licenses/agpl-3.0/).

Vous êtes globalement libre d'utiliser le contenu de ce dépôt de code n'importe où à condition :
* d'en faire mention dans vos projets
* de diffuser les modifications apportées aux fichiers fournis dans ce projet sous licence AGPL (en y laissant les mentions de copyright d'origine (auteur, lien vers ce dépôt, licence) obligatoirement complétées par les vôtres)
* de diffuser les codes sources de vos créations sous licence AGPL

Si cette licence ne convient pas à vos besoins vous pouvez acheter un droit d'utilisation de ce projet sous la licence [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/) ou une licence commerciale dédiée ([contactez l'auteur](https://trucs-de-developpeur-web.fr/nous-contacter.php) pour discuter de vos besoins).

Ces codes sources sont fournis en l'état sans garantie d'aucune sorte.

Certains éléments inclus dans ce dépôt peuvent dépendre de droits d'utilisation de tiers (images, sons, ...). Ils ne sont pas réutilisables dans vos projets sauf mention contraire.

## Comment demander une nouvelle fonctionnalité, signaler un bogue ou une faille de sécurité ?

Si vous voulez une réponse du propriétaire de ce dépôt la meilleure façon de procéder pour demander une nouvelle fonctionnalité ou signaler une anomalie est d'aller sur [le dépôt de code sur GitHub](https://github.com/DeveloppeurPascal/Tests-AJAX-JavaScript) et [d'ouvrir un ticket](https://github.com/DeveloppeurPascal/Tests-AJAX-JavaScript/issues).

Si vous avez trouvé une faille de sécurité n'en parlez pas en public avant qu'un correctif n'ait été déployé ou soit disponible. [Contactez l'auteur du dépôt en privé](https://trucs-de-developpeur-web.fr/nous-contacter.php) pour expliquer votre trouvaille.

Vous pouvez aussi cloner ce dépôt de code et participer à ses évolutions en soumettant vos modifications si vous le désirez. Lisez les explications dans le fichier [CONTRIBUTING.md](CONTRIBUTING.md).

## Supportez ce projet et son auteur

Si vous trouvez ce dépôt de code utile et voulez le montrer, merci de faire une donation [à son auteur](https://github.com/DeveloppeurPascal). Ca aidera à maintenir le projet (codes sources et binaires).

Vous pouvez utiliser l'un de ces services :

* [GitHub Sponsors](https://github.com/sponsors/DeveloppeurPascal)
* Ko-fi [en français](https://ko-fi.com/patrick_premartin_fr) ou [en anglais](https://ko-fi.com/patrick_premartin_en)
* [Patreon](https://www.patreon.com/patrickpremartin)
* [Liberapay](https://liberapay.com/PatrickPremartin)
* [Paypal](https://www.paypal.com/paypalme/patrickpremartin)

ou si vous parlez français vous pouvez [vous abonner à Zone Abo](https://zone-abo.fr/nos-abonnements.php) sur une base mensuelle ou annuelle et avoir en plus accès à de nombreuses ressources en ligne (vidéos et articles).
