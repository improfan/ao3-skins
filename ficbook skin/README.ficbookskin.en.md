# Ficbook skin

This skin was inspired by [Ficbook](https://ficbook.net/)

Skin consists of 3 (three) css files, so you have to create skin for each. Here I'll describe you how to combine them so they work as one skin.

First of all I must say that icons for this skin I took from here: [Replace the AO3 icons and default images [Site skin]](https://archiveofourown.gay/works/54831748). Do not be lazy and leave kudos for that work! Default icons stand out too much, and those icons with muted colors fit perfectlly. Maybe I'll make my own later.

So 3 (tree) skins need to be made: 

- ficbook skin - main
- ficbook skin - icons
- ficbook skin - mobile

> [!NOTE]
> Remembrer that titles must be unique!

## 1. Main

1. Let's use Wizard ("Use Wizard" button) to configure colors (Header Color and Accent Color). Click Submit (or Update, if you've already made the skin before).

| Header Color | Accent Color |
| :----------: | :----------: |
| #442302      | #ead6b5 |

2. Cliack Edit, to paste our custom css. Copy css from file [ficbook skin - main](/ficbook%20skin/ficbook%20skin%20-%20main.css), paste in css field and click Update.

## 2. Icons

Copy css from file [ficbook skin - icons](/ficbook%20skin/ficbook%20skin%20-%20icons.css), paste in css field and click Submit (or Update, if you've already made the skin before).

## 3. Mobile

1. Copy css from file [ficbook skin - mobile](/ficbook%20skin/ficbook%20skin%20-%20mobile.css), paste in css field. 
2. Open Advanced section and check the following variant in Media field: only screen and (max-width: 42em)
![mobile](/images/advanced-section.png)
3. In Parent Skins section click Add Parent Skin and begin to type the title of your [Main](#1-main) skin, choose it from the list.
4. Repeat third step for [Icons](#2-icons) skin.
4. Click Submit (or Update, if you've already made the skin before).

![mobile skin](/images/mobile-skin.png)

Click Use on Mobile skin and it's done!

![skin showcase](/images/skin-showcase-1.png)
![skin showcase](/images/skin-showcase-2.png)