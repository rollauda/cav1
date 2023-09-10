---
title: Essai
layout: default
nav_order: 30
has_children: false
permalink: /Modeles/essai
published: false
---

pour programmer la publication d'un post pour le 1er janvier 2023 à 12h00 UTC, vous pouvez ajouter les lignes suivantes au fichier Markdown du post :

--
title: My post
scheduled_at: 2023-01-01T12:00:00Z
--

This is my post. It will be published on January 1, 2023, at 12:00 UTC.

Notez que l'attribut scheduled_at doit être une date-heure au format ISO 8601. Le format ISO 8601 est un format universel pour représenter les dates et les heures. Il est composé de l'année, du mois, du jour, de l'heure, des minutes et des secondes.

---

![image](../assets/img/schema_conscience.svg)

# Tests
{: .no_toc }

<details open markdown="block">
  <summary>
    Sommaire
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## lien 
[page](https://truc.com)

## image
![on image](../../assets/img/caverne-harambat2.jpeg)

**taille limitée**

<img src="../../assets/img/caverne-harambat2.jpeg"  width="75%">

## Embed pdf

{% pdf "../assets/pdf/presentation.pdf" no_link %}

**Taille limitée:**  

{% pdf "../assets/pdf/presentation.pdf" width=80% height=600px no_link %}

## video local

<video src="../../assets/vid/inherit.mp4" controls="controls" style="max-width: 730px;">


## Video youtube

<iframe width="560" height="315" src="https://www.youtube.com/embed/_-SO6rBizQc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Vimeo

<iframe src="https://player.vimeo.com/video/430695?h=b9727ea27a" width="640" height="479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

## Tableaux

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

## embed markmap

<iframe src="../assets/html/schema_conscience.html" width="100%" height="600px" frameborder="0"></iframe>

<iframe src="../../assets/cartes/carte1.html" width="100%" height="600px" frameborder="0"></iframe>

