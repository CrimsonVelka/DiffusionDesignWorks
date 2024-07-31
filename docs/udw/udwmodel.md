icon:material/ufo-outline
# Unlimited Diffusion Works (UDW)
## Overview

Unlimited Diffusion Works is a model based on the works of animation studio ufotable, whose works include:

* 14 Animated Films
* 15 TV Shows 
* 17 Video Game Opening Animations and Cutscenes

This model will focus on their studio's adaptations of works by Type-Moon, and will include their collaborations on series produced by Namco Bandai, to have a set level of character design, color grading, quality consistency.

## Dataset

[![](./images/overview/dataset/thumb/knkekv1-thumb.png){: style="width:170px"}](./images/overview/dataset/full/knkekv1.jpg)
[![](./images/overview/dataset/thumb/fatezerokv1-thumb.png){: style="width:170px"}](./images/overview/dataset/full/fatezerokv1.jpg)
[![](./images/overview/dataset/thumb/ubwkv1-thumb.png){: style="width:170px"}](./images/overview/dataset/full/ubwkv1.jpg)
[![](./images/overview/dataset/thumb/hf1kv1-thumb.png){: style="width:170px"}](./images/overview/dataset/full/hf1kv1.jpg)


This model’s current version was trained on 09/2023, with around 200k images finetuned over NovelAI v1, uses the following content from studio ufotable:

!!! abstract "ufotable sources"
    
    * Fate Zero 
    * The Garden of Sinners
        * 8 - Epilogue
        * 9 - Future Gospel
        * 9.5 - Future Gospel: Extra Chorus
    * Fate Stay Night [Réalta Nua]
    * Fate Stay Night Unlimited Blade Works
    * Fate/Hollow Ataraxia
    * Fate Stay Night Heaven’s Feel
        * 1 - presage flower
        * 2 - lost butterfly
        * 3 - spring song

In addition to ufotable, I added for experimentation purposes content from the following non-ufotable works for additional data and regularization purposes:

!!! abstract "Non-themed sources"
    * Lord El-Melloi II Case Files (studio TROYCA)
    * *additional miscellaneous non-animation data*


The original dataset was created by running Blu-ray rips of the listed content through ffmpeg as part of the aid of [Anime Screenshot Pipeline](https://github.com/cyber-meow/anime_screenshot_pipeline) on Github back in February of 2023. But I have since used [my own workflow pipeline processes](./udwpipeline.md) and modified or used new tools to improve the training and creation of the current model back in 09/2023.


## Sample Gallery

### Main Theme Assorted Samples

[![](./images/overview/keyvisual/full/71966-357371757.png){: style="width:340px"}](./images/overview/keyvisual/full/71966-357371757.png)
[![](./images/overview/keyvisual/full/73082-256545115.png){: style="width:340px"}](./images/overview/keyvisual/full/73082-256545115.png)
[![](./images/overview/keyvisual/full/72307-3288374492.png){: style="width:340px"}](./images/overview/keyvisual/full/72307-3288374492.png)
[![](./images/overview/keyvisual/full/72333-3049597417.png){: style="width:340px"}](./images/overview/keyvisual/full/72333-3049597417.png)
[![](./images/overview/blurayres/73815-2911211619.png){: style="width:340px"}](./images/overview/blurayres/73815-2911211619.png)
[![](./images/overview/blurayres/74919-646950122.png){: style="width:340px"}](./images/overview/blurayres/74919-646950122.png)
[![](./images/overview/conceptart/71234-3241660550.png){: style="width:340px"}](./images/overview/conceptart/71234-3241660550.png)
[![](./images/overview/conceptart/107655-3787594491.png){: style="width:340px"}](./images/overview/conceptart/107655-3787594491.png)

### 16:9 Screen Resolution TV/Movie Look Examples

[![](./images/overview/blurayres/68981-3336393614.png){: style="width:340px"}](./images/overview/blurayres/68981-3336393614.png)
[![](./images/overview/blurayres/68792-2210440585.png){: style="width:340px"}](./images/overview/blurayres/68792-2210440585.png)
[![](./images/overview/blurayres/87508-1453217043.png){: style="width:340px"}](./images/overview/blurayres/87508-1453217043.png)
[![](./images/overview/blurayres/87590-2557507210.png){: style="width:340px"}](./images/overview/blurayres/87590-2557507210.png)
[![](./images/overview/blurayres/88147-1535975933.png){: style="width:340px"}](./images/overview/blurayres/88147-1535975933.png)
[![](./images/overview/blurayres/98315-3984287718.png){: style="width:340px"}](./images/overview/blurayres/98315-3984287718.png)

### Key Visual Resolution Style Examples

[![](./images/overview/keyvisual/thumb/Layer-9-Crop.png){: style="width:340px"}](./images/overview/keyvisual/full/61824-1959696816.png)
[![](./images/overview/keyvisual/thumb/Layer-10-Crop.png){: style="width:340px"}](./images/overview/keyvisual/full/55835-2128820733.png)
[![](./images/overview/keyvisual/thumb/Layer-11-Crop.png){: style="width:340px"}](./images/overview/keyvisual/full/60607-3231689894.png)
[![](./images/overview/keyvisual/thumb/Layer-13-Crop.png){: style="width:340px"}](./images/overview/keyvisual/full/01470-2327565163.png)

### Concept Art Style Mock Up Examples

[![](./images/overview/conceptart/63265-885359435.png){: style="width:340px"}](./images/overview/conceptart/63265-885359435.png)
[![](./images/overview/conceptart/63291-3832714336.png){: style="width:340px"}](./images/overview/conceptart/63291-3832714336.png)
[![](./images/overview/conceptart/63322-1230264608.png){: style="width:340px"}](./images/overview/conceptart/63322-1230264608.png)
[![](./images/overview/conceptart/63324-2435138676.png){: style="width:340px"}](./images/overview/conceptart/63324-2435138676.png)

----