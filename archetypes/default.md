---
title: "Title for your recipe"
recipe_image: {{ .Site.Params.front.defaultImage | default "images/defaultImage.png" }}
image_width: {{ .Site.Params.front.defaultImageWidth | default 512 }}
image_height: {{ .Site.Params.front.defaultImageHeight | default 512 }}
date: {{ .Date }}
tags: ["tag1", "tag2"]
servings: 4
prep_time: #in minutes, can be BLANK
cook: true # If cooking leave true, if cooling set to false
cook_increment: minutes # set to minutes or hours
cook_time: #in minutes or hours, can be BLANK
calories: #in kcal, can be BLANK
---

## Ingrédients

- Premier
- Second [^1]

## Instructions

1. Première étape
   1. Première sous étape
2. Seconde étape

## Notes

[^1]: Détails
