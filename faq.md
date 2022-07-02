layout: page
title: "Triforce% OoT ACE Showcase: FAQ"
permalink: /faq/

# Frequently Asked Questions

## Project

**What is Triforce% OoT ACE Showcase?**

Triforce% is a hybrid RTA/TAS superplay ("speedrun") of The Legend of Zelda: Ocarina of Time (1.0) (U) (Nintendo 64) which uses Arbitrary Code Execution (ACE) to install a set of data loaders in the console’s memory, enabling arbitrary assets (scenes, objects, music, etc.) in the game ROM to be seamlessly live-patched via the TAS replay device. By modifying the game programming and assets, beta content cut from the final version of OoT is restored and brought to life on screen. A new plot is constructed based on this beta content and on urban legends from the late '90s, culminating in Link obtaining the Triforce, all within the vanilla game.

Then, Link uses the power of the Goddesses--and we use the power to make the game whatever we can imagine--to go far beyond what would have been possible in 1998, and bring together the community in a meaningful way.

**Okay, explain that to me like I’m five?**

A human speedrunner and a robot sit down in front of a completely unmodified copy of Ocarina of Time on N64. They press buttons on the controllers very quickly and very precisely, and activate complicated glitches in the game. These glitches let them hack into the game and start changing the plot, but this is still all done just by pressing buttons on the controllers.

**How does Triforce% relate to OoT Beta Showcase?**

OoT Beta Showcase is the name we were using for Triforce% in order to avoid spoiling that we were going to get the Triforce. They are the same thing.

**Why did the team make Triforce%?**

