icon:material/information-variant
# About Diffusion Design Works

Diffusion Design Works is a Stable Diffusion model series created with the goal of producing AI Art Generations with illustration styles mimicking the look and quality of studio produced Japanese animations.

----

## What's Different from other LoRAs?

It's not a LoRA, it's a full checkpoint!

What separates this model project from other checkpoints that similarly go about recreating popular artists’ and media’s styles lies mostly on a larger, higher fidelity dataset and an emphasis on doing a full finetune training rather than training a LoRA based network that then gets merged into an SD1.x, Novel AI, or SDXL base checkpoint, giving it better flexibility with the use of other extensions such as Controlnet or AnimateDiff that may struggle to incorporate generating with additional networks enabled.

----

## Text to Image Models

### Unlimited Diffusion Works

Studio Ufotable themed Stable Diffusion 1.x based model

*Standard Text to Image Generation*

[![](./images/104188-2819849585.png){: style="width:400px"}](./images/104188-2819849585.png)
[![](./images/107011-4194903623.png){: style="width:400px"}](./images/107011-4194903623.png)
[![](./images/107115-3621427120.png){: style="width:400px"}](./images/107115-3621427120.png)
[![](./images/107574-2339296326.png){: style="width:400px"}](./images/107574-2339296326.png)

*Img2Img Movie Poster + Inpainting Upscale*

[![](./images/posterimg2img.gif){: style="width:800px"}](./images/posterimg2img.gif)

## Text to Video Models

### Motion Model Diffusion 

AnimateDiff Stable Diffusion Plug In to create Text to Video

![](./images/00109-3896167239.png){: style="width:384px"} <iframe src="https://files.catbox.moe/8ts0hn.webm" width= "384" height= "256" frameborder="0"></iframe>

AnimateDiff is a seperate motion video model that integrates the unet block information of the loaded model to generate the individual frames that then get joined together into an animation.

[![](./images/00312-1092277290-RIFE.gif)](./images/00312-1092277290-RIFE.gif) [![](./images/ContactSheet-002.png){: style="width:768px"}](./images/ContactSheet-002.png)
