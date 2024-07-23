icon:material/information-variant
# About Diffusion Design Works

Diffusion Design Works is a Stable Diffusion model series created with the goal of producing AI Art Generations with illustration styles mimicking the look and quality of studio produced Japanese animations.

----

## What's Different from other LoRAs?

It's not a LoRA, it's a full checkpoint!

What separates this model project from other checkpoints that similarly go about recreating popular artists’ and media’s styles lies mostly on a larger, higher fidelity dataset and an emphasis on doing a full finetune training rather than training a LoRA based network that then gets merged into an SD1.x, Novel AI, or SDXL base checkpoint, giving it better flexibility with the use of other extensions such as Controlnet or AnimateDiff that may struggle to incorporate generating with additional networks enabled.

----

## T2I Models

### Unlimited Diffusion Works

Studio Ufotable theme Stable Diffusion 1 Based Model

*Standard Text 2 Image Generation*

![](.\images\104188-2819849585.png){: style="width:49.5%"}
![](.\images\107011-4194903623.png){: style="width:49.5%"}
![](.\images\107115-3621427120.png){: style="width:49.5%"}
![](.\images\107574-2339296326.png){: style="width:49.5%"}

*Img2Img Movie Poster + Inpainting Upscale*

![](.\images\BrotherhoodWolf.png){: style="width:32.5%"}
![](.\images\00341-100224763.png){: style="width:32.5%"}
![](.\images\00474-3492909164.png){: style="width:32.5%"}

## T2V Models

### Motion Model Diffusion 

AnimateDiff Stable Diffusion Plug In to create Text to Video

![](.\images\00109-3896167239.png){: style="width:49.5%"} <iframe src="https://files.catbox.moe/8ts0hn.webm" width= "384" height= "256" frameborder="0"></iframe>



![](.\images\ContactSheet-002.png){: style="width:47.4%"} <iframe src="https://files.catbox.moe/0bef63.webm" width= "400" height= "270" frameborder="0"></iframe>

AnimateDiff uses the loadded model to generate individual frames that then get joined together into an animation
