# Generative AI - Text to Video, Image and Audio in Blender
AI generate video, image and audio from text prompts or strips. 

https://github.com/tin2tin/Generative_AI/assets/1322593/7cd69cd0-5842-40f0-b41f-455c77443535

## Video Examples
### Modelscope & Bark
[![Watch the video](https://img.youtube.com/vi/auHu02KJZQs/0.jpg)](https://youtu.be/auHu02KJZQs) [![Watch the video](https://img.youtube.com/vi/AAdQfQjENJU/0.jpg)](https://youtu.be/AAdQfQjENJU)

## Features
* Text to video
* Text to audio
* Text to image
* Seed, Quality Steps, Frames, Word Power. 
* Batch operation of text strips into videos, audios or images.
* Model card selector
* Render finished notification
* Model Cards: Modelscope, Animov, Stable Diffusion 1.5 & 2, AudioLMD and Bark 

## Requirements
* A CUDA supported Nvidia card with at least 4 GB VRam.

## How to install
(As for Linux and MacOS, if anything differs in installation, then please share instructions.)

* First you must download and install git for your platform(must be on PATH(or Bark will fail)): https://git-scm.com/downloads

* Download the add-on: https://github.com/tin2tin/text_to_video/archive/refs/heads/main.zip

* On Windows, right click on the Blender icon and "Run Blender as Administrator"(or you'll get write permission errors).

* Install the add-on as usual: Preferences > Add-ons > Install > select file > enable the add-on. 

* In the Generative AI add-on preferences, hit the "Install all Dependencies" button.

* Note that you can change what model cards are used in the various modes here(video, image, audio).

* When it writes that it is finished(if any errors, let me know).

* Open the add-on UI in the Sequencedr > Sidebar > Generative AI.

* The first time any model is executed many GB will have to be downloaded, so go grab lots of coffee. 

Install Dependencies, set Movie Model Card and set Sound Notification in the add-on preferences:

![image](https://user-images.githubusercontent.com/1322593/233810577-961de9ec-ce3f-433b-a43c-dd4583fb518c.png)


## Location

Video Sequence Editor > Sidebar > Generative AI

![image](https://user-images.githubusercontent.com/1322593/233038942-ae01ed61-9977-4478-b90a-af8282d6556c.png)
![image](https://user-images.githubusercontent.com/1322593/233155019-05c514a3-d7cc-4f4f-ba9c-7d77f957fd98.png)
![image](https://user-images.githubusercontent.com/1322593/233361486-e8fc96c3-1c3f-4077-af56-98bab66638c3.png)

Converting Text strips into GeneratorAI strips:

![image](https://user-images.githubusercontent.com/1322593/232625894-6726d407-c802-4619-864a-0b8b7faeceff.png)

# Text to Video/Image

The Modelscope model have a watermark, since it's been trained on Shutterstock material, and can't be used for commercial purposes. 
The Animov models have been trained on Anime material, so adding "anime" to the prompt is nessessary for especially the Animov-512x model. 
The Stable Diffusion models for generating images, have been used a lot, so there are plenty of promt suggestions out there if you google for them. 

Tip           |
:------------- |
If the image of your renders breaks, then use the resolution from the Model Card in the Preferences.     |


# Text to Audio

### AudioLDM
Find AudioLDM documentation here: https://github.com/haoheliu/AudioLDM
Try prompts like: Bag pipes playing a funeral dirge, punk rock band playing hardcore song, techno dj playing deep bass house music, and acid house loop with jazz.
Or: Voice of God judging mankind, woman talking about celestial beings, hammer on wood.

### Bark
Find Bark documentation here: https://github.com/suno-ai/bark
* [laughter]
* [laughs]
* [sighs]
* [music]
* [gasps]
* [clears throat]
* — or ... for hesitations
* ♪ for song lyrics
* capitalization for emphasis of a word
* MAN/WOMAN: for bias towards speaker

Speaker Library: https://suno-ai.notion.site/8b8e8749ed514b0cbf3f699013548683?v=bc67cff786b04b50b3ceb756fd05f68c

Tip           |
:------------- |
If the audio breaks up, try processing longer sentences.      |

## Modules
Diffusers: https://github.com/huggingface/diffusers

ModelScope: https://modelscope.cn/models/damo/text-to-video-synthesis/summary

AudioLDM: 

https://huggingface.co/cvssp/audioldm-s-full-v2

https://github.com/haoheliu/AudioLDM

Bark: https://github.com/suno-ai/bark

If some additional python modules are missing, write about it here(so I can add them), and use the Blender PIP add-on to manually install the missing modules:

https://github.com/amb/blender_pip


## Restrictions for using the AI models:

- The models can only be used for non-commercial purposes. The models are meant for research purposes.
- The models was not trained to realistically represent people or events, so using it to generate such content is beyond the model's capabilities.
- It is prohibited to generate content that is demeaning or harmful to people or their environment, culture, religion, etc.
- Prohibited for pornographic, violent and bloody content generation.
- Prohibited for error and false information generation.








