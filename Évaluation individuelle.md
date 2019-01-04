# Évaluation individuelle

## Programmation - Coaching

```
Nom : Da Silva
Prénom : Lionel
URL de votre compte Github : https://github.com/lioneldasi
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
L'intéraction client-serveur implique une communication entre un client envoyant des requêtes à des serveurs qui donnent des réponses en retour (exemple: envoi d'une page, envoi d'un contenu sécurisé... ).
```



 ### 2. HTML est un langage côté... 	

```
HTML est un langage côté client.
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html lang="fr">
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="style.css">
```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
p
{
    color: #008000;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est un site permettant de recenser un ensemble d'outils de programmation comme des lignes de codes permettant d'être utilisées dans un langage HTML, CSS et Javascript.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html lang="fr">
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="style.css">
    
   	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html

    <div class="container"> 
      <div class="row">
        <div class="col-sm"> 
          <p align="center"> Google </p>
        </div>
        <div class="col-sm"> 
          <p align="center"> Microsoft</p>
        </div> 
        <div class="col-sm"> 
          <p align="center"> Apple </p>
        </div> 
        </div> 
      </div>
        
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="container"> 
      <div class="row">
        <div class="col-sm"> 
          <img src="logogoogle.jpg" alt="Google">
        </div>
        <div class="col-sm"> 
          <img src="logomicrosoft.jpg" alt="Microsoft">
        </div> 
        <div class="col-sm"> 
          <img src="logoapple.jpg" alt="Apple">
        </div> 
        </div> 
      </div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div class="container"> 
      <div class="row">
        <div class="col-sm"> 
          <a href="http://google.fr"><img src="logogoogle.jpg" alt= "Google"></a>
        </div>
        <div class="col-sm"> 
          <a href="http://microsoft.com"><img src="logomicrosoft.jpg" alt= "Microsoft"></a>
        </div> 
        <div class="col-sm"> 
          <a href="http://apple.com"><img src="logoapple.jpg" alt= "Apple"></a>
        </div> 
        </div> 
      </div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Ruby est un langage côté serveur.
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
 « Lionel » = Chaine de caractère
 123 = Integer 
 15.6 = Float
 True = Boolean
 [« Chaine de caractère », true, false, 12] = Array
 [“#{Lionel} #{Da Silva}”] = Hash

```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
my_string= "lionel"
puts my_string
my_string= "da silva"
puts my_string
my_string= "https://github.com/lioneldasi"
puts my_string
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a = 674
b = 311
c = 674 % 311
puts c
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Un gem est un module qui s'ajoute à une ligne de commande d'un langage Ruby.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Une API (Application Programming Interface) est un code permettant l'intéraction entre un client et un serveur via une application.
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
print "Quel est ton nom?"

hour = 15
# Si hour est inférieur à 12
if integer < 12
    puts "Bonjour"
else
    puts "Bonsoir"
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