The short answer is, to finally get the Triforce in OoT and make the dreams of millions of players come true. Other answers include:
- to raise hundreds of thousands of dollars for MSF (Doctors Without Borders)
- to explore the relationship between beta content and urban legends in OoT
- to create a new type of video game related creative work, which has almost never been seen before (prior example was [MrCheeze putting Mew under the truck with ACE](https://www.youtube.com/watch?v=i2x3pIvVnP4&t=2s))
- to show off what can be technically achieved on a real N64 console

## Lore

**So is the Triforce actually obtainable in Ocarina of Time?**

The answer to this question depends on your philosophy. Some good answers to this question would be:
- “It is now!”
- “If you are a superhuman with 12 arms who can accurately press buttons on four controllers 480 times per second, then yes, you can get the Triforce!”

The scene where Link gets the Triforce shown during Triforce% was created by our team and injected into the game via controller input. None of the data comprising this scene (room model, cutscene, music, custom Link animation, etc.) is in the cartridge ROM.

However, the glitches which can be used to get arbitrary code execution ARE in Ocarina of Time. They were not put there intentionally by the developers of course, but they are as much a part of the game as any other part of the game’s programming. Since the player can use those glitches to get the Triforce, there is a sense in which getting the Triforce is indeed now part of the game. Of course this also means that anything else the player is able to create, program, and inject via controller input--in our case, Breath of the Wild Link and Zelda and all of the people in the Twitch chat--also become a part of the “““““canon””””” of Ocarina of Time.

**Why does Breath of the Wild Link speak Japanese?**

The primary reason is that the Japanese version of BotW gets closer to having Link speak than the English version does. Some have conjectured that the Japanese audience is more willing to accept Link speaking--being more of his own character rather than just an avatar--than the Western audience. And, after all, Link has had Japanese voice actors for his vocalizations since OoT, even though these have not included actual speech. So, it seemed more appropriate to give Link a Japanese voice than an English voice.

**What was the significance of X element (e.g. Unicorn Fountain, Overture of Sages, etc.) shown in the run?**

See [SwankyBox’s video](https://www.youtube.com/watch?v=1_RighmL04g) and [Hard4Games’ video](https://www.youtube.com/watch?v=f9cCtRYMKm4) for more information on the lore.

## Data

**Surely this is a romhack playing off of a flashcart?**

No. The cartridge is a completely unmodified, original OoT V1.0 (US) cart. The N64 used during the SGDQ marathon has an RGB mod, but this is a passive mod to the video output circuit to get better video quality and does not affect the game contents in any way. All of the custom content shown during the project was injected into the game live through controller input.

**I saw some references to a “shortcut” Triforce% ROM and a “romhack” Triforce% ROM. What are these?**

Shortcut: This is a copy of OoT which has one modified actor, which gives arbitrary code execution (ACE) “for free” without needing any complicated setup. From there, the rest of the data is injected through controller input just like in the real run. This was used by the development team to test most of the contents of Triforce%, because no one on the team besides Savestate is actually skilled enough to do the ACE setup by hand. You can build this mod with our toolchain from an original 1.0 ROM. This was NOT used during the live event at SGDQ.

Romhack: The Triforce% build toolchain also outputs a romhack version of Triforce%, which is a modified ROM which contains all the custom contents built-in instead of being injected through controller inputs. This was used by the development team for testing purposes. You can build a smaller, partial version of this with our toolchain from an original 1.0 ROM. This was NOT used during the live event at SGDQ.

**Where can I get a copy of the ROM / all the data injected?**

For legal reasons, we cannot distribute any ROMs, and we also cannot distribute any data files which contain any copyrighted code or assets. All of the tools, code, and assets created by the Triforce% team are released [here](https://github.com/triforce-percent/triforce-percent). Because this release does not include any copyrighted content, it is not possible to reproduce the full Triforce% run from this data. Besides, Triforce% was not created to be a fully playable “game”; if the player were to go outside the plot shown in the live performance, at best they would simply find the vanilla game, and at worst they would encounter crashes and other issues.

**Was any of the beta content shown copied from the Gigaleak or the Spaceworld ‘97 overdump?**

No. In fact, Triforce% was in progress before the Gigaleak was released and was mostly done before the Spaceworld ‘97 overdump was released. All of the content which was not already in the OoT cartridge was created by the Triforce% team based on the beta trailers and such.

**How much/which parts of this were already on the cart?**

Here is a complete list of all the debug / beta content left on the cartridge which we showed off:
- Inventory editor
- Arwing
- Part of text patching system is for the N64DD expansion (URA Zelda)
- Beta Kokiri head and body
- Butterfly get item model and entry in one of the item tables
- Arguable: full Ocarina system
- Arguable: ability to change between child and adult without pulling the Master Sword
- Beta Great Fairy
- Pedestal of the Ocarina
- Triforce wipe animation before entering Triforce room
- Beta Staff Roll cutscene flying through Kokiri Forest

Here is a complete list of all the alpha / beta content which was shown in official prerelease footage / screenshots / etc. So this is real alpha / beta content, but it was recreated by our team, not left on the cartridge.
- Equipping Medallions to C-buttons
- Unicorn Fountain scene
- Beta Great Fairy behavior
- Triforce room scene
- Triforce pieces model / behavior
- Triforce light model
- Triforce chest model / behavior

## TASBot

**What is TAS?**

A TAS is a Tool-Assisted Speedrun. The tools used vary by game but often consist of using an emulator with features to help record inputs and retry things. Sometimes letting the player see game values, create savestates to go back to and retry a section, slow down the game, or even go frame by frame so specific inputs can be entered for every individual frame.

However, in Triforce%, the inputs TASBot plays into the game were not created this way at all. They were generated by scripts which convert various programs the team wrote into controller input. Emulators were only used when initially debugging these programs, but most of Triforce% was developed on a real N64, not using emulators at all.

**What is TASBot doing?**


TASBot the cute robot is a mascot for a team of people working towards getting TASs to actually run correctly on real consoles through the use of a TAS replay device. You can find this team at [https://discord.tas.bot/](https://discord.tas.bot/)

**What is a TAS replay device then?**

A TAS replay device is basically a controller adapter but better. It takes the TAS input file and actually feeds the necessary inputs to the console when the console needs it. This is the little box which TASBot holds on stage, which connects between a host computer and the game console’s controller ports.

**Where could I learn to make something like this?**

TAS: [tasvideos.org](https://tasvideos.org)

N64 homebrew: N64brew discord

OoT romhacking: [The decomp](https://github.com/zeldaret/oot), [Hylian Modding discord](https://discord.gg/nGFZ394)


**Can I still contribute to N64 / OoT / TAS development if this all seems over my head right now?**

You sure can! Hop into any community that seems interesting and ask around. Do consider trying to read into things if you can find things to read, but most speedrunning and adjacent communities are quite helpful to those seeking to give things a try. If you’re not sure where to head first any of the linked communities may be a good start.

## Technical

**How did you do all of this?**

21 years of reverse engineering effort by the OoT community, and then an additional 2 and a half years of development effort by the Triforce% team. Over a thousand hours by more than 25 people: programmers, artists, musicians, voice actors…

For a technical explanation of how we use glitches to obtain ACE and then use ACE to get Total Control over the game, see the [Retro Game Mechanics Explained video on Triforce%](https://www.youtube.com/watch?v=qBK1sq1BQ2Q).

**How did you get the Twitch messages in the game? Were they actual messages from the live chat?**

Yes, during the SGDQ 2022 showcase they were real live chat messages. In any of the videos created in advance, you'll see fake messages with usernames made of random characters which were generated by a script to simulate the Twitch chat.

As far as how it was done, some scripts on the computer controlling TASBot connect to the Twitch API and read the chat. Chat messages are filtered and metadata about them is encoded and sent to TASBot. TASBot injects them into the game via the controller ports, in a similar way to how all the other custom content was injected. A custom actor in the finale scene renders the messages in the sky, in a vaguely similar way to how they are rendered in a web browser.

**How did you do the cel shading?**

We hope to eventually make some sort of video explaining this, but the short answer is that it is using alpha compare and drawing each triangle once per cel level. A patch to the F3DZEX RSP microcode moves the lighting information from the shade color channels to the shade alpha channel. This was initially conceived by Sauraen, first implemented and tested by glank, and then integrated into fast64 by Sauraen. The fast64 display list generation code is here TODO. Two other, completely different, implementations of cel shading on the N64 were created in January 2022, by James Lambert https://www.youtube.com/watch?v=AQphLFA0DZY and Wiseguy. Our implementation was made in October 2021 but was not made public and is different from both of these.

**How did you make the Running Man boss fight?**

Generally, the same way we made all the other custom content. As far as the Running Man boss himself, the original 3D model and skeleton was imported into Blender, IK rigged, and animated by rankaisija. rankaisija also wrote his AI and most of his other code, and Sauraen wrote a few small parts. The Running Man boss is a separate actor from the custom Running Man who meets us at the end of the race in the Lost Woods, which is also separate from the Running Man actors in the vanilla game.

**The ROM is, by definition, read-only. So how did you change content within existing parts of OoT which were loaded from the cartridge?**

There are three overall techniques which were used for patching the game.

- After the game loads anyfile from the cartridge, it checks a list of patches which have been loaded into memory via controller input. If this is a file we want to patch, it then applies our patch to that data, in the form of a list of differences (e.g. move to byte 100, write 2 bytes: 00 01, etc.). This happens before that data is “returned” to whatever code requested to load it. This method is used for making relatively small changes to things like scene files or actor overlays (code).
- We can replace a whole file which is normally on the cartridge with a copy we uploaded into RAM. That is, we change the file list (which is stored in RAM) and overwrite the entry for that file from the ROM with a special entry telling it to load from our injected RAM data instead. This is used for things like fully custom scenes, or actors which needed larger changes like the Gerudo guards and Zora’s Domain ice/waterfall.
- We can patch the code (stored in RAM) which asks to load the data from ROM, so that it doesn’t try to load from a ROM file at all in cases we want. This is used for types of data which are normally streamed in uncompressed format from the ROM, including music sequences, sound effects, and Link animations, and types of data which have tables separate from the file list, like completely custom actors and objects.


---

Triforce Percent
