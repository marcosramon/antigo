---
title: Ficções
layout: page
description: "Narrativas filosóficas."
permalink: /ficcoes
image: ficcoes-sp.png
---

<i class="icon-twitter"></i> <a href="https://twitter.com/PodcastFiccoes">@PodcastFiccoes</a>

<iframe src="https://embed.podcasts.apple.com/us/podcast/fic%C3%A7%C3%B5es/id967600465?itsct=podcast_box&amp;itscg=30200" sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-top-navigation-by-user-activation" allow="autoplay *; encrypted-media *;" style="width: 100%; max-width: 660px; overflow: hidden; border-radius: 10px; background: transparent none repeat scroll 0% 0%;" height="450px" frameborder="0"></iframe>

---

Para ouvir todos os episódios use um dos links a seguir:

<a href="https://open.spotify.com/show/1smphr2Sl3kHncMYB984rc"><img src="/assets/images/spotify-badge.png" width="165px" height="40px"></a> 

<a href="https://www.google.com/podcasts?feed=aHR0cHM6Ly9hbmNob3IuZm0vcy9hOWM4NWIwL3BvZGNhc3QvcnNz"><img src="/assets/images/google_podcasts.png" width="165px" height="40px"></a>

<a href="https://podcasts.apple.com/br/podcast/fic%C3%A7%C3%B5es/id967600465?mt=2&app=podcast" style="display:inline-block;overflow:hidden;background:url(https://linkmaker.itunes.apple.com/pt-br/badge-lrg.svg?releaseDate=2020-05-26T00:00:00Z&kind=podcast&bubble=podcasts) no-repeat;width:165px;height:40px;"></a> 

<i class="icon-rss"></i> <a href="https://anchor.fm/s/a9c85b0/podcast/rss">RSS</a>

Narrativas filosóficas.

Me ajude a continuar produzindo o podcast e outros projetos na internet: [marcosramon.net/apoie](https://marcosramon.net/apoie){:target="_blank"}

---

Na lista abaixo você encontra algumas publicações. Para acessar os quase 500 episódios, utilize o [Google Podcasts](https://www.google.com/podcasts?feed=aHR0cHM6Ly9hbmNob3IuZm0vcy9hOWM4NWIwL3BvZGNhc3QvcnNz){:target="_blank"} ou outro app de sua preferência.
<br>
{% for post in site.categories.ficcoes %}
  <li><span><a href="{{ post.url }}">{{ post.title }}</a></span> &nbsp; <span>{{ post.date | date_to_string }}</span></li>
{% endfor %}
