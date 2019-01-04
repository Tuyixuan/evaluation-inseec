# Évaluation individuelle

## Programmation - Coaching

```
Nom : TU
Prénom : YI XUAN
URL de votre compte Github : https://github.com/Tuyixuan
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

Nous, comme les clients, on entre dans un serveur. Le programmeur va écrire les codes dans le serveur.

Qand on est entré dans une interface, le serveur va marcher les codes pour ce qu'on peut voir.



 ### 2. HTML est un langage côté... 

client

### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
	<head>
        <title></title>
    </head>
    	<body>
    	</body>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
p {
    color: green;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap c'est un site qui permet de proposer les codes pour HTNL et CSS.
On doit tout d'abord faire le lien avec le site et apres on peut ajouter les codes tout de suit dans le html et css.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">
	<head>
        <title></title>
    </head>
    	<body>
    	</body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="container">
    <div class="row">
	
        <div>
    Google
		</div>

	<div>
    Microsoft
		</div>

	<div>
    Apple
		</div>
        
    </div>
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div>
 
	<img src="https://inside-assets1.inside.com.tw/2015/09/Googlelogo2015sd.jpg?auto=compress&fit=max&w=730" alt="Google" />

</div>

<div>
  
	<img src="https://zdnet3.cbsistatic.com/hub/i/r/2014/08/27/0d77a99a-2da9-11e4-9e6a-00505685119a/resize/570x428/9c14ac223374e81816a3973dcbd3f661/microsofts-logo-gets-a-makeover.jpg" alt="Microsoft" />

</div>

<div>

	<img src="http://logok.org/wp-content/uploads/2014/04/Apple-logo-grey-880x625.png" alt="Apple" />

</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div>
  <a href="http://google.com">
	<img src="https://inside-assets1.inside.com.tw/2015/09/Googlelogo2015sd.jpg?auto=compress&fit=max&w=730" alt="Google" />
</a>
</div>

<div>
   <a href="https://www.microsoft.com/fr-fr/">
	<img src="https://zdnet3.cbsistatic.com/hub/i/r/2014/08/27/0d77a99a-2da9-11e4-9e6a-00505685119a/resize/570x428/9c14ac223374e81816a3973dcbd3f661/microsofts-logo-gets-a-makeover.jpg" alt="Microsoft" />
</a>
</div>

<div>
    <a href="https://www.apple.com/">
	<img src="http://logok.org/wp-content/uploads/2014/04/Apple-logo-grey-880x625.png" alt="Apple" />
</a>

</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```

1. array=[1,2,3,4,5]        #ceci est une chaine de caractère 
2. boolean = true   #ceci est un valeur pour dire que c'est true ou false
3. integer = 1      #ceci est un numero 
4. float = 1.4      #ceci est un nemero avec Décimal
5. string = myName. ＃ceci est un variable

# Ceci est un 
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
prenom = "YI XUAN"
nom = "TU"
Github = "https://github.com/Tuyixuan"
puts prenom
puts nom
puts Github
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a = 674
b = 311 
c = a % b
puts c
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Gem c'est un programe qui permet de l'utiliser dans le Ruby.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
APi c'est une interface aka un bot qui permet d'acceder le site.
Avec api on peut Twitter, follower, ou retweet dans un bot.
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
prenom = "Anthony"
hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom
if hour < 12
puts "Bonjour #{prenom}"
# sinon
else 
puts "bonsoir #{prenom}"
    
	# j'écris mon code permettant de dire Bonsoir prénom
end

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


client.follow("@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra")


```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

