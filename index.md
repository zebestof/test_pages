---
layout: default
testvar_un: My wonderful variable
testvar_deux: My wonderful deuxieme variable
---

## Xav test

### Images : 

![zbo logo](images/logo.png)

### Liens : 

- [Lien interne vers le bas de la page](#test-internal-ref)
- [Lien externe vers Page 2](pages/page2.html)

### Citations :

>Machine learning is like highschool sex. Everyone says they do it, nobody really does, and no one knows what it actually is.
>-- [@Mikettownsend](https://twitter.com/Mikettownsend/status/780453119238955008).

### Code : 

    shell $> Rrrrr
    shell $> ....
    shell $> Rrrrr
    shell $> ....
    shell $> Rrrrr
    shell $> ....

### Test de substitution 

Test de {{page.testvar_un}}

Nouveau test avec {{page.testvar_deux}}

### Test de tableau

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

&nbsp;

### Aide pour formater son texte 

Go to [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/)

### Test-internal-ref

Est ce que ca marche ???

### Test de Posts dynamiques 

{% for post in site.posts %}
- {{ post.date | date: "%b %-d, %Y" }} : [{{ post.title | escape }}]({{ post.url | prepend: site.baseurl }})
{% endfor %}

[RSS]({{ "/feed.xml" | prepend: site.baseurl }})
