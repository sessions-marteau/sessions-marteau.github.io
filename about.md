---
layout: page
title: A propos
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

<!-- ## Some heading  -->

Inspirées par les meikyoku kissaten* au Japon, Les sessions Marteau réhabilitent l'écoute de la musique dans un espace où le public peut ralentir et s’immerger dans l’univers de pièces musicales sélectionnées avec soin par des commissaires invités.
 
Ces sessions d’écoute ont pour but d’offrir au public un répertoire musical rare ou méconnu, rendu accessible dans ce contexte grâce aux collections de partenaires.

* Meikyoku kissaten, que l'on pourrait traduire par « cafés muets où l'on écoute des chefs-d'œuvre musicaux », ont vu le jour dans les années 1940 dans le but de démocratiser l'accès à des enregistrements.

</div>
