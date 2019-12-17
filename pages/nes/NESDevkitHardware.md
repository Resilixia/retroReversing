---
layout: post
tags: 
- nes
- devkit
- hardware
title: NES (Famicom) Development Kit Hardware
thumbnail: /public/consoles/Nintendo Entertainment System.png
image: /public/consoles/Nintendo Entertainment System.png
permalink: /official-nes-devkit/
breadcrumbs:
  - name: Home
    url: /
  - name: Nintendo Entertainment System
    url: /nes
  - name: NES (Famicom) Development Kit Hardware
    url: #
recommend: nes
editlink: /nes/NESDevkitHardware.md
---

The Nintendo Famicom was released in Japan on 15th July, 1983 at a price of 14,800 yen. It was one of the first consoles on the market that used the 6502 processor and so not many developers has experience creating games for it. As such most of the games initially released for the platform were made by Nintendo itself, presumably on prototype NES hardware.

Since Nintendo were very new to the video game market and saw themselves as creating most of the software that will run on the NES they did not make a specific development kit, or if they did it was very well hidden in the official Nintendo headquarters and no public information has been released on it.

It wasn't until the first 3rd party game was in development that the need for a Development Kit for the NES was established.

It is likely that developers who managed to get an official license from Nintendo were given some basic documentation about the hardware such as the memory map, PPU and APU. It would then be up to the developer to create their own development environment [^3].

# Official Nintendo development kit
Nintendo has been very secretive about how their official NES games were developed but there is some information coming from a Japanese childrens book of all places and kindly translated by Chris Mcovell on his website.

## Programming Hardware

---
## Famicom Disk System Development hardware
The Famicom Disk System (FDS) was just a cheaper way of distributing games for the Famicom in Japan due to the higher cost of producing cartridges.

It was released in Japan only on the 21st of February 21 1986, 3 years later than the Famicom but the same year as the European NES release. 

It seems to have been commonly been used for development of NES games even if they ended up on cartridges for western audiences.

### FDT ICE  (ISD)
<section class="postSection">
    <img src="/public/images/nes/IntelligentSystems-ICE-Famicom-Disc-System.jpg" class="wow slideInLeft postImage" />
This is a very rare item, it is possibly only used within Intelligent Systems (IS) themselves, although IS did mass produce a similar product for the SNES so it is possible that this was THE official development kit for the NES.

ICE stands for In-Circuit Emulator and Intelligent Systems made these for most of Nintendo's hardware in the future too. These would be used by connecting to a development PC and allowing breakpoints and memory checking to be run from a debugger like interface.

ISD may stand for Intelligent Systems Debugger or Development.

FDT may stand for Famicom Disk T???

</div>
</section>

### Famicom Disk System Prototypes
<section class="postSection">
    <img src="/public/images/nes/PrototypeFamicomDiskWhite.jpg" class="wow slideInLeft postImage" />

<div markdown="1">


Retail FDS games were either yellow or Blue so a White FDS disk is used for in-development prototype games and may be re-writable. It is unclear whether they could be written to via a standard PC floppy drive however.
</div>
</section>

---
# Graphic Artist hardware

<section class="postSection">
    <img src="/public/images/nes/FmicomGraphiEditing.jpg" class="wow slideInLeft postImage" />

From the same children's book we can see Mr. Tezuka hard at work on Super Mario Bros 3, it looks like he is viewing the Character (Sprite/Pixel) data for the Mario sprite sheet. 

It is unclear if it is connected to the version running on the Famicom to the right of the computer. It would be pretty useful if changes made on the PC automatically updated the sprites in the running game, but it is unlikely they had  built the hardware to support such a feature.

</div>
</section>

<section class="postSection">
    <img src="/public/images/nes/FamicomMarioSpriteViewer.jpg" class="wow slideInLeft postImage" />
Presumably this is some sort of pixel editing tool that can piece together parts from the sprite sheet and update and possibly even animate the result to the viewer. It is unclear what the colours at the top represent, it could be the available colour pallet.

The Fujitsu FM R-50 HD business computer was used to create all the pixel art for Super Mario Bros 3. It was an IBM-PC compatible which ran a version of MS-DOS.
</div>
</section>

---
# In-house development kits
Due to the lack of official NES development kits, many companies had to reverse engineer the system themselves in order to do any game development for the system.

## NES Mission control dev kit
<section class="postSection">
    <img src="/public/images/nes/NESMissionControlDeckNESInternals.jpg" class="wow slideInLeft postImage" />
