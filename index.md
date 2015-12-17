---
layout: default
---

Texte d'intro de la page d'accueil

<div class="row">
  {% for post in site.posts %}
    <div class="col-md-4 img-portfolio">
      
                <a href="{{ post.url }}">
                    <img class="img-responsive img-hover" src="http://placehold.it/700x400" alt="">
                </a>  
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>

    <p>{{ post.excerpt }}</p>
    </div>
  {% endfor %}
</div>