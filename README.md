<!DOCTYPE html>
<html>
<head>
<title>Ma page web comment la créer ?</title>
<style>
h1
{
color: #000000;
background-color: #98FFFF;
}
h2
{
color:#0000FF;
background-color: #007BFF;
}
table, th, td {
  border: 1px solid black; /* Crée une bordure noire */
  border-collapse: collapse; /* Colle les bordures entre elles pour un rendu propre */
  padding: 10px; /* Ajoute un peu d'espace autour du texte */
}
body
{
color: #333;
background-color: #F4F4F4;
}
</style>
<meta charset="UTF-8">
</head>
<body>
<h1>Ma page web, comment la créer ?</h1>
<h2>Sommaire</h2>
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#html">HTML</a></li>
<li><a href="#css">CSS</a></li>
<li><a href="#js">JavaScript</a></li>
<li><a href="#bonus">Bonus</a></li>
</ul>
<h2 id="intro">Introduction</h2>
<p>Dans cette page web, nous allons apprendre à en créer une nous même.<br>Nous aurons besoin de seulement un ordinateur/téléphone/tablette.<br>Sur celui-ci doit être installé un logiciel de bloc note : bloc note pour Windows, TextEdit pour Mac, Notes pour iPhone et Google Keep pour Android.<br>Pour créer une page web  il vous faut ouvrir cette application de notes et en créer une nouvelle (sans nom pour les téléphones) nommés en fonction de votre site et enregistrer sous index.html (⚠️ pas besoin sur téléphone).</p>
<h2 id="html">HTML</h2>
<p>Le HTML est le langage de programmation utilisé pour créer des pages web, notamment la partie texte.</p>
<p>En langage HTML, plus précisément HTML5 (qui signifie HyperText Markup Langage), on utilise des balises : ce sont des instructions pour que le navigateur sache quoi afficher.</p>
<p> les balises commencent par < et se terminent par ></p>
<p>Maintenant, quand je mets du texte de <code>cette façon</code>, c'est qu'il faudra, pour voir l'instruction se réaliser, le mettre entre ça < et ça ></p>
<p>Déjà, pour écrire bonjour en grand, il faut faire<code> h1 </code>, écrire bonjour et ensuite<code> /h1 </code>. h signifie titre et après, il y a un chiffre de 1 à 6 : 1 est la police la plus grande et 6, la plus petite (on descend rarement en dessous de 3).</p>
<p>Maintenant que tu as fait ce petit test, passons à la structuration de la page. On commence avec : <code>!DOCTYPE html</code> ensuite, on va à la ligne, puis <code>html</code>, encore à la ligne et ensuite <code>head</code> (là ou il y a les informations pour le navigateur), à la ligne puis <code>/head</code> (comme tu l'as peut être compris, pour fermer une balise, il faut mettre un slash.) ensuite on met <code>body</code> (c'est la partie où il y a tout le code qui servira pour le texte) et après on le referme et enfin, on referme la balise html ( la deuxième balise que l'on a mit).</p>
<p>Pour continuer, nous allons voir la partie qui est dans le head. D'abord, on écrit <code>meta charset="UTF-8"</code>, ce qui sert à définir l'encodage (ou le type de caractère utilisé dans la page web)(j'ai moi même oublié de le mettre dans des essais de pages webs et je me suis retrouvé avec des caractères trops bizarres) ensuite on écrit <code>title</code>, ce qui sert à définir le titre de la page et pour ce qui doit être recherché dans le navigateur.</p>
<p>Pour le moment, on laisse de côté la partie head, et on vas plutôt s'intéresser à body.</p>
<p>Dans cette partie là, on vas mettre tout  le code qui fait partie de ce qui est visible sur la page.</p>
<p>Voici un répertoire des principales balises html : </p>
<p><code>p</code> pour l'écriture normale, <code>em</code> pour mettre en <em>italique</em>, <code>strong</code> pour mettre en <strong>évidence</strong>, <code>u</code> permet de <u>souligner</u>, <code>b</code>, permet de mettre en <b>gras</b>, <code>code</code> permet d'écrire de la même manière que celle que j'utilise pour les balises.</p>
<h2 id="css" >CSS</h2>
<p>Maintenant, on vas passer à CSS, la partie qui permet de faire le style de la page web. CSS (plus précisément CSS3) permet donc de faire le style. CSS signifie Cascading style sheets. Donc en gros, cela signifie feuille de style.</p>
<p> En CSS, on n'utilise pas de crochet comme cela <, mais plutôt des acollades comme ceci : {<br>Donc en gros, quand je vous mettrai quelques choses dans la balise HTML code, c'est qu'il faudra tout mettre entre accolade.</p>
<p>On peut faire, pour le CSS un fichier différents de celui pour le HTML, mais cela nous complique la vie (surtout si vous travaillez sur mobile) donc on vas le faire dans la partie head.<br>Pour commencer, on vas remonter notre page web jusqu'au head et on vas à la fin de celui ci.<br>Après, nous allons écrire une balise en html (qui vas servir au navigateur de savoir que c'est une partie CSS) que je vais mettre en écriture code et en souligné <code><u>style</u></code> puis après, si vous avez un h1 dans votre page, on écrit h1 tel-quel (Sinon, on écrit h2 et si vous n'en avez pas dans votre page, on ouvre h3...) (et si vous n'avez aucun titre, alors ouvrez une balise comme p) et donc vous ne mettez aucun crochet pour html et vous allez à la ligne. <br>
On vas mettre la partie sélectionné en rouge avec un fond vert : <br><code>color: #FF0000;<br>background-color: #00FF00;</code><br>Et après, on referme la balise style.</p>
<p>Vous avez maintenant votre texte qui s'affiche donc en rouge avec le fond vert (si ça ne s'affiche pas, essayer de sauvegarder le fichier et de rafraîchir la page).</p>
<p>Vous pouvez créer des centaines de couleurs grâce à ce code :</p>
<table>
  <tr>
    <td>Taux de rouge</td>
    <td>Taux de vert</td>
    <td>Taux de bleu</td>
  </tr>
