---
layout: default
testvar_un: My wonderful variable
testvar_deux: My wonderful deuxieme variable
---

# <i class='fa fa-bullhorn fa-rotate--20'></i> Xav test

## Images : 

![zbo logo](images/logo.png)

## Icons from FontAwesome <i class='fa fa-flag-o'></i>

  - <i class='fa fa-area-chart'></i> Area
  - <i class='fa fa-pie-chart'></i> Pie
  - <i class='fa fa-bar-chart'></i> Bar
  - <i class='fa fa-cloud'></i> Cloud
  
[More icons <i class='fa fa-external-link'></i>](http://fontawesome.io/icons/) 

## Liens : 

- [Lien interne vers le bas de la page](#test-internal-ref)
- [Lien externe vers Page 2](pages/page2.html)

## Citations :

>Machine learning is like highschool sex. Everyone says they do it, nobody really does, and no one knows what it actually is.
>-- [@Mikettownsend](https://twitter.com/Mikettownsend/status/780453119238955008).

## Code : 

    shell $> Rrrrr
    shell $> ....
    shell $> Rrrrr
    shell $> ....
    shell $> Rrrrr
    shell $> ....

```javascript
if (isAwesome){
  return true
}
```

## Todo liste

- [x] This is a complete item
- [ ] This is an incomplete item
- [ ] Essayer de faire marcher avec le theme Jekyll minima

## Emoji 

Est ce que ca marche :boom: ?

## Text formating 

- *This text will be italic*
- _This will also be italic_
- **This text will be bold**
- __This will also be bold__
- ~~This is not valid any more~~

_You **can** combine them ```the way``` you want_

## Test de substitution 

Test de {{page.testvar_un}}

Nouveau test avec {{page.testvar_deux}}

## Test de tableau

First Header | Second Header | Third Header | Forth Header
------------ | ------------- | ------------ | -------------
Content from cell 1 | Content from cell 2 | Content from cell 3 | Content from cell 4
Content from cell 1 | Content from cell 2 | Content from cell 3 | Content from cell 4
Content from cell 1 | Content from cell 2 | Content from cell 3 | Content from cell 4
Content from cell 1 | Content from cell 2 | Content from cell 3 | Content from cell 4

&nbsp;

## Aide pour formater son texte 

Go to [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/)

## Test-internal-ref

Est ce que ca marche ???

## Test de Posts dynamiques 

{% for post in site.posts %}
  - {{ post.date | date: "%b %-d, %Y" }} : [{{ post.title | escape }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

## Icons again (because I love it)

<i class='fa fa-commenting fa-4x'></i> <i class='fa fa-send-o fa-4x'></i> <i class='fa fa-envelope fa-4x'></i> <i class='fa fa-thumbs-o-up fa-4x'></i> <i class='fa fa-universal-access fa-4x'></i> 

## End of test

This is the end

[RSS]({{ "/feed.xml" | prepend: site.baseurl }})

