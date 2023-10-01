# Collection of AI Tech

As there are better and better models coming out everyday, I made this list to atleast have a general grasp on it.

This is a concise mostly personal collection of __the best__ AI technologies & researches that I have came accross. This list does not endorse anything or is competing with any other List. It simply wishes to be informative.

Also a lot of the information gathered here was extracted from the Bycloud youtube channel(the G.O.A.T. on this topic). [Definitely check out his YT channel](https://www.youtube.com/@bycloudAI)

<hr style="height:3px;border-width:0;color:gray;background-color:gray">

# Contents

- [Text to Image](#text-to-image)
- [Text to Video](#text-to-video)
- [Text to Music](#text-to-music)
- [Text to Speach](#text-to-speach)
  - [Voice Cloning](#voice-cloning)
- [AI NPCs(Speach to Speach)](#games-with-ai-npcs)
- [Image Restoration](#image-restoration)
- [Generative LLMs](#generative-llms)
- [Code Generation](#code-generation)
- [Humaniod]()
- [Autonomous Vehicles](#Autonomous)
- [Extras]()

---

# Text to Image
There is undisputedly a lot of models and sevices for this type of tech, but in this I try to mention some of the better ones.

- Mid journey
- DALL-E 3
- Stable Diffusion
  - Lora
  - ComfyUI


## midjourney
probably the best service on this topic for now
<details>
  <summary>testing details</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>


#### Dall-E 3

stablity Ai
Stable Diffusion is a deep learning model that was released in 2022 and is primarily used to generate detailed images conditioned on text descriptions. It is based on diffusion techniques and is a text-to-image model. The model learns to generate images by gradually removing noise from a very noisy image, a process called “reverse diffusion”.
[Blog](https://stability.ai/blog/stable-diffusion-sdxl-1-announcement)
[Hugginface](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
[Huggingface(Refiner)](https://huggingface.co/stabilityai/stable-diffusion-xl-refiner-1.0)



Lora 
[Github](https://github.com/cloneofsimo/lora)
[Back to Contents](#contents)

ComfyUI(GUI)
[Github](https://github.com/comfyanonymous/ComfyUI)

### Fooocus
Fooocus is a Stable Diffusion interface that is designed to reduce the complexity of other SD interfaces like ComfyUI, by making the image generation process only require a single prompt. The interface uses a set of default settings that are optimized to give the best results when using SDXL models.

[github](https://github.com/lllyasviel/Fooocus)

---
# Text to Video

CogVideo
[Github](https://github.com/THUDM/CogVideo)



---

# Text to Music

MusicGen



MusicLM
[Paper](https://arxiv.org/abs/2301.11325)
[Project Page] 
[AI Test Kitchen] 
[ByCloud's extra Video on it]   



SoundStream (RVQ origin paper)

[Paper]()




---
# Text to Speach
Again, do check out Bycloud's [channel](https://www.youtube.com/@bycloudAI).



Online Services
[Uberduck](https://uberduck.ai/)
[Fakeyou](https://fakeyou.com/)
[ElevenLabs](https://elevenlabs.io/)

Has Local UI
[RVC]
probably behind the drake song, generally the best one.
[RVC Tutorial]

[Tacotron2]
used for AI spongebob
[Tacotron2 Tutorial]    
[Ultimate Voice Remover 5]
[TorToiSe] 
[TorToiSe Tutorial]   
[so-vits-svc 4.0]
[so-vits-svc 4.0 Tutorial]   
[so-vits-svc 5.0 (NEW)] 

---

# Voice Cloning
---
# Games with AI NPCs

these are games that you have talk to NPCs in order to progress, the AIs consist of a LLM and TTS so they can be very interactive. In both of these games you play as a detective and have to slove the case by talking to NPCs and extracting information from them. NPCs have designate roles and their own back stories which influcences how they will repond to you.

Games:

- [Vaudeville](#vaudeville)
- [Inworld Origins](#inworld-origins)

[Back to Contents](#contents)

<hr style="height:1px;border-width:0;color:gray;background-color:gray">

#### Vaudeville

You play as a detective and have to solve a murder case.

![image](</Images/Game(NPCs)/vaudeville.png>)
[steam](https://store.steampowered.com/app/2240920/Vaudeville/)

[Back to Contents](#contents)

<hr style="height:1px;border-width:0;color:gray;background-color:gray">

#### Inworld Origins

Has been in development more than Vaudeville, you are also a detective in this game, but the story is a quite different.

![image](</Images/Game(NPCs)/origins.jpg>)
[steam](https://store.steampowered.com/app/2199920/Inworld_Origins/)

[Back to Contents](#contents)

---
# Image Restoration
this is tech is about...


<hr style="height:1px;border-width:0;color:gray;background-color:gray">
#### Bringing Old Photos Back to Life
best resoltration, also the back bone of myheritage
Focusing on physcial damage. research done by mircosoft.
![micro](/Images/Image-Restoration/Microsoft.jpg)
[Github](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life)

[Back to Contents](#contents)

<hr style="height:1px;border-width:0;color:gray;background-color:gray">

#### DeOldify
best free colorizer

[Github](https://github.com/jantic/DeOldify)

[Back to Contents](#contents)

<hr style="height:1px;border-width:0;color:gray;background-color:gray">

#### DFDNet

![img1](/Images/Image-Restoration/DFDNet/Title.png)
![image](/Images/Image-Restoration/DFDNet/Screenshot%202023-09-24%20165924.png)
[Github](https://github.com/csxmli2016/DFDNet)

[Back to Contents](#contents)
<hr style="height:1px;border-width:0;color:gray;background-color:gray">

CodeFormer
best free upscaler
[Github](https://github.com/sczhou/CodeFormer)

[Back to Contents](#contents)


<hr style="height:1px;border-width:0;color:gray;background-color:gray">

MyHeritage 
image resotration / upscalers best paid
[website](https://www.myheritage.com)

[Back to Contents](#contents)

<hr style="height:1px;border-width:0;color:gray;background-color:gray">

palette
colorzation, best paid colorzation
[Website](https://palette.fm)

[Back to Contents](#contents)
![Alt text](image-1.png)
[Fotor](https://www.fotor.com/features/background-remover)

---
# Generative LLMs

OpenAi's Chatgpt
undisputed king of this domain, not much else needs to be said. I also didn't put bing chat here since its just a customized version of GPT4.

Claude
[Website](https://claude.ai/login)

---
# Code Generation
Since most popular LLMs fit this role. this can be a bit tough.

- Github Copilot
- Bing Chat


---
# Humaniod


---
# Autonomous Vehicles

Tesla
this [channel](https://www.youtube.com/c/WholeMarsCatalog)




---

# Extras


- [Tips for Temopral stability(stable diffusion)](https://www.reddit.com/r/StableDiffusion/comments/11zeb17/tips_for_temporal_stability_while_changing_the/)