</table>
<p>Pour définir la couleur, on utilise les chiffres de 00 à 99 et les lettres de A à F(#000000=noir #FFFFFF=blanc...)(FF est la valeur la plus élevée=255)</p>
<p>Et pour mettre tout de la même couleur, il faut écrire body dans la partie style.</p>
<h2 id="js">JavaScript</h2>
<p>Grâce à JavaScript, on peut faire des choses comme cela :</p>
<button id="boutonMode">Passer en mode sombre</button>
<p>Le JavaScript est le langage de programmation utilisé pour créer l'interactivité des pages web (comme les boutons, les menus ou les calculs).</p>
<p>En langage JavaScript (souvent abrégé JS), on n'utilise pas de crochets comme en HTML, mais beaucoup de parenthèses <code>()</code> et d'accolades <code>{}</code> pour organiser les instructions.</p>
<p>Comme pour le CSS, on peut faire un fichier séparé, mais il est plus simple de l'écrire dans la partie <code>body</code>, tout à la fin, pour ne pas ralentir l'affichage du texte. On utilise la balise <code><u>script</u></code> pour dire au navigateur que c'est du code JS.</p>

<p>Voici un répertoire des outils principaux en JavaScript :</p>
<p><code>let</code> sert à créer une variable (une boîte pour stocker une info), <code>function</code> sert à créer une action réutilisable, <code>alert</code> permet d'afficher un message surgissant, et <code>document.querySelector</code> permet de sélectionner un élément de la page pour le modifier.</p>

<p>Par exemple, pour créer le bouton ci-dessus, j'ai utilisé une instruction qui surveille le "clic" et qui change la couleur du <code>body</code> :</p>
<h2 id="bonus">Bonus : Java vs JavaScript</h2>
<p>Le Bonus de cette page est une partie très importante pour ne pas faire d'erreur quand tu feras des recherches. Il faut savoir que le <strong>Java</strong> et le <strong>JavaScript</strong> sont deux langages totalement différents.</p>

<p>Le Java est un langage de programmation "orienté objet". Contrairement au JavaScript qui s'écrit simplement dans une balise <code>script</code>, le Java a besoin d'une structure beaucoup plus rigide pour fonctionner.</p>

<p>En langage Java, on doit toujours créer une "classe" et une "méthode principale" pour que l'ordinateur comprenne où commencer. On utilise des mots-clés très différents du Web.</p>

<p>Voici un répertoire des bases de la programmation en Java :</p>
<p><code>public class</code> sert à déclarer le nom du programme, <code>String[] args</code> est une instruction obligatoire pour lancer le code, et <code>System.out.println</code> est l'équivalent du <code>console.log</code> pour afficher du texte.</p>

<p>Voici à quoi ressemble un code Java pour écrire "Bonjour" :</p>
<code>
public class Main {<br>
  public static void main(String[] args) {<br>
    System.out.println("Bonjour en Java !");<br>
  }<br>
}
</code>

<p>Comme tu peux le voir, c'est beaucoup plus lourd que le JavaScript ! C'est pour cela qu'on utilise le Java pour des logiciels complexes ou des serveurs, et le JavaScript pour rendre les pages web vivantes.</p>o
<p>Une question ou une suggestion ? Contactez-moi ici : 
   <a href="mailto:lesitewebdemaxence@gmail.com">lesitewebdemaxence@gmail.com</a>
</p>
<script>
  const btn = document.querySelector('#boutonMode');
  
  btn.addEventListener('click', function() {
    // On vérifie la couleur actuelle du fond
    if (document.body.style.backgroundColor === 'black') {
      document.body.style.backgroundColor = '#f4f4f4';
      document.body.style.color = '#333';
      btn.innerText = "Passer en mode, sombre";
    } else {
      document.body.style.backgroundColor = 'black';
      document.body.style.color = 'white';
      btn.innerText = "Passer en mode clair";
    }
  });
</script>
