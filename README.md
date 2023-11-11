# My Homepage

Se reposent ici les fichiers HTML, CSS, et JavaScript qui comprend mon exemple d'un site du web personnel.

## Comment commencer à créer le votre ?

Tout d'abord, il faut comprendre les idées basiques du HTML.

Puis, on ajoute des styles avec du CSS.

Enfin, si on souhaite, on peut introduire de l'interactivité avec du JavaScript.

### HTML

HTML nous provient le structure d'un page web. Il a été inventé avant que tous nous ne soient nées (probablement) en 1990. C'est tout simplement la langue du markup de l'hypertext, ou en anglais (comme était la langue maternelle de son inventeur Tim Berners-Lee) : Hypertext Markup Language.

L'idée dans un langue de "markup" est simple : de remarquer notre intention du type d'information. Il existe plein des autre, plus notable pour le HTML est son cousin XML, la langue de markup extensible (en anglais _Extensible Markup Language_).

On ajoute une idée pour aider la navigation dans les fichiers longs de HTML : les _anchors_, ce qu'on utilise en tant de table des contents afin de fait bouger le lecteur.
C'est pareil avec l'idée de trouver la chanson prochaine sur un CD.
En lisant un disque vinyle, on peut pas le faire, dans la même façon que dans un document en papier, on ne peut pas avancer en manière automatique jusqu'au section prochain.

Cette idée des anchors se déroule vite et bientôt on aurait les hyperlinks — liens pas juste dedans un seul document, mais entre eux.

On crée des elements avec des tags comme `<a>` pour les liens, `<p>` pour les paragraphs, `<h1>` pour le titre principal du page, et `<h2>` à `<h6>` pour les titres des sections et leurs sous-sections.

Un petit exemple :

```html
<h1>Robin James Kerrison : Accueil</h1>
<p>
  Bonjour et bienvenue chez moi. Veuillez trouver plus d'informations en lisant
  <a href="/a-propos-de-robin.html"
    >le guide de tout ce qu'on veut dire lorsqu'on parle de Robin</a
  >
</p>
```

### CSS

CSS, _Cascading Style Sheets_, sont des feuilles (voire fichiers) qui emporte du style dans nos

Ils fut introduits en 1993, afin de rendre plus stylé le _world wide web_.

Mais pourquoi "cascading"?

Bonne question, _insérez votre prénom_.

L'idée de la cascade, c'est que chaque régle qu'on écrit dans le CSS appliquent partout dans le document HTML concerné, et peut être étendu par les prochains régles.
Comme ça, c'est plutôt un glisse de terrain qu'un cascade.

Voilà un exemple :

```css
a {
  color: blue;
}

p a {
  background-color: yellow;
}
```

Comme ça, la régle qui rend bleu les liens appliquent partout, lorsque la régle qui rend jaune leur fond de toile appliquent seulement dans le contexte d'un paragraph.
