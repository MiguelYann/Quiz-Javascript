## Réponses

###  Ecrire du code Javascript

1. Le JavaScript peut être insérér de trois manières à notre fichier HTML. Considérons un fichier HTML simple, avec une structure basique, c'est aà dire un head et un body.  
On peut écrire notre code JavaScript:

On utilise le tag \<script> :  
* Dans le **head**
  ``` HTML
   <!DOCTYPE>
   <html>
        <head>
            <script>  
        votre code Javascript
            </script>
   </head>
   <body>

   </body>
   </html>

* Dans le **body**

```HTML
<!DOCTYPE>

<html>
    <head>

    </head>

    <body>
    <script>
        Votre code Javascript
    </script>
    </body>

</html>  

```  
* Editer un fichier portant l'extension .js

Vous avez la possibibilité de créer un fichier JavaScript externe et de l'insérer à votre code HTML. Supposons que nous avons créer un fichier nommé _"test.js"_ et nous devons l'insérer à notre page HTML. il suffit d'ajouter un attribut "src" au tag \<script>, qui va spécifier le chemin relatif de notre code Javascript

``` HTML

<script src = test.js></script>

```
C'est d'ailleurs cette méthode que vous allez utliser le plus pour des raisons de compréhension et de clarté du code. Et je vous conseille d'insérer le fichier JavaScript juste après la balise fermante body.    






2.  Une fois votre code JavaScript écrit il doit être interpreté et éxécuter par un programme appeleé Moteur JavaScript. De nos jours les navigateurs Web embarquent tous des moteurs JavaScript. Ainsi chaque Navigateur est doteéé de la console qui nous permerra d'éxécuter nos futurs programmes JavaScript.

* **Google Chrome**: Google V8
* **Mozilla FireFox**: SpiderMonkey
* **Safari**: JavaScript Core
* **Internet Explorer**: Chakra.  

> **Astuces**:  Pour ouvrir la console dans les navigateurs. Une fois que vous êtes sur n'importe quelle page Web, _faites un clique droit et cliquer sur **Inspecter l'élement**_ et rendez vous dans la console.



### Syntaxe

Dans cette section nous parlerons de l'indentation des commentaires et des varibales.

### Indentation

Indenter son code signifie de décaler certaines instructions par rapport à d'autres. Son but principal est de rendre son code plus lisible et plus compréhensible. Son utilisation est très simple il suffit de penser à une sorte arborescence.  
##### **Exemple code indenter**:  

``` html
<html>
    <head>

        <meta>
    </head>

</html>
```

##### **Exemple code non indenter**: 

``` HTML
<html>
<head>
<meta>
</head>
</html>
```

### Commentaires

Les commentaires jouent plusieurs rôles au sein d'un programme:

* Les commentaires permettent au développeur qui l'a écrit de se souvenir de ce que faisait telles ou telles lignes de code
* Les commentaires permettent au développeur d'isoler temporairement une ou plusieurs lign de code. En effet les commentaires ne sont pas interprétés par nle moteur JS, elles sont invisibles pour le navigateur.
* Les commentaires expliquent mieux le code à toute personne qui se trouve pour la première devant le dit programme.
Ainsi en JavaScript nous avons deux types de commentaires:  

Les _**commentaires multilignes**_ et les _**commentaires monolignes**_.

``` Javascript

//Ceci est un commentaire monoligne  

/*Ceci est un commentaire multilignes
qui peut aller sur plusieurs lignes*/

```

### Variables

5. Une variable est un emplacement meémoire qui persmet de stockeé des informations de manière temporaire. Comme son nom l'indique la valeur varie.

6. En Javascript, il existe un seul mot clé pour déclarer une variable(Nous verrons plus tard que cela n'est pas exactement correct). On utilise le mot clé **var**
``` Javascript
var nom;
```
7. Alors comme règle de nomenclature cela est assez simple:
* Une variable commence par une lettre minuscule ou un blanc souligné
* Une variable doit avoir un nom (son identificateur), un type(qui est deéterminé en JavaScript uniquement par la valeur qu'il contient), et une valeur.
* Le  nom d'une variable doit idéalement être simple et précis, ne courrez pas le risque de donnner des noms farfelus. De plus il doit respecter la notation CamelCase. C'est aà dire chaque nouveau mot dans l llongue chiane de caractere de son nom doit commencer par une lettre majuscule.

``` Javascript

var uneVariable = 3 // uneVariable représente son nom et 3 la valeur qu'il contient.

var 7variables// le nom e cette variable est incorrect. 


