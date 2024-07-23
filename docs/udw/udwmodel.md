icon:material/ufo-outline
# Unlimited Diffusion Works (UDW)
## Overview

Unlimited Diffusion Works is a model based on the works of animation studio ufotable, whos works including 14 Animated Films, 15 TV Shows, and Opening Animations and Cutscenes for 17 Video Game works for several different franchises, giving a diverse palate of different animators, styles, settings, and subjects while having a recognizable visual finish due to their CGI usage and consistent color grading technique. 

## Dataset

This model’s current version was trained on 09/2023, with around 200k images over NovelAI v1, uses the following content from studio ufotable:
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
In addition to ufotable, I added for experimentation purposes the dataset from the following non ufotable works for additional data and regularization purposes:
```
Lord El-Melloi II Case Files (TV – Studio Troyca)
*and additional miscellaneous non-animation frame data not from danbooru*
```

Dataset was created by running Blu-ray rips of the listed content through ffmpeg as part of the aid of Anime-Screenshot-Pipeline on Github back in February of 2023, but I had quickly become dissatisfied with the quality of the dataset it originally produced, and parts of its pipeline were not useful for what I needed, thus I took some tools, repurposed and/or modified settings, and redid the entire dataset after several months of doing initial training tests before committing to an overall.