<img src="/public/images/nes/NESMissionControDeck.jpg" class="wow slideInLeft postImage" />

<div markdown="1">
The `Mission Control NES development kit` was created by Rocket Science Productions to help smaller developers get into the market of creating games for Nintendos new console [^1].

It consists of a breadboard filled with chips and screwed to a plank of wood and a modified retail NES console [^2].

Games built using this development system include but is not limited to:
* Bill & Ted's Excellent Adventure
* The Mutant Virus [^2]
</div>
</section>

# HAL “Game Maker” (Twin Famicom)
<section class="postSection">
    <img src="/public/images/nes/TwinFamicomGameMaker.png" class="wow slideInLeft postImage" />

<div markdown="1">
HAL Laboratory, Inc. who are best known for creating the Kirby and Mother series of games were very early NES developers. Like many other developers they did not have an official development kits available so took a rather unique approach to developing games on the system. They used the retail Twin Famicom System with an added trackball mouse, no keyboard at all [^7]!

Development data was written and read from the floppy disc and they presumably created some software that ran on the cartridge port that allowed them to edit code or sprite data.
</div>
</section>

## Software Creations Development Kit (Mike Webb)
Software Creations Ltd has a problem on their hands, they wanted to develop games for Nintendo's new home console but Nintendo only allowed companies who were already developing NES games to become licensed. 

This Catch-22 situation resulted in Mike Webb reverse engineering the NES hardware and creating his own development kit. According to an interview in Retro Gamer Magazine issue 37 it was quite an elaborate creation consisting of a stack of RAM chips that could be written on a Commodore 64 and then read via the cartridge port of a retail NES [^4]. 

You can see Mike Webb talking about the making of Solstice for NES, a game he not only programmed but also created the hardware development kit for, in the video below.
<iframe width="560" height="315" src="https://www.youtube.com/embed/894_PNqBkx4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Rare Ltd (PDS development system)
<section class="postSection">
    <img src="/public/images/nes/Famicom_PDS_INTERFACE.jpg" class="wow slideInLeft postImage" />
<div markdown="1">

Rare became of Nintendos first 3rd party developers outside of Japan by Reverse engineering the Famicom hardware before its western launch and presenting the results to Nintendo [^16].

This development kit was the result of the reverse engineering effort as you can see the board has `COPYRIGHT 1988 RARE LTD` rather than an official Nintendo or Intelligent Systems Copyright mark.

It also has `Nintendo PDS Interface` printed on the board, which likely stands for `Programmers Development System`.

This hints at it being used with the `PDS development system` made by `P.D.Systems Ltd` (Andy Glaister & co) which came with a 6502 assembler and was a full development system for  C63 and ZX Spectrum [^17]. 

PDS was a commonly used development kit in UK and it would be likely that when Rare was developing ZX Spectrum games they used this development system so all they had to do was reverse-engineer the NES and create an interface to control it from their existing development setup. 
</div>
</section>

### Eurocom (Used PDS)
In the source code for the 1990 NES game Magician, which was kindly opened source by developer Chris Shrigley, it contains .PDS files which are used in the PDS development kit.

When you open the .PDS files in a text editor the string `P.D.Systems Ltd 1985-88` can clearly be seen confirming that it used the  PDS development system.

So it was definitely used for NES game development by studio `Eurocom` but whether they used Rare's interface board or created their own remains a mystery.

### Zippo Software (Rare partnership)
In the UK Magazine GamesTM issue 22 it is mentioned that Zippo software's partnership with Rare meant they were one of the first to receive a NES development kit outside of Japan and thus producing `Solar Jetman` in 1989. It is possible that this is a PDS development System kit with the Interface card built by Rare.



## BEAM's NES Development System
BEAM was a very small company in the 80s mostly creating titles for the ZX Spectrum from their office in Melbourne, Australia. When the Famicom (NES) was released in Japan to critical acclaim they knew hat their next development platform would be. However they also knew that Nintendo would never give development kits to such a small company 
[^8].

They spent the year reverse engineering the Famicom hardware and in 1987 they completed their `NES Development System`. These caused quite a stir especially in the local Australian development community, so much so that BEAM started selling the kits to other development companies [^8].

The news of the sale of these 3rd party development kits did not please Nintendo and after a lengthy negotiation process BEAM agreed to stop selling its development kit in order to gain an official development license from Nintendo [^8].

## Westwood Studios

