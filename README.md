# Texture-Pack-Template
Minecraft LCE **template** and a detailed **guide** for texture-pack making.

In this **README.md** you'll find:
- A **Manual** (detailed guide) method
- An **automatic** method
- A video tutorial

The icon of the pack is the default one and the name/decription are be blank (idk why, plz help)

---

# Documentation
`.pck` is the primary file extension you will find  
`.arc` is the file extension for GUI related things  
`.swf` is what you find when extracting `.pck` files

---

# Needed tools

- https://github.com/LCERD/PCK-Studio to edit `.pck` files  
- https://github.com/PhoenixARC/MUArchiveEditor to edit `.arc` files  
- https://github.com/jindrapetrik/jpexs-decompiler to edit/extract `.swf` files  
You can use any image editor

Feel free to use `https://www.virustotal.com/gui/home/upload` if you want to scan those tools.  
If you don't want to use the provided tools, you can search other ones, there are plenty out there :)

---

# **Manual** Method

Before **any** customisation, you need to extract `Texture-pack.Template.v4.zip`.  

## For items/blocks

We'll look at `x16Data.pck` inside the `Data` folder.

Then you need to launch **PCK Studio**.
- When you first execute PCK Studio, you may have a screen telling you that "Windows protected you computer".  
  Don't worry, the program just isn't signed since it cost money.

You need to open the file with drag and drop or by locating in in the "File" section.  
You should now be seeing this

<img width="1057" height="707" alt="image" src="https://github.com/user-attachments/assets/e87e49ec-a151-45d4-a419-0965e976a1ca" />

### Modifying item textures

You first need to right-click `item.png` and then extact it to any location on your computer.  
I recommend to delete it now.  
Open it and as you can see, all of the items are arranged in a specific way, they all are in a 16x16 box.  
You can edit one item directly or you can paste a texture you got from another pack, just make sure you are moving it to the corresponding item 16x16 box.  
You can edit as much item as you want.  
You now have to put it in the exact same location as it was before, you can drag and drop.  

### Modifying block textures

You first need to right-click `terrain.png` and then extact it to any location on your computer. 
I recommend to delete it now.  
Open it and as you can see, all of the blocks are arranged in a specific way, they all are in 16x16 resolution.  
You can edit one block directly or you can paste a texture you got from another pack, just make sure you are moving it to the exact same block.  
You can edit as much item as you want.  
You now have to put it in the exact same location as it was before, you can drag and drop.  

## For GUIs

We'll look at `media.arc` inside the `Data` folder.  
You need to extact it with the program of your choice, for me it is **MUArchiveEditor**


---

## Tutorial

[https://youtu.be/gxs1tqKz9Mo](https://youtu.be/gxs1tqKz9Mo) (the links in the description are outdated)

---

## **Automatic** Method
PLEASE READ THE MANUAL GUIDE BEFORE

The tool is buggy, you may need to finish the work yourself  
https://github.com/ASAOddball1/Java-to-MLCE-Texture-Pack-Converter
