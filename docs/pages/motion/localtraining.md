icon:fontawesome/solid/network-wired
# Local Training of AnimeateDiff

## Homebrew Potential

Sometime this year, the developers of AnimateDiff disclosed their training method, and since then only one decent finetune fork was created where the training resolution was doubled, but no new data was added due a lack of video tagging tools. While not a significant leap, it shows that enthusiasts are interested in pursuing this tech. With the visibility of the video dataset now clear, the path is open for those that have the hardware to finetune the motion model. 

[WebVid10M](https://github.com/m-bain/webvid) [(Mirror for education purposes)](https://huggingface.co/datasets/TempoFunk/webvid-10M), is comprised of low-resolution watermarked previews of shutterstock footage run through their own classifier as part of a larger project the group worked on. With a good stating off point, my existing pipeline for SD can be adjusted to incorporate new video clips, need only to use their Video trainer `Video2dataset` and repurpose the media rips I already have.

----

## Theoretical Pipeline

Since specific tuning is not required, we are open to using more types of movies, recordings, and other animations not necessarily related to official films and shows or even the ones we are using. 

Say we have access to a collection of videos. What we can create a [script that will generate timestamps](https://www.youtube.com/watch?v=nOeaFEHuFyM), similar to chapter select codes for Blu-Rays or steaming services, to mark every time there is a jumpcut to a new scene or camera shot. This will get written onto a sidecar file. 
Then with ffmpeg, use the video clip command with the sidecar automate the video clips slices. These clips will then be tagged and captioned and can be organized within Hydrus (Hydrus also can organize video format files) and use the same image organization tools to manually review tags and captions every time we need to train the model. 

!!! tip "Potential Prompting Improvement"

    * An addition step that can be performed to improve prompting results on the finetune is to introduce the Danbooru/Novel AI tag format as well as keeping the natural language captioning. Keeping the tagging consistent across both the main model and the motion model will cause less confusion for the final generation as both models will have a similar format to follow. 
    * A method to do this would be to take some frames from the peak of each clip, run the SD Tagger on it, and then apply those tags onto its corresponding video clip on Hydrus. 

Steps:

1. FFMPEG 
    * Create scene jump cut timestamp sidecar txt file from video 
    * Created segmented clips with ffmpeg 
2. Tagger (Video)
    * Run a video-based caption classifier on clips 
3. Tagger (Image - Optional)
    * Semi-automate additional Danbooru/NovelAI format tags 
        * Use frames from scenes to aggregate and average out compatible tags
4. Hydrus
    * Manual review dataset
6. Video2dataset
    * Export to trainer
7. Debug
    * Rinse and Repeat

From there it would be business as usual on the training front, depending on whether our local resources are sufficent to run the job ourselves.

----