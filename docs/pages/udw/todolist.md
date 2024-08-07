icon:material/update
# Status Update + To Do List

## 08/2024

### Content Update

#### ufotable Key Animation Collections

I ironically mentioned in a previous update that these Key Animations were likely going to be low priority in acquiring because there are too many of them, very expensive to obtain, and no cases I was aware of where anyone ever scanned their collection to show off these rare box sets... until about a couple days ago as of this writing. Someone scanned several of these animation key frames books. Unfortunately they were scanned in [black and white](./images/todolist/artbook/keyframe/092.jpg), they should actually be [partially colored](./images/todolist/artbook/keyframe/UwZjAmaV.jpeg) to denote color separation and shading. The scans also did not contain the illustration cards, but I had some scans of them already, and some of the frames look like they came from another set of collections, but still match the theme. Nonetheless I will add them as they are absurdly high resolution with clear detailing, until I find the colored versions.

[![](./images/todolist/full/AEFigp5.jpeg#only-light)](./images/todolist/full/AEFigp5.jpeg)
[![](./images/todolist/full/AEFigp5.png#only-dark)](./images/todolist/full/AEFigp5.png)

<span style="font-size: 80%;">*Fate/Stay Night 'Unlimited Blade Works' Character Complete Key Animations 1st - 2nd Season Comiket C88 Banner*</span>

!!! Tip "The following content to be added to a future training:"
    *   Artbook
        *   ufotable 
            *   Fate/Stay Night 'Unlimited Blade Works' Character Complete Key Animations #00 · #01
                * [Saber](./images/todolist/artbook/1182551.jpeg) - <span style="font-size: 80%;">*[Sample](./images/todolist/artbook/keyframe/093.jpg)*</span>
                * [Archer](./images/todolist/artbook/1182553.jpeg) - <span style="font-size: 80%;">*[Sample](./images/todolist/artbook/keyframe/073.jpg)*</span> - <span style="font-size: 80%;">*[Illustration Card](./images/todolist/artbook/678218.jpg)*</span>
                * [Toksaka Rin](./images/todolist/artbook/1182552.jpeg) - <span style="font-size: 80%;">*[Sample](./images/todolist/artbook/keyframe/161.jpg)*</span> - <span style="font-size: 80%;">*[Illustration Card](./images/todolist/artbook/678217.jpg)*</span> 
            *   Fate/Stay Night 'Unlimited Blade Works' Character Complete Key Animations 1st - 2nd Season
                * [Lancer](./images/todolist/artbook/55C0AA984A2C740018.jpg) - <span style="font-size: 80%;">*[Sample](./images/todolist/artbook/keyframe/008.jpg)*</span>
                * [Gilgamesh](./images/todolist/artbook/55C0AA964A025B0032.jpg) - <span style="font-size: 80%;">*[Sample](./images/todolist/artbook/keyframe/064.jpg)*</span>

#### Dataset Experiment

I'm also preparing a different kind of dataset sample from a Visual Novel that has almost fully animated sprites and cutscenes but are already seperated in frames. The game's engine would assemble all of the keyframes together in real time, so no need to frame extract the content. I would have to reassemble and animate the the scenes if I want to add it for the motion model's dataset when I attempt the finetune once UDW's next training is completed.

Will also make a point to try and get some Visual Novel assets from Witch on the Holy Night and Tsukihime prepared for this next training. Introduce the other main Type Moon artist's (Hirokazu Koyama) character designs that will be adapted in a new movie with the former, and reinforce the modern Takeuchi character designs already adapted by ufotable with the latter. The goal is to improve clean sprite resolution depictions of characters and that can be blown up to larger resolutions, using their ultra high resolution sources images (1200x5400 for example) that can be resized down or chopped up to fit various form of image composition sizes and have data for up close detailing.
                
## 07/2024

### Content Updates

#### Manual Review and Clean Up

!!! info "The following content in the current model is undergoing quality control and clean up:"
    * Fate Zero
        * <span style="font-size: 90%;">*Episode 1-19 re-extracted, Episodes 1-3 and OP/ED 1 and 2 Completed, manual review and post work still in progress*</span>
    * Fate Stay Night Unlimited Blade Works (TV)
        * <span style="font-size: 90%;">*Episode 0-12 re-extracted, Episode 0-2 and OP/ED 1 and 2 Completed, manual review and post work still in progress*</span>
    * Fate Stay Night Heaven’s Feel
        * <span style="font-size: 90%;">*1 – presage flower: re-extracted, deduped and sorted, undergoing post-processing. manual review need*</span>
        * <span style="font-size: 90%;">*2 – lost butterfly: re-extracted, deduped and sorted, undergoing post-processing. manual review need*</span>
        * <span style="font-size: 90%;">*3 – spring song: re-extracted, duplicate removal and sorting in progress, some stitching completed*</span>
    * The Garden of Sinners 
        * <span style="font-size: 90%;">*8 – Epilogue: re-extracted, deduped and sorted, undergoing post-processing, manual review done*</span>
        * <span style="font-size: 90%;">*9 – Future Gospel: re-extracted, clean up in Progress, some stitching completed*</span>
        * <span style="font-size: 90%;">*9.5 Future Gospel – Extra Chorus: re-extracted, deduped and sorted, undergoing post-processing, manual review done*</span>
    * Fate Stay Night [Réalta Nua]
        * <span style="font-size: 80%;">*Opening Animations*</span>
            * <span style="font-size: 90%;">*re-extracted, deduped and sorted, undergoing post-processing. manual review need*</span>
    * Fate/Hollow Ataraxia
        * <span style="font-size: 80%;">*Opening Animations*</span>
            * <span style="font-size: 90%;">*re-extracted, deduped and sorted, undergoing post-processing. manual review need*</span>


#### Ready To Train

[![](./images/todolist/thumb/Layer-3-Crop.png){: style="width:170px"}](./images/todolist//full/knk6.jpg)
[![](./images/todolist/thumb/Layer-2-Crop.png){: style="width:170px"}](./images/todolist/full/tozx.jpg)
[![](./images/todolist/thumb/Layer-1-Crop.png){: style="width:170px"}](./images/todolist/full/ktrfull.jpg)
[![](./images/todolist/thumb/Layer-4-Crop.png){: style="width:170px"}](./images/todolist/full/tob.png)


!!! success "The following content will be included in the next training session - minimal manual edits only:"
    *   Movies
        *   The Garden of Sinners 
            * 3 – Remaining Sense of Pain
            * 4 – The Hollow Shrine
            * 5 – Paradox Spiral
            * 6 – Oblivion Recorder
            * 7 – A Study in Murder - Part 2
    *   TV 
        *   Katsugeki/Touken Ranbu
        *   Tales of Zestiria the X  (Season 1)
    *   Video Games
        *   Tales of Zestiria
            * <span style="font-size: 80%;">*Opening Animations and Cutscenes*</span>
        *   Tales of Berseria
            * <span style="font-size: 80%;">*Opening Animations and Cutscenes*</span>
        *   Tsukihime -A piece of blue glass moon-
            * <span style="font-size: 80%;">*Opening Animations*</span>
    *   Mobile
        *   Fate Grand Order
            *   [The Garden of Sinners] crossover event
                * <span style="font-size: 80%;">*ufotable assets and promotional animation only*</span>
            *   [Fate Zero] crossover event
                * <span style="font-size: 80%;">*ufotable promotional animation only*</span>
            *   [Fate Stay Night - Heaven's Feel] movie premiere promotions
                * <span style="font-size: 80%;">*ufotable assets only*</span>

----

#### In Progress

[![](./images/todolist/thumb/Layer-5-Crop.png){: style="width:170px"}](./images/todolist//full/tsukire.jpg)
[![](./images/todolist/thumb/Layer-6-Crop.png){: style="width:170px"}](./images/todolist/full/mahoyofull.png)
[![](./images/todolist/thumb/Layer-7-Crop.png){: style="width:170px"}](./images/todolist/full/tos.jpg)
[![](./images/todolist/thumb/Layer-8-Crop.png){: style="width:170px"}](./images/todolist/full/kny.png)

!!! example "The following will be included in a future session - not ready, not ufotable content, lower priority, or limited disk space"

    *   Artbooks
        *   [The Garden of Sinners: The Animation by Ufotable](./images/todolist/artbook/81WRhFUmhFL._SL1500_.jpg)
            * <span style="font-size: 80%;">*Have physical source, needs to be scanned*</span>
        *   [The Garden of Sinners: Complete Illustration Art Book by Takeuchi Takashi](./images/todolist/artbook/9784062186971_w.jpg)
            * <span style="font-size: 80%;">*Have physical source, needs to be scanned*</span>

    *   Movies
        *   The Garden of Sinners 
            * 1 – Overlooking View
                * <span style="font-size: 80%;">*Have source media, not extracted*</span>
            * 2 – A Study in Murder - Part 1: 
                * <span style="font-size: 80%;">*Have source media, not extracted*</span>
        *   Tales of Symphonia
            * <span style="font-size: 80%;">*Have not finalized a source*</span>
        *   Demon Slayer - Mugen Train
            * <span style="font-size: 80%;">*Have not finalized a source*</span>
    *   TV
        *   Tales of Zestiria the X (TV - Season 2)
            * <span style="font-size: 80%;">*Have source media, not extracted*</span>
        *   Today's Menu for the Emiya Family  
            * <span style="font-size: 80%;">*Have source media, not extracted*</span>     
        *   Demon Slayer
            * <span style="font-size: 80%;">*Have not finalized a source*</span>
    *   Video Games
        *   Tales of Xillia I
            * <span style="font-size: 80%;">*Openings and cutscenes extracted, Not sorted*</span>
        *   Tales of Xillia II
            * <span style="font-size: 80%;">*Openings and cutscenes extracted, Not sorted*</span>
        *   Witch on the Holy Night
            * <span style="font-size: 80%;">*Not ufotable, assembling in-game sprites and CG assets*</span>
        *   Tsukihime -A piece of blue glass moon-
            * <span style="font-size: 80%;">*Assembling non-ufotable in-game sprites and CG assets*</span>
    *   Mobile
        *   Tales of Asteria 
            * <span style="font-size: 80%;">*ufotable assets only*</span>
        *   Tales of Crestoria
            * <span style="font-size: 80%;">*ufotable assets only*</span>

----

#### TBD

!!! failure "Waiting on USM decryption for the following games to frame extract cutscenes"
    *   Video Games
        *   Tales of Arise
            *   <span style="font-size: 80%;">*Have usm video files on standby*</span>

!!! failure "Awaiting sale or alternate source for follow collections"
    *   Artbook
        *   ufotable 
            *   [The Garden of Sinners - Seikaisha (Background Art Book)](./images/todolist/artbook/91vngIKYgCL._SL1500_.jpg)
            *   [The Garden of Sinners - Future Gospel New Years Illustrations Postcards [Comiket 85]](./images/todolist/artbook/000.jpg)
                * <span style="font-size: 80%;">*A scan of this exists online but what looks to be dust or fuzz on the images from when it was scanned is obscuring fine details.*</span>
            *   [Fate/Zero - Seikaisha (Background Art Book)](./images/todolist/artbook/91NlW-xGcBL._SL1500_.jpg)
            *   [Fate/Stay night 'Unlimited Blade Works' - Seikaisha (Background Art Book)](./images/todolist/artbook/9784062198738_w.jpg)
            *   [Fate/Stay Night 'Unlimited Blade Works' S1 - Settei Shiryoushuu (Setting Material) [Comiket 87]](./images/todolist/artbook/55C0AAA247644B001F.jpg)
            *   [Fate/Stay Night 'Unlimited Blade Works' S2- Settei Shiryoushuu (Setting Material) [Comiket 88]](./images/todolist/artbook/55C0AA9F470499000C.jpg)
            *   [Fate/Stay Night 'Unlimited Blade Works' Character Complete Key Animations [Comiket 87, 88, 89]](./images/todolist/artbook/55C0AA924A17CD0025.jpg)
                *   <span style="font-size: 80%;">*There's 10 of these, very low priority in seeking out product or scans of it other than to obtain it's included lineart image. [#1](./images/todolist/artbook/686658.jpg), [#2](./images/todolist/artbook/686659.jpg)*</span>

!!! failure "Waiting on releases for the following Ufotable Media:"
    *   Movies
        *   Witch on the Holy Night
            *   <span style="font-size: 80%;">*Have rips of the trailers for quality source testing on standby: [#1](https://www.youtube.com/watch?v=OujIyh_h-M4), [#2](https://www.youtube.com/watch?v=IqUZ6y6ldeA)*</span>
    *   TV
        *   Untitled Genshin Impact Animation
            *   <span style="font-size: 80%;">*[Have rip of trailer for quality source testing on standby](https://www.youtube.com/watch?v=V07G0_PE2CE)*</span>
    *   Mobile
        *   Honkai Starrail 
            *   <span style="font-size: 80%;">*[Fate Stay Night - Unlimited Blade Works] crossover event*</span>

----