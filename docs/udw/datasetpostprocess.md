icon:material/account-box-edit-outline
# Dataset post processing

There are 3 additional processes I do to my dataset that combat either certain flaws in the dataset, cleaning up data that could have production mistakes or bothersome editing choices, and maximize the amount of detail of specific shots or scenes: Layering, Cropping, and Stitching.

!!! info
    
    * SD1.x is trained on 512x512 resolution images, a size of 262,144 Pixels

    * Novel AI continues training from SD1.4 with 768x768 resolution images, a size of 589,824 Pixels

    * SDXL is trained on 1024x1024 resolution images, a size of 1,048,576 Pixels
    
    * Most enthusiast’s LoRAs are still trained on 512x512 due to their hardware constraints

## Layering
Say I have a shot of store front backdrop with a lot of moving foreground pieces, but not a single frame has a clean shot of that backdrop, but if I piece together enough separate frames together on top of each other and mask out the unwanted bits, I can create a clean frame edit of the backdrop that then I can include in my dataset. Then I can reintroduce some separate frames with the foreground pieces to train concept of being able to draw an empty room or location, and that same spot with people or other moving subjects. This is not something I prioritize often, but when a particular scene with too many movie pieces shows up that I feel is worth doing the work to get

## Stitching

In any sort of motion picture, you will get scenes where the camera is panning from one direction another to either show off a landscape shot, or a character’s reveal a sizing up of several characters in the prelude to a confrontation. The frames by themselves may not be quite useful, but they would be if you had a completed picture. I will take a scene and either using a Photoshop or Lightroom tool to stich the pieces together, or I will manually layer the frames together if it’s a complex shot, to have a single complete picture. This also gives provides an additional resolution sizes that the model can train on, fighting the potential overfit that can be caused by training almost exclusively on 16:9 resolution images. I will still include some of the separate frames in full if there is detail in them I want the model to train on.

## Cropping

While originally a requirement to make 1:1 crop cutouts of images for your dataset in the early days of Stable Diffusion Dreambooth training, the introduction and source code release for Aspect Ratio Bucketing by NovelAI allowed the use of any resolution size for datasets and would be sized to fit a resolution bucket for training. This crop and resizing down of the full images however will cause a loss in detail of the image as the bucket still needs to comply with the 1:1 aspect pixel size, and those buckets will always have a lower pixel count than the default training resolution, so a large image like a 1920x1080 blu-ray frame or any other 2MP image from an imageboard getting crunched down will cause the model to lose out on information detail. To combat this, I also include sizable amount of 1:1 aspect images. These focus on facial expressions, certain detail focus shots of objects and items, character’s extremities to improve hand and finger accuracy, or close ups of clothing and/or patterns. I will also use this on the same frames of stitches I created, if possible, to also preserve those details of panning shots. The 1:1 aspect images also help in reducing overfit from the main resolution.