<section class="postSection">
    <img src="/public/images/nes/WestwoodStudiosNESDevkit.jpg" class="wow slideInLeft postImage" />
<div markdown="1">

A rather intriguing looking item was put up for auction on Ebay in 2011 claiming it was a NES development kit used by Westwood studios. Strangely the description for the item also mentions that "Atari" was printed on some of the boards. It is currently unknown who bought the hardware and if it was used for Westwood's only NES title called DragonStrike.

Games that may have been built with this kit:
* DragonStrike

</div>
</section>

## Namco
Namco reverse engineered the Famicom hardware and created their own suite of development tools [^10]. However very little information has been released about their internal development kits so it is presumed they were disposed of after NES development ceased.

## Square (Apple II & Twin Famicom)

<section class="postSection">
<iframe class="wow slideInLeft postImage" width="560" height="315" src="https://www.youtube.com/embed/LGzd7JRbxL0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<div markdown="1">

In a very rare interview with Nasir Gebelli he talks about creating NES games for Square with an Apple II and Mini Assembler, including final fantasy 1!

</div>
</section>

<section class="postSection">
<iframe  class="wow slideInLeft postImage" width="560" height="315" src="https://www.youtube.com/embed/z6pcfINCB4o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<div markdown="1">
This is a short video on the making on final fantasy 2 and it looks like most of the developers are using a Sharp Twin Famicom. This was used to at least test their games on but it is unclear if they built any custom hardware or even what computers they used to write the 6502 assembly on. Although it was presumably the Apple II with Mini Assembler.

</div>
</section>

---
# Unanswered Questions

## Did Nintendo ever provide an Official Development kit for the NES?
Many sources hint that there was no official Nintendo development kit for the NES and in fact there is very little information that has been leaked about these development kits. It looked like Nintendo themselves used EEPROM writers and custom made cartridges for development.

However in the NintendoAge article from issue 2 [^8] it mentioned that in 1987 BEAM software knew they couldn't get an official development kit from Nintendo and so made their own. When Nintendo found out about their custom development kit they wanted the sale of it stopped. Why did they want the custom development kits to case production if they didn't have officially supported ones?

Did they really rely on every single creating their own hardware based development kit?

## Was their official software such as assemblers?
Some sources such as [^3] suggest that there was an official Nintendo assembler for the NES but very little information online confirms this.

# References
[^1]: [NES Mission control dev kit](https://www.assembler-games.com/threads/nes-mission-control-dev-kit.41738/)
[^2]: [NES Mission Control Development System](http://devkits.handheldmuseum.com/NES_MissionControl.htm)
[^3]: [What was dev like on the NES back in 1987?](https://forums.nesdev.com/viewtopic.php?f=2&t=10169)
[^4]: [Bagshot Row : The Chuckie Egg Professional's Resource Kit](http://www.bagshot-row.org/chuckie-egg/authors.html)
[^5]: [Stars of Famicom Games](http://www.chrismcovell.com/secret/weekly/Stars_of_the_Family_Computer.html)
[^6]: [Nintendo’s Development Disks « Famicom World](https://famicomworld.com/workshop/tech/nintendos-development-disks/)
[^7]: [Kirby’s Development Secrets – Source Gaming](http://www.sourcegaming.info/2017/04/19/kirbys-development-secrets/)
[^8]: NintendoAge e-Zine Issue 02 2009
[^9]: Edge UK Issue 136
[^10]: [How Do You Make a Game? Part 2: Development Tools – The History of How We Play](https://thehistoryofhowweplay.wordpress.com/2018/07/10/how-do-you-make-a-game-part-2-development-tools/)
[^11]: [First Kirby Game Was Created With a Trackball, No Keyboard Gaming](https://uk.pcmag.com/games/89073/first-kirby-game-was-created-with-a-trackball-no-keyboard)
[^12]: [Gamasutra - A former mentor recalls the early career of Satoru Iwata](https://www.gamasutra.com/view/news/254169/A_former_mentor_recalls_the_early_career_of_Satoru_Iwata.php)
[^13]: [Original Famicom (NES) development kit belonging to RARE. : retrogaming](https://www.reddit.com/r/retrogaming/comments/9aspgn/original_famicom_nes_development_kit_belonging_to/)
[^14]: GamesTM issue 22
[^15]: [Take A Peek Behind The Curtain At Rare With This New Exhibit - Feature - Nintendo Life](http://www.nintendolife.com/news/2018/08/feature_take_a_peek_behind_the_curtain_at_rare_with_this_new_exhibit)