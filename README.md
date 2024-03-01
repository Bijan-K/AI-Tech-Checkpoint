*this is still a draft and there is still a lot I have yet to add*

# Collection of AI Tech

As there are better and better models coming out everyday, I made this list to atleast have a general grasp on it. This list,also, will always be outdated. :thumbsup:

This is a concise mostly personal collection of __the best__ AI technologies & researches that I have came accross, which probably isn't much. 

Disclaimer:
This list does not endorse anything or is competing with any other List. It simply wishes to be informative(for myself mostly). Also a lot of the information gathered here was extracted from the Bycloud youtube channel(the G.O.A.T. on this topic). [Definitely check out his YT channel](https://www.youtube.com/@bycloudAI). 


---

# Contents

- [Text to Image](#text-to-image)
- [Text to Video](#text-to-video)
- [Text to Music](#text-to-music)
- [3D Image(NeRF + others)](#3d-images)
- [Text to "4D"](#text-to-4d)
- [Voice Cloning](#voice-cloning)
- [Background Removal](#background-removal)
- [Deep Fake](#deep-fake)
- [AI NPCs(Speach to Speach)](#games-with-ai-npcs)
- [Image Restoration](#image-restoration)
- [Generative LLMs](#generative-llms)
- [Code Generation](#code-generation)
- [Humaniod](#humaniod)
- [Autonomous Vehicles](/Directories/Autonomous-Vehicles/README.md)
- [Extras](#extras)

---




--- 
<!-- New Topic -->
# Text to Video
There are quite a few approaches to this, but they can be categorised to 3 segements for now.

[Pure text to Video](#pure-text-to-video):
- [runaway gen-2](#runaway-gen-2)
- [Pika labs](#pika-labs)
- [Zeroscope v2](#zeroscope-v2)
- [animatediff](#animatediff)

[img2img](#img2img):
- [Ebsynth](#ebsynth)
- [TemporalNet](#temporalnet2)
- [CoDeF](#codef)
- [TokenFlow](#tokenflow)
- [Warp Diffusion](#warp-diffusion)
- [DeForum](#deforum)

[Media Manipluation](#media-manipulation):

- [SimSw ap](#simswap)
- [Face Fusion](#face-fusion)
- [DaGAN](#depth-aware-generative-adversarial-network)
- [SadTalker](#sadtalker)
- [HeyGen](#heygen)

[Back to Contents](#contents)

# Pure Text to Video
## Runaway gen-2
- [Website](https://app.runwayml.com/login)
## Pika labs
- [Website](https://www.pika.art)
## Zeroscope v2
- [HuggingFace](https://huggingface.co/spaces/hysts/zeroscope-v2)

## animatediff
- [Page](https://animatediff.github.io)

[Back to Contents](#contents)


---
# img2img

## Gen 1
- [Page](https://research.runwayml.com/gen1)


## ebsynth
ideal for low frame rate videos
- [Website](https://ebsynth.com)

## TemporalNet2
- [HuggingFace](https://huggingface.co/CiaraRowles/TemporalNet2)
- [Reddit Guide](https://www.reddit.com/r/StableDiffusion/comments/11zeb17/tips_for_temporal_stability_while_changing_the/)

## CoDeF
- [Page](https://qiuyu96.github.io/CoDeF/)

## Tokenflow
not open source so who knows, if it is actually this  good.
[Page](https://diffusion-tokenflow.github.io)

## Warp Diffusion
Closed source and not free. The results aren't bad tho.
- [You have to pay someone like this guy](https://www.patreon.com/sxela)

## Deforum
- [Page](https://deforum.github.io/)

[Back to Contents](#contents)


---
# Media Manipulation
Things like deepfakes - face animations - face swaps. They are used to edit specific parts of the video.
## SimSwap
- [Github](https://github.com/neuralchen/SimSwap)

## Face Fusion
made by one of the creators of [roop](https://github.com/s0md3v/roop)
- [Github](https://github.com/facefusion/facefusion)

## SadTalker
- [Github](https://github.com/OpenTalker/SadTalker#generating-3d-face-from-audio)

## HeyGen
- [Website](https://www.heygen.com)

[Back to Contents](#contents)


---

# Text to Music

- [MusicGen](#musicgen)
- [MusicLM](#musiclm)
- [SoundStream](#soundstream)

[Back to Contents](#contents)
 

## MusicGen
![musicgen](/Images/Text-to-Music/MusicGen/MusicGen.png)

- [paper](https://arxiv.org/abs/2306.05284)
- [Page](https://ai.honu.io/papers/musicgen/)
- [Github](https://github.com/facebookresearch/audiocraft)
- [HuggingFace](https://huggingface.co/spaces/facebook/MusicGen)
- [Colabs](https://github.com/camenduru/MusicGen-colab)

[Back to Contents](#contents)

## MusicLM
![MusicLM](/Images/Text-to-Music/MusicLM/MusicLM.png)

- [Paper](https://arxiv.org/abs/2301.11325)
- [Project Page](https://google-research.github.io/seanet/musiclm/examples/)
- [AI Test Kitchen](https://aitestkitchen.withgoogle.com/experiments/music-lm)
- [ByCloud's extra Video on it](https://www.youtube.com/watch?v=2CUKU2iAzAs) 


[Back to Contents](#contents)

## SoundStream 
RVQ origin paper

- [Paper](https://arxiv.org/pdf/2107.03312.pdf)
- [Website](https://blog.research.google/2021/08/soundstream-end-to-end-neural-audio.html)
- [Github](https://github.com/wesbz/SoundStream)

[Back to Contents](#contents)

---
# 3D Images
- [NeRF](#nerf)
  - [LeRF](#lerf)
  - [MixNeRF](#mixnerf)
  - [F2-NeRF](#f2-nerf)
  - [BungeeNeRF](#bungeenerf)
  - [GridNeRF](#gridnerf)
  - [NSFF](#nsff)
  - [ReLight My NeRF](#relight-my-nerf)
  - [MSNeRF](#msnerf)
  - [DyNeRF](#dynerf)
  - [NeRFPlayer](#nerfplayer)
- [NeRF-SR](#nerf-sr)
- [DreamFusion](#dreamfusion)
- [ProlificDreamer]()
- [Neuralangelo](#neuralangelo)
- [Luma Labs AI](#luma-labs-ai)
- [InstructPix2Pix](#instructpix2pix)
- [3D Video Loops from Asynchronous Input](#3d-video-loops-from-asynchronous-input)

## NeRF
stands for: Representing Scenes as Neural Radiance Fields for View Synthesis. Simply put, uses multiplue images to construct a scene that can be view from multipule angles.
- [Website](https://www.matthewtancik.com/nerf)
- [Github](https://github.com/bmild/nerf)
- [Paper](https://arxiv.org/abs/2003.08934)

## LeRF
- [Paper](https://arxiv.org/abs/2303.09553)
- [Page](https://www.lerf.io)
- [Github](https://github.com/kerrj/lerf)
- [NeRF Studio](https://docs.nerf.studio)

## MixNeRF
- [Paper](https://arxiv.org/abs/2302.08788)
- [Page](https://shawn615.github.io/mixnerf/)
- [Github](https://github.com/shawn615/MixNeRF)


## F2-NeRF
- [Paper](https://arxiv.org/abs/2303.15951)
- [Github](https://github.com/totoro97/f2-nerf)

## BungeeNeRF
- [Paper](https://arxiv.org/abs/2112.05504)
- [Page](https://city-super.github.io/citynerf/)
- [Github](https://github.com/city-super/BungeeNeRF)

## GridNeRF
- [Paper](https://arxiv.org/abs/2303.14001)
- [Page](https://city-super.github.io/gridnerf/)

## NSFF
- [Paper](https://arxiv.org/abs/2303.14001)
- [Page](https://city-super.github.io/gridnerf/)

## ReLight My NeRF
- [Paper](https://arxiv.org/abs/2304.10448)
- [Page](https://eyecan-ai.github.io/rene/)

## MSNeRF
- [Paper](https://arxiv.org/abs/2305.04268)
- [Page](https://zx-yin.github.io/msnerf/)
- [Github](https://github.com/ZX-Yin/ms-nerf)

## DyNeRF
- [Paper](https://arxiv.org/abs/2103.02597)
- [Page](https://neural-3d-video.github.io)

## NeRFPlayer
- [Paper](https://arxiv.org/pdf/2210.15947.pdf)
- [Page](https://lsongx.github.io/projects/nerfplayer.html)

## NeRF-SR
- [Github](https://github.com/cwchenwang/NeRF-SR)

## DreamFusion
Text-to-3D using 2D Diffusion
- [Website](https://dreamfusion3d.github.io)
- [Paper](https://arxiv.org/abs/2209.14988)

## Neuralangelo
- [Paper](https://research.nvidia.com/labs/dir/neuralangelo/paper.pdf)
- [Page](https://research.nvidia.com/labs/dir/neuralangelo/)

## Luma Labs AI
- [Website](https://lumalabs.ai)
- [App](https://apps.apple.com/in/app/luma-ai/id1615849914) 

## InstructPix2Pix
- [Paper](https://arxiv.org/abs/2211.09800)
- [Page](https://www.timothybrooks.com/instruct-pix2pix/)
- [Github](github.com/timothybrooks/instruct-pix2pix)

## 3D Video Loops from Asynchronous Input
- [Paper](https://arxiv.org/abs/2303.05312)
- [Page](https://limacv.github.io/VideoLoop3D_web/)
- [Github](https://github.com/limacv/VideoLoop3D)

---

# Text to 4D

## Text-To-4D Dynamic Scene Generation
Since they were the first to do this, they named it "4D". it's basically text to video but also quite different. You could think of the forth dimension as time, I guess.

- [Website](https://make-a-video3d.github.io)
- [Paper](https://arxiv.org/abs/2301.11280)

[Back to Contents](#contents)

---

# Voice Cloning

<!-- should change later -->
Online Services(links):
- [Uberduck](https://uberduck.ai/)
- [Fakeyou](https://fakeyou.com/)
- [ElevenLabs](https://elevenlabs.io/)(pretty good)

Local:
- [RVC](#rvc)
- [Tacotron2](#tacotron2)
- [so-vits-svc](#so-vits-svc)
- [TortoiSe](#tortoise)
TortoiSe + RVC is the best


## RVC
Stands for Retrieval based Voice Conversion.This is probably behind the drake song, generally the best one. 
- [Github](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)
- [Tutorial](https://www.youtube.com/watch?v=hB7zFyP99CY)

## TorToiSe
- [Ecker.tech](https://git.ecker.tech/mrq/ai-voice-cloning) 
- [Tutorial](https://www.youtube.com/watch?v=6sTsqSQYIzs)


## so-vits-svc
Stands for SoftVC VITS singing voice Conversion.

- [so-vits-svc 4.0](https://github.com/voicepaw/so-vits-svc-fork)
- [so-vits-svc 4.0 Tutorial](https://www.youtube.com/watch?v=tZn0lcGO5OQ)   
- [so-vits-svc 5.0 (NEW)](https://github.com/PlayVoice/whisper-vits-svc)

## Tacotron2
Most likely used for AI spongebob videos.

- [Github](https://github.com/BenAAndrew/Voice-Cloning-App)
- [Tutorial](https://youtube.com/playlist?list=PLk5I7EvFL13GjBIDorh5yE1SaPGRG-i2l&si=yqEWu-rZM0EWGfyv) 

---



# Deep Fake
This continuation of [Media Manipluation](#media-manipulation)


#### First Order Motion Model
Image Animation
- [Paper](https://proceedings.neurips.cc/paper/2019/hash/31c0b36aef265d9221af80872ceb62f9-Abstract.html)
- [Github](https://github.com/AliaksandrSiarohin/first-order-model)
- [Website](https://aliaksandrsiarohin.github.io/first-order-model-website/)

[Back to Contents](#contents)


#### Thin-Plate Spline Motion Model
Image Animation
- [Paper](https://arxiv.org/abs/2203.14367)
- [Code](https://github.com/yoyo-nb/Thin-Plate-Spline-Motion-Model)

[Back to Contents](#contents)

#### Depth-Aware Generative Adversarial Network
Talking Head Video Generation
- [Website](https://harlanhong.github.io/publications/dagan.html)
- [Paper](https://arxiv.org/abs/2203.06605)
- [Github](https://github.com/harlanhong/CVPR2022-DaGAN)
- [Online Demo](https://huggingface.co/spaces/HarlanHong/DaGAN)

[Back to Contents](#contents)

#### MegaPortraits: One-shot Megapixel Neural Head Avatars
closed source
- [Paper](https://arxiv.org/abs/2207.07621)
- [Website?(Github)](https://github.com/neeek2303/MegaPortraits)

[Back to Contents](#contents)

---
# Background Removal

## Robust Video Matting (RVM)

- [Website](https://peterl1n.github.io/RobustVideoMatting/#/)
- [Github](https://github.com/PeterL1n/RobustVideoMatting)
- [Paper](https://arxiv.org/abs/2108.11515)


## BackgroundMattingV2 (BGMv2)
- [Website](https://grail.cs.washington.edu/projects/background-matting-v2/#/)
- [Github](https://github.com/PeterL1n/BackgroundMattingV2)
- [Paper](https://arxiv.org/abs/2012.07810)

[Back to Contents](#contents)

---
# Games with AI NPCs

these are games that you have talk to NPCs in order to progress, the AIs consist of a LLM and TTS so they can be very interactive. In both of these games you play as a detective and have to slove the case by talking to NPCs and extracting information from them. NPCs have designate roles and their own back stories which influcences how they will repond to you.

[Back to Contents](#contents)

Games:

- [Vaudeville](#vaudeville)
- [Inworld Origins](#inworld-origins)




## Vaudeville

You play as a detective and have to solve a murder case.

![image](</Images/Game(NPCs)/vaudeville.png>)

- [steam](https://store.steampowered.com/app/2240920/Vaudeville/)

[Back to Contents](#contents)

<hr style="height:1px;border-width:0;color:gray;background-color:gray">

## Inworld Origins

Has been in development more than Vaudeville, you are also a detective in this game, but the story is a quite different.

![image](</Images/Game(NPCs)/origins.jpg>)

- [steam](https://store.steampowered.com/app/2199920/Inworld_Origins/)

[Back to Contents](#contents)


# Image Restoration
Models for upscaling, adding color and reparing images

- [Bringing old photos back to life](#bringing-old-photos-back-to-life)
- [DeOldify](#deoldify)
- [DFDNet](#dfdnet)
- [CodeFormer](#codeformer)
- [MyHeritage](#myheritage)
- [Palette](#palette)


<hr style="height:1px;border-width:0;color:gray;background-color:gray">

## Bringing Old Photos Back to Life

Best resoltration, also the back bone of myheritage, focuses on physcial damage. research done by mircosoft.

![microsoft](/Images/Image-Restoration/Microsoft.jpg)

- [Github](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life)

[Back to Contents](#contents)

<hr style="height:1px;border-width:0;color:gray;background-color:gray">

## DeOldify
best free colorizer

- [Github](https://github.com/jantic/DeOldify)

[Back to Contents](#contents)

<hr style="height:1px;border-width:0;color:gray;background-color:gray">

## DFDNet

![img1](/Images/Image-Restoration/DFDNet/Title.png)
![image](/Images/Image-Restoration/DFDNet/Screenshot%202023-09-24%20165924.png)

- [Github](https://github.com/csxmli2016/DFDNet)

[Back to Contents](#contents)


<hr style="height:1px;border-width:0;color:gray;background-color:gray">

## CodeFormer
best free upscaler

- [Github](https://github.com/sczhou/CodeFormer)

[Back to Contents](#contents)


<hr style="height:1px;border-width:0;color:gray;background-color:gray">

## MyHeritage 
image resotration / upscalers best paid

- [website](https://www.myheritage.com)

[Back to Contents](#contents)

<hr style="height:1px;border-width:0;color:gray;background-color:gray">

## Palette
colorzation, best paid colorzation

- [Website](https://palette.fm)

[Back to Contents](#contents)

---
# Generative LLMs



## Chat GPT(4 - MultiModal)
undisputed king of this domain, not much else needs to be said.
- [Website](https://chat.openai.com/auth/login)
## LLama 2
- [Website](https://ai.meta.com/llama/)
## Claude
- [Website](https://claude.ai/login)

[Back to Contents](#contents)

---
# Code Generation
Since most popular LLMs fit this role. this can be a bit tough.

- Github Copilot
- Chatgpt's GPT-4
- Bing Chat(Kinda)
- Code Llama2
- Phind


Phind
[Website](https://www.phind.com)


---
# Humaniod
Boston dynamics
Tesla
Hanson robotics
Ubtech robotics

I'll put links to Clips of them later on.

---



---

# Extras


- [Tips for Temopral stability(stable diffusion)](https://www.reddit.com/r/StableDiffusion/comments/11zeb17/tips_for_temporal_stability_while_changing_the/)
- [Ultimate Voice Remover 5](https://github.com/Anjok07/ultimatevocalremovergui)
