# Texture-Pack-Template
Minecraft LCE **template** and a detailed **guide** for texture-pack making.
This template was made by CheapManga and Gamer99

In this **README.md** you'll find:

- Documentation
- A list of the needed tools
- A **Manual** method (detailed guide) 
  - Modifying item textures 
  - Modifying block textures
  - Modifying GUIs
  - Modifying name/description (.loc file) 
  - Modifying icon/banner/preview
  - A tutorial
- An **automatic** method

<img width="2487" height="1205" alt="image" src="https://github.com/user-attachments/assets/903d83e5-d2be-414a-acf1-20cda2a8f89d" />


---

# Documentation
`.pck` is the primary file extension you will find  
`.arc` is the file extension for GUI related things  
`.swf` is what you find when extracting `.pck` files

---

# Needed tools

- [PCK Studio](https://github.com/LCERD/PCK-Studio) to edit `.pck` files  
- [MUArchiveEditor](https://github.com/PhoenixARC/MUArchiveEditor) to edit `.arc` files  
- [jpexs-decompiler](https://github.com/jindrapetrik/jpexs-decompiler) to edit/extract `.swf` files  
You can use any image editor
You can use any hex edito (for .loc files customization)

Feel free to use **[Virustotal](https://www.virustotal.com/gui/home/upload)** if you want to scan those tools.  
If you don't want to use the provided tools, you can search other ones, there are plenty out there :)

There is a tool that lets you do all the actions of the said tools, but in one place.
It is still in developement.
https://github.com/TNTaddicted/MCLCE-Texture-Pack-Editor

---

# **Manual** Method

Before **any** customisation, you need to:
- download/extract `Texture-pack.Template.v5.zip`.
- download/extract `PCK Studio`.

When you first execute **PCK Studio**, you may have a screen telling you that "Windows protected you computer".  
Don't worry, the program just isn't signed since it cost money.


# For items/blocks

We'll look at `x16Data.pck` inside the `Data` folder.

You need to open the file with drag and drop or by locating in in the "File" section.  
You should now be seeing this

<img width="1057" height="707" alt="image" src="https://github.com/user-attachments/assets/e87e49ec-a151-45d4-a419-0965e976a1ca" />


## Modifying item textures

You first need to right-click `item.png` and then extact it to any location on your computer.  
I recommend to delete it now.  
Open it and as you can see, all of the items are arranged in a specific way, they all are in a 16x16 box.  
You can edit one item directly or you can paste a texture you got from another pack, just make sure you are moving it to the corresponding item 16x16 box.  
You can edit as much item as you want.  
You now have to put it in the exact same location as it was before, you can drag and drop.  
When you are finished modifying, save as and replace the old `x16Data.pck` with the new one.  
If you finished your texture pack, the folder goes in `"LCEWindows64\Windows64Media\DLC"`. You can now start your game and select your pack in the apropriate section when joining/creating a world.


## Modifying block textures

You first need to right-click `terrain.png` and then extact it to any location on your computer. 
I recommend to delete it now.  
Open it and as you can see, all of the blocks are arranged in a specific way, they all are in 16x16 resolution.  
You can edit one block directly or you can paste a texture you got from another pack, just make sure you are moving it to the exact same block.  
You can edit as much item as you want.  
You now have to put it in the exact same location as it was before, you can drag and drop.  
When you are finished modifying, save as and replace the old `x16Data.pck` with the new one.  
If you finished your texture pack, the folder goes in `"LCEWindows64\Windows64Media\DLC"`. You can now start your game and select your pack in the apropriate section when joining/creating a world.

## Modifying GUIs

We'll look at `media.arc` inside the `Data` folder.  
You need to extact it with the program of your choice, for me it is **MUArchiveEditor**.  
Extract all the files, and edit them in your `.swf` file editor.  
Then repack it, save as and replace it in the same location.  
If you finished your texture pack, the folder goes in `"LCEWindows64\Windows64Media\DLC"`. You can now start your game and select your pack in the apropriate section when joining/creating a world.  

If you can't figure out how to repack .arc files, here's a screenshot on how:  
<img width="628" height="549" alt="image" src="https://github.com/user-attachments/assets/c6924bca-6787-42ce-b1e1-aa68892f40f1" />


## Modifying name/description (.loc file)

We'll look at `TexturePack.pck`.  
You'll need to edit the languages.loc file with a hex-editor.  
PS: It's a pain

Here is a tutorial, **https://youtu.be/CoDBGkWRDbM**  
It seems easy because Gamer99 already done it two or three times.  
Start by editing the Display Name first, it's easier.  
MAKE A BACKUP OF YOUR `languages.loc` BEFORE EDITING IT  

<img width="1336" height="344" alt="image" src="https://github.com/user-attachments/assets/696b6e57-4ad2-4dad-b45a-e1bf85a70214" />

If you finished your texture pack, the folder goes in `"LCEWindows64\Windows64Media\DLC"`. You can now start your game and select your pack in the apropriate section when joining/creating a world.

## Modifying icon/banner/preview
We'll look at `x16Info.pck` in `TexturePack.pck`.  

<img width="1061" height="708" alt="image" src="https://github.com/user-attachments/assets/06210903-cbf8-4756-bd0d-54177a7eb81f" />  
You first need to right-click it and then extact it to any location on your computer.  
Open it in PCK Studio.  
And start modifying! (Your images need to be at the correct size)
When you are finished modifying, save as and replace the old `x16Data.pck` with the new one inside `TexturePack.pck`.  
Then save as and replace the old `TexturePack.pck` with the new one.  
If you finished your texture pack, the folder goes in `"LCEWindows64\Windows64Media\DLC"`. You can now start your game and select your pack in the apropriate section when joining/creating a world.

---

## Tutorial

[https://youtu.be/gxs1tqKz9Mo](https://youtu.be/gxs1tqKz9Mo) (the links in the description are outdated)

---

## **Automatic** Method
PLEASE READ THE MANUAL GUIDE BEFORE

The tool is buggy, you may need to finish the work yourself  
https://github.com/ASAOddball1/Java-to-MLCE-Texture-Pack-Converter
