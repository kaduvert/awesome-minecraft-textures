# Awesome Minecraft Textures

**Disclaimer: This is NOT AN OFFICIAL MINECRAFT PRODUCT. It is NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT. All rights to Minecraft names, brands, assets, and textures remain the property of Mojang AB / Mojang Studios, Microsoft and the respective texture pack authors.**

**Important: This guide is for educational and personal use only. The resulting merged resource pack contains copyrighted assets owned by Mojang and the respective texture pack authors. Do not redistribute, sell, or upload the merged pack to the internet.**

<br>

## 1.8.9 on 26.1.2 Texture Pack Guide

makes textures for all 26.X blocks and uses original 1.8.9 assets for all blocks that also existed back then which still exist today

**Are you confused by minecraft's 1.9+ textures and their style? Do you want to make your game feel like minecraft 2015 but keep playing the latest version?**

<ins>follow this guide to at least make it visually look like back then.</ins>

<details>
  <summary>screenshots (also see gallery)</summary>

![broad showcase](https://github.com/user-attachments/assets/7d34d866-5aca-4601-ac63-65da28e8e760)

![F5 screenshot](https://github.com/user-attachments/assets/2a2b2caa-e8ee-42d0-a4b7-7422bf9f8345)
</details>

**NOTE: This guide explicitly targets 26.1.2** but the resulting pack is still very much functional at **26.2 / 26.3**

## 1. prepare some necessary packs:

- **Get / locate your own legal copies of the minecraft 1.8.9 & 26.1.2 client .jars** or your favorite 1.8.9 pack and the 26.1.2 client .jar
  - **Check <a href="https://minecraft.wiki/w/Client.jar" target="_blank">this guide</a>** on where it probably is **once** you **launched** both a vanilla **26.1.2 and** a vanilla **1.8.9** game

  - **<a href="https://kaduvert.github.io/PackPort-1.8.9-to-26.1.2/" target="_blank">use this converter to get 26.1.2-compatible 1.8.9 textures</a>**

<br>

- get <a href="https://modrinth.com/resourcepack/classic-look" target="_blank">"Classic Look" Resource Pack</a> (choose latest available version at download)
  - **<a href="https://kaduvert.github.io/awesome-minecraft-textures" target="_blank">patch it with this tool</a>** (only this pack, not any of the others)

<br>

- get 
<a href="https://modrinth.com/resourcepack/programmer-art-ultimate" target="_blank">"Programmer Art Ultimate"</a> (choose latest available version at download)

- get <a href="https://modrinth.com/resourcepack/programmer-art-fix" target="_blank">"Programmer Art Fix"</a> (choose version 26.1.2 at download)

## 2. put all the packs into an online resource pack merger in this order:

**Just google "Minecraft Resource Pack Merger" and choose the one that supports uploading multiple and ordering them** <a href="https://www.phoenixplugins.com/tools/resource-pack-merger" target="_blank">like this one</a>

**Put the exact packs exactly in this order:**

(top to bottom)

#1 1.8.9 textures (**<a href="https://kaduvert.github.io/PackPort-1.8.9-to-26.1.2/" target="_blank">converted</a> as outlined above to** be **26.1.2** compatible)<br>
#2 **Patched** <a href="https://modrinth.com/resourcepack/classic-look" target="_blank">Classic Look</a> (patched with <a href="https://kaduvert.github.io/awesome-minecraft-textures" target="_blank">the above tool</a>)<br>
#3 <a href="https://modrinth.com/resourcepack/programmer-art-ultimate" target="_blank">Programmer Art Ultimate</a><br>
#4 <a href="https://modrinth.com/resourcepack/programmer-art-fix" target="_blank">Programmer Art Fix</a><br>

<img width="882" height="746" alt="resource pack merge order screen" src="https://github.com/user-attachments/assets/aedb897c-9e08-42f8-8965-a1e43edfba9f" />


_Note that PA Ultimate and Classic Look as of right now don't actually have a 26.1.2 release, so you're merging incompatible packs. Ideally you'd use an <a href="https://convertmcpack.net/" target="_blank">generic online texture pack updater like this one</a> for these 2 packs, but i didn't see any difference. The game looks completely fine even if you don't do this. I didn't either._

<br>

**Download the resulting pack and rename it to "Minecraft 1.8.9" or whatever (as said, for your local reference only, do not distribute this pack)**

## 3. Done

If you did it right your **pack should be ~38.9MB big** and look and feel like a heavily modded Minecraft 1.8.9

ingame you just have to **load the pack, but also make sure you** also **load** the built-in programmer art below it, so **your resource packs** are **ordered like this**:

#1 "Minecraft 1.8.9" or whatever you named it<br>
#2 Programmer Art (built-in)<br>
#3 Default Textures (built-in)<br>

<img width="881" height="388" alt="resource pack order" src="https://github.com/user-attachments/assets/7c53ebe6-d215-4468-9cd8-fa90d7281818"/>

<br>

<br>

### Footnote:

**Lots of other things changed since 1.8.9 but they can't be reverted without breaking compatibility with servers and other clients.**
this is because we're talking about

- **hit cooldown** (this can be **solved through datapack but only locally** or with compatible servers) and
- **physics changes** (**currently no mod out there** i think **that reverts to 1.8.9 physics**)

However **a texture pack is 80% the way there in terms of look and feel** so i guess **this is fine if you're usually a 1.8.9 player but want to play latest version without getting confused by all the changed textures**

If you did it right your pack should be ~38.9MB big and look and feel like a heavily modded Minecraft 1.8.9
