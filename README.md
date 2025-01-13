# Using AJAX in JavaScript

[Cette page en français.](LISEZMOI.md)

Examples of solutions for retrieving JSON with AJAX in JavaScript

The [Delphi Books](https://delphi-books.com) API was used to output a list of books to be displayed on the screen. The data is accessed via GET and returned as JSON.

These examples were developed on Twitch on February 1, 2022. [The replay of this session](https://serialstreameur.fr/comment-utiliser-ajax-depuis-javascript-pour-afficher-des-donnees-provenant-d-une-api-externe.html) can be viewed at [Serial Streameur](https://serialstreameur.fr/). Video excerpts are also available for each example.

Other examples have since been added, off-stream, to simplify copy/paste or the creation of simple projects without having to read the “official” documentation, which is rarely clear!

I've written some explanations on [using Ajax in JavaScript](https://trucs-de-developpeur-web.fr/ajax.html) on [this blog](https://trucs-de-developpeur-web.fr).

## Samples list

### jQuery (GET)

Retrieve the list of books using jQuery's $.ajax() command. Display is done by creating HTML from jQuery.

[See the video and explanations](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-jquery.html)

### jQuery-with-HTML-Templates (GET)

Retrieve the list of books using jQuery's $.ajax() command. Display by cloning an HTML template in jQuery.

[See the video and explanations](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-jquery-et-un-template-html.html)

### Web-Fetch-API (GET)

Use of the latest JavaScript Fetch API to retrieve data. Display by creating HTML code through DOM manipulation.

[See the video and explanations](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-fetchapi.html)

### Web-Fetch-API-Get (GET)

Uses Fetch API to make a GET request with two parameters to [a PHP dump program](https://github.com/DeveloppeurPascal/PHP-API-Dump) on the server side.

### Web-Fetch-API-Post (POST)

Uses Fetch API to make a POST request with two parameters to [a PHP dump program](https://github.com/DeveloppeurPascal/PHP-API-Dump) on the server side.


### Web-Fetch-API-VueJS (GET)

Use of the latest JavaScript Fetch API to retrieve data. Display data using VueJS.

[See the video and explanations](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-fetch-api-et-vuejs-pour-l-affichage.html)

### XMLHttpRequest (GET)

Use of XMLHttpRequest to retrieve data. Display is also done by DOM manipulation.

[See the video and explanations](https://trucs-de-developpeur-web.fr/faire-de-l-ajax-en-javascript-avec-xmlhttprequest.html)

### XMLHttpRequest-GET (GET)

A GET request to show how to simulate sending values as a classic HTML form would have done with a GET method.

Use the [PHP API Dump](https://github.com/DeveloppeurPascal/PHP-API-Dump) program as the request destination.

GET = QUERY_String => parameters are sent in the URL.

### XMLHttpRequest-POST (POST)

A POST request to demonstrate how to simulate the sending of values in the same way as a classic HTML form with a POST method.

Uses the [PHP API Dump](https://github.com/DeveloppeurPascal/PHP-API-Dump) program as the request destination.

POST => parameters are sent in the request body, but their encapsulation depends on the Content-Type added in the request header.

## Talks and conferences

### Twitch

Follow my development streams of software, video games, mobile applications and websites on [my Twitch channel](https://www.twitch.tv/patrickpremartin) or as replays on [Serial Streameur](https://serialstreameur.fr) mostly in French.

## Source code installation

To download this code repository, we recommend using "git", but you can also download a ZIP file directly from [its GitHub repository](https://github.com/DeveloppeurPascal/Tests-AJAX-JavaScript).

## Compatibility

When I code, I work locally with XAMPP on Windows. My projects work for this stack.

There's no guarantee of compatibility with other software or versions, even though I try to keep my code clean and avoid using too many specific things.

If you detect any anomalies on earlier versions, please don't hesitate to [report them](https://github.com/DeveloppeurPascal/Tests-AJAX-JavaScript/issues) so that I can test and try to correct or provide a workaround.

## License to use this code repository and its contents

This source code is distributed under the [AGPL 3.0 or later license](https://choosealicense.com/licenses/agpl-3.0/).

You are generally free to use the contents of this code repository anywhere, provided that:
* you mention it in your projects
* distribute the modifications made to the files supplied in this project under the AGPL license (leaving the original copyright notices (author, link to this repository, license) which must be supplemented by your own)
* to distribute the source code of your creations under the AGPL license.

If this license doesn't suit your needs, you can purchase the right to use this project under the [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/) or a dedicated commercial license ([contact the author](https://trucs-de-developpeur-web.fr/nous-contacter.php) to explain your needs).

These source codes are provided as is, without warranty of any kind.

Certain elements included in this repository may be subject to third-party usage rights (images, sounds, etc.). They are not reusable in your projects unless otherwise stated.

## How to ask a new feature, report a bug or a security issue ?

If you want an answer from the project owner the best way to ask for a new feature or report a bug is to go to [the GitHub repository](https://github.com/DeveloppeurPascal/Tests-AJAX-JavaScript) and [open a new issue](https://github.com/DeveloppeurPascal/Tests-AJAX-JavaScript/issues).

If you found a security issue please don't report it publicly before a patch is available. Explain the case by [sending a private message to the author](https://trucs-de-developpeur-web.fr/nous-contacter.php).

You also can fork the repository and contribute by submitting pull requests if you want to help. Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## Support the project and its author

If you think this project is useful and want to support it, please make a donation to [its author](https://github.com/DeveloppeurPascal). It will help to maintain the code and binaries.

You can use one of those services :

* [GitHub Sponsors](https://github.com/sponsors/DeveloppeurPascal)
* Ko-fi [in French](https://ko-fi.com/patrick_premartin_fr) or [in English](https://ko-fi.com/patrick_premartin_en)
* [Patreon](https://www.patreon.com/patrickpremartin)
* [Liberapay](https://liberapay.com/PatrickPremartin)
* [Paypal](https://www.paypal.com/paypalme/patrickpremartin)

or if you speack french you can [subscribe to Zone Abo](https://zone-abo.fr/nos-abonnements.php) on a monthly or yearly basis and get a lot of resources as videos and articles.
