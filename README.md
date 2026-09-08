# Awesome Minecraft Textures

<br>

**Disclaimer: This is NOT AN OFFICIAL MINECRAFT PRODUCT. It is NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT. All rights to Minecraft names, brands, assets, and textures remain the property of Mojang AB / Mojang Studios, Microsoft and the respective texture pack authors.**

**Important: This guide is for educational and personal use only. The resulting merged resource pack contains copyrighted assets owned by Mojang and the respective texture pack authors. Do not redistribute, sell, or upload the merged pack to the internet.**

<br>

<img width="1920" height="1080" alt="2026-09-08_01 03 02" src="https://github.com/user-attachments/assets/2a2b2caa-e8ee-42d0-a4b7-7422bf9f8345" />

<br>

## Are you confused by minecraft's 1.9+ textures and their style? Do you want to make your game feel like minecraft 2015 but keep playing the latest version?

follow this guide to at least make it visually look like back then.

**NOTE: This guide explicitly targets 26.1.2**

## 1. prepare some necessary packs:

- **Get 1.8.9 default textures** by extracting them directly from your own legally purchased copy of Minecraft 1.8.9.
  - **Do not download a '1.8.9 texture pack template' from an unverified third-party website found on Google** or similar, as these sites are redistributing copyrighted assets which violates Mojang's Usage Guidelines and Copyright. **This is very important! Do not just download them from Online Resource Pack Websites**, go through the legal, proper way of extracting the textures from your own minecraft 1.8.9 jar. **Extremely important that you do exactly this and don't just download redistributed assets.**

  - **[convert it to 26.1.2 with this converter](https://kaduvert.github.io/PackPort-1.8.9-to-26.1.2/)**
    - Note that you also need a 26.1.2 reference pack for this to work. Same game, extract it from your own legal copy of Minecraft, do not download random resource pack templates that hold all the assets
<br>

- get ["Classic Look" Resource Pack](https://modrinth.com/resourcepack/classic-look) (choose latest available version at download)
  - **[patch it with this tool](https://kaduvert.github.io/awesome-minecraft-textures)** (only this pack, not any of the others)
<br>

- get ["Programmer Art Ultimate"](https://modrinth.com/resourcepack/programmer-art-ultimate) (choose latest available version at download)

- get ["Programmer Art Fix"](https://modrinth.com/resourcepack/programmer-art-fix) (choose version 26.1.2 at download)

## 2. put all the packs into an online resource pack merger in this order:

**Just google "Minecraft Resource Pack Merger" and choose the one that supports uploading multiple and ordering them** [like this one](https://www.phoenixplugins.com/tools/resource-pack-merger)

**Put the exact packs exactly in this order:**

(top to bottom)

#1 1.8.9 textures (**converted as outlined above to** be **26.1.2** compatible)<br>
#2 **Patched** [Classic Look](https://modrinth.com/resourcepack/classic-look) (patched with [the above tool](https://kaduvert.github.io/awesome-minecraft-textures))<br>
#3 [Programmer Art Ultimate](https://modrinth.com/resourcepack/programmer-art-ultimate)<br>
#4 [Programmer Art Fix](https://modrinth.com/resourcepack/programmer-art-fix)<br>

<img width="882" height="746" alt="screenshot-03d23773" src="https://github.com/user-attachments/assets/aedb897c-9e08-42f8-8965-a1e43edfba9f" />


_Note that PA Ultimate and PA Fix as of right now don't actually have a 26.1.2 release, so you're merging incompatible packs. I didn't convert prior either though, so it's fine.
It doesn't matter if you pre-convert them in some online converter first, it's not worth the effort. I didn't do this either._

<br>

**Download the resulting pack and rename it to "Minecraft 1.8.9" or whatever (as said, for your local reference only, do not distribute this pack)**

## 3. Done

ingame you just have to **load the pack, but also make sure you** also **load** the built-in programmer art below it, so **your resource packs** are **ordered like this**:

#1 "Minecraft 1.8.9" or whatever you named it<br>
#2 Programmer Art (built-in)<br>
#3 Default Textures (built-in)<br>

<img width="881" height="388" alt="2026-09-08_01 34 29" src="https://github.com/user-attachments/assets/7c53ebe6-d215-4468-9cd8-fa90d7281818" />


#### Footnote:

**Lots of other things changed since 1.8.9 but they can't be reverted without breaking compatibility with servers and other clients.**
this is because we're talking about

- **hit cooldown** (this can be **solved through datapack but only locally** or with compatible servers) and
- **physics changes** (**currently no mod out there** i think **that reverts to 1.8.9 physics**)

However **a texture pack is 80% the way there in terms of look and feel** so i guess **this is fine if you're usually a 1.8.9 player but want to play latest version without getting confused by all the changed textures**

If you did it right your pack should be ~38.9MB big and look and feel like a heavily modded Minecraft 1.8.9
