# Setting vari - prove
Questo file "note" contiene varie prove effettuate nei setting del codice.



## {% block announce %}
Per inserire una barra sopra l'header.

Il 10.11.2021 ho eliminato dal file override/main.html:

``` markdown
{% extends "base.html" %}

<!-- Add announcement here, including arbitrary HTML (https://squidfunk.github.io/mkdocs-material/setup/setting-up-the-header/#announcement-bar) -->]
{% block announce %}
<span style="background-color: #f50505; color: #ffffff; padding: 0px 3px; border-radius: 4px;">Mappatura e analisi dei procedimenti amministrativi ai fini della digitalizzazione</span>
{% endblock %}
```


## Code annotation
riferimento: https://squidfunk.github.io/mkdocs-material/reference/code-blocks/#adding-annotations

``` { .yaml .annotate }
theme:
  features:
    - content.code.annotate # (1)
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted text__, images, ... basically anything that can be expressed in `Markdown`.



## Catalogo
ho tolto l'iframe dal file `mappatura-procedimenti/7-catalogo-procedimenti.md`

<iframe src="https://uo-transizionedigitalecomunepalermo.github.io/procedimenti-amministrativi-comunepalermo/" height="83000"; width="100%"; frameborder="0"; > </iframe>


## Flowchart
https://mermaid-js.github.io/mermaid/#/flowchart
