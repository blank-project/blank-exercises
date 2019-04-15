# Le traitement des requetes AJAX

## Construisons d'abord notre mini serveur

Pour effectuer une requete AJAX, on a besoin d'un serveur. En effet, les navigateurs nous interdisent de faire des requetes entre fichiers statiques et serveurs.

* Vérifiez que vous avez bien l'extension Live Server par Ritwick Dey.
* Lancez votre serveur dans visual studio à l'aide de la combinaise de touche `Alt + L, Alt + O`.
* Vérifiez que votre serveur est accessible à l'adresse suivante : [http://localhost:5500](http://localhost:5500)

## Utilisons les données de la mairie de Paris !

* Naviguez vers ce lien pour obtenir des données concernant les arbres remarquables à Paris: [https://opendata.paris.fr/explore/dataset/arbresremarquablesparis/api/](https://opendata.paris.fr/explore/dataset/arbresremarquablesparis/api/)


## Passons à l'exercice

* Créez un fichier `script.js` et incluez le dans votre page HTML
* Utilisez une requête AJAX pour récupérer les données des arbres remarquables à Paris.
* Récupérez la réponse de votre requete avec `this.responseText`. Pour le "parser" et le transformer en objet JavaScript vous pouvez utiliser la méthode `parse` de l'objet `JSON` : `JSON.parse(this.responseText)`. Voir la doc ici : [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse)
* Interprétez les données en javascript pour générer un HTML cohérant, que vous insérerez dans le DOM (sous forme d'un tableau ?)

## BONUS :
* Faire une pagination (10 par 10).
* Faire un fitre de requête, ou l'on peut chercher les arbres par leur nom.
* Générez une carte avec Leaflet en indiquant la position des arbres remarquables.
