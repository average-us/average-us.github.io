---
layout: single
title: "New Project Idea"
date: 2026-07-14
categories:
  - Blogging
tags:
  - Jekyll
excerpt: "Description of an idea I had"
---

### Idea

I was watching a [YouTube video](https://www.youtube.com/watch?v=nzytWZPyuEw) about how a guy used a combination of open source intelligence and machine learning to track down an animal abuser. Anyways, the video was quite interesting, and it really impressed me how he used machine learning in order to complete his objective.


He used CLIP, or Contrastive Language Image Pre Training, which is basically training a model to understand images by associating them with text, or a caption. After watching the video, I watched another video explaining how CLIP works, and an idea formed.


Basically, I want to create a CLIP model to relate the English language to a someone signing the same sentence in sign language in order to translate it.


### The Options

Making a CLIP model from scratch takes a LOT of resources and a LOT of data, so I'm not sure if I can make something good from scratch. I could probabaly take a pre-trained model, lock most of the layers, and only train some of the layers in order to save on training time and hardware requirements.


Another option, instead of all this CLIP stuff is to try to extract a wire frame "skeleton" of the hands, calculate relative distances between nodes, and feed it some labled data. The downside is that it will only ever know what I feed it, while the CLIP one could possibly translate things it has never seen before.


### Final

Anways, I really want to do this project, no matter which direction I go, but only after I get the Spotify project more refined. I'm not giving up on it; I'm still working on it (I promise).
