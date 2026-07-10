---
layout: single
title: "Song Recommender Day 9"
date: 2026-07-09
categories:
  - Blogging
  - song-recommender-project
tags:
  - Jekyll
excerpt: "Update on day 9 of the project"
---

### Good News

Ladies and gentlemen: we got em. The recommender works now. Basically, with my current listening context (that I get from the Spotify API), and the model that I trained on my listening log, it makes a recommendation in the playlist that it calculates I will be least likely to skip. And it works pretty well, except for one small thing.

### Slightly Worse News

So basically, it mostly just recommends the same songs, which I guess is to be expected since I can't actually get low level song data and the model is purely going off of the name and other features like that. But it still has some variations in the songs it recommends, which is a good sign. I'll probably make it select a random one from the top 20 thats weighted to make it less likely to recommend the songs that I've already listened to receently.


### More on What's Next

I'll keep trying to figure out how to actually get audio features, and also expand my listening log.
