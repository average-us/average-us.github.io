---
layout: single
title: "projects"
permalink: "/projects/song-rec-project"
author_profile: true
---


### Song Recommender Project (WIP)

Song recommender that extracts audio features from songs and finds similar songs using cosine similarity. Started because I wanted to try making my own Spotify-esque recommender that I can use to find new songs that I would like.

### [GitHub Link](https://github.com/average-us/music-similarity)

### Related Posts

<ul>
{% for post in site.categories.song-recommender-project %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>