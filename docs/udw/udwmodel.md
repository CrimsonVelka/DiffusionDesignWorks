icon:material/ufo-outline
# Unlimited Diffusion Works (UDW)
## Overview

Unlimited Diffusion Works is a model based on the works of animation studio ufotable, whos works including:

* 14 Animated Films
* 15 TV Shows 
* 17 Video Game Opening Animations and Cutscenes

With this much material overarching several different franchises handed by different animators displaying a variety of styles, settings, and characters; while all the works still having the studio's distinct finish, it is a great source of material to make a model that can stay consistent across the board and still make unique images that don't look too much like carbon copies of what it's based on. 

## Dataset

![](./images/Key Visual/fatezerokv1.jpg){: style="height:250px;width:161px"}
![](./images/Key Visual/ubwkv1.jpg){: style="height:250px;width:161px"}
![](./images/Key Visual/hf3kv1.jpg){: style="height:250px;width:161px"}
![](./images/Key Visual/knkekv1.jpg){: style="height:250px;width:161px"}
![](./images/Key Visual/emcfkv.jpg){: style="height:250px;width:161px"}


This model’s current version was trained on 09/2023, with around 200k images over NovelAI v1, uses the following content from studio ufotable:

### ufotable sources

```
Fate Zero 
The Garden of Sinners 8 – Epilogue
The Garden of Sinners 9 - Future Gospel
The Garden of Sinners 9.5 - Future Gospel: Extra Chorus
Fate Stay Night [Réalta Nua]
Fate Stay Night Unlimited Blade Works
Fate/Hollow Ataraxia
Fate Stay Night Heaven’s Feel Trilogy
```

### Non-themed sources 

In addition to ufotable, I added for experimentation purposes the dataset from the following non ufotable works for additional data and regularization purposes:
```
Lord El-Melloi II Case Files (TV – Studio Troyca)
*and additional miscellaneous non-animation frame data not from danbooru*
```
Dataset was created by running Blu-ray rips of the listed content through ffmpeg as part of the aid of [Anime Screenshot Pipeline](https://github.com/cyber-meow/anime_screenshot_pipeline) on Github back in February of 2023.


## Sample Gallery

### Main Theme Assorted Samples

![](./images/71966-357371757.png){: style="width:48.5%"}
![](./images/73082-256545115.png){: style="width:48.5%"}
![](./images/72307-3288374492.png){: style="width:48.5%"}
![](./images/72333-3049597417.png){: style="width:48.5%"}
![](./images/73815-2911211619.png){: style="width:410px"}
![](./images/74919-646950122.png){: style="width:410px"}
![](./images/71234-3241660550.png){: style="width:410px"}
![](./images/107655-3787594491.png){: style="width:410px"}

### 16:9 Screen Resolution TV/Movie Look Examples

![](./images/68981-3336393614.png){: style="width:400px"}
![](./images/68792-2210440585.png){: style="width:400px"}
![](./images/87508-1453217043.png){: style="width:400px"}
![](./images/87590-2557507210.png){: style="width:400px"}
![](./images/88147-1535975933.png){: style="width:400px"}
![](./images/98315-3984287718.png){: style="width:400px"}

### Key Art Resolution Style Examples

![](./images/61824-1959696816.png){: style="width:400px;height:500px"}
![](./images/55835-2128820733.png){: style="width:400px"}
![](./images/60607-3231689894.png){: style="width:400px"}
![](./images/61060-2296952070.png){: style="width:400px"}

### Concept Art Style Mock Up Examples

![](./images/63265-885359435.png){: style="width:400px"}
![](./images/63291-3832714336.png){: style="width:400px"}
![](./images/63322-1230264608.png){: style="width:400px"}
![](./images/63324-2435138676.png){: style="width:400px"}


## Status Updates

After many trainings however, I had become dissatisfied with the quality of the dataset it originally produced, and didn't even use parts of the for what I needed. Through repurposing and editing some of tools and scripts, I redid the entire dataset from scratch after several months of doing initial training tests before committing to an overall.