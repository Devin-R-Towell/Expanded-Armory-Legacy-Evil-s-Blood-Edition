# Expanded Armory: Legacy

[![Workflow status](https://img.shields.io/github/actions/workflow/status/ThexXTURBOXx/Expanded-Armory-Legacy/build.yml?logo=githubactions&style=flat-square)](https://github.com/ThexXTURBOXx/Expanded-Armory-Legacy/actions/workflows/build.yml)
[![CurseForge Downloads](https://img.shields.io/curseforge/dt/1197267?logo=curseforge&style=flat-square)](https://www.curseforge.com/minecraft/mc-mods/expanded-armory-legacy)
[![Modrinth Downloads](https://img.shields.io/modrinth/dt/75W8JAu2?logo=modrinth&style=flat-square)](https://modrinth.com/mod/expanded-armory-legacy)
[![Translate on Crowdin](https://img.shields.io/static/v1?label=Translate&message=on%20Crowdin&logo=crowdin&style=flat-square)](https://crowdin.com/project/balkons-weaponmod-legacy)
[![Sponsor me!](https://img.shields.io/github/sponsors/ThexXTURBOXx?logo=github&style=flat-square)](https://github.com/sponsors/ThexXTURBOXx)

Expanded Armory: Legacy Evil's Blood Edition is a mod, it takes the tool materials from other mods and brings them to Balkon's WeaponMod: Legacy.

What sets this version appart is, Additional Support for Blood Magic, & Blood Arsanal.  Also a couple of other mods. 
This is a Fork of
[HyperSpeeed](https://nmexis.me/)'s modernisation fork of
the [original project](https://github.com/mallrat208/ExpandedArmory).

## Why?
Well two reasons, 1st I love Balkon's weapon Mod allways have, I play legacy and Beta Versions of minecraft just so I can install the original.
Sadly Most of the files I used to own of all of the Original Balkon's Weapon mod are either corrupted beyond repair lost, or glitched to hell.
I have never been satisfied with any weapon mod that is not Balkon's, Tinkers is great and all, but it just doesn't feel close to home enough for me.
I love the smithing system in tinkers and if I could play tinkers without all the weapons and extra fluff, without it crashing on me I would.

Apart from that I was supper estatic to discover someone revived the project and ported it over to 1.7.10. (My favorite version of Minecraft to date) "Mostly because of Thaumcraft and Forbbiden magic"
I was even glad that they added more weapon types to the mod with extra compatibilities with other mods.

However sadly the mods I wanted to combine the most were left out. SO I have decided to learn Java and make my own fork of the mod.
This repository is for my personal use, I do not care what you do with it, so long as the original Auther would be ok with it. 
I plan on getting permision to upload my version to CurseForge and Modrinth at some point, however for now the few of you who do happen to see this I am Glad you found it.

Currently this reposistory is fresh and has yet to implement any atchual changes. Have fun, and happy moding.

the rest of this section is coppied from the original branch of this mod and Is not my work.

Without anything further to say here, enjoy!

## Contributing

There are many ways to contribute!

### Development

Development should be rather easy. BWM: Legacy currently uses Loom in three different flavors:

- [Architectury Loom](https://github.com/architectury/architectury-loom) for everything above 1.16.5. It is the easiest
  way to enable multi-platform modding and is officially endorsed by
  the [Architectury API](https://github.com/architectury/architectury) (which this mod depends on in 1.16.5+).
- [Essential Loom](https://github.com/EssentialGG/architectury-loom) for all versions between 1.8.9 and 1.12.2. Sadly,
  Architectury Loom does not officially support Minecraft versions that old. So,
  the [Essential team](https://github.com/EssentialGG) added many fixes to Architectury Loom to support these legacy
  versions.
- [My own Loom](https://github.com/ThexXTURBOXx/architectury-loom/tree/dev/1.6-1.7.10) for everything between and below.
  Sadly, even Essential Loom is not even able to handle some of these other versions correctly. So, I forked it and
  hence created a fourth fork layer of the official Loom - perfect! I added fixes and hacks to make Loom even
  1.7.10-compatible and fixed a few additional bugs that I found in upstream versions; that's all.

This way, you don't have to worry about most of the background tasks.  
If you want to change the mod's code, you can just do the following:

1. Clone the repo: `git clone https://github.com/ThexXTURBOXx/Expanded-Armory-Legacy.git`
2. Checkout the branch you want to work on, e.g., `git checkout 1.7.10`
3. Open `build.gradle` or `build.gradle.kts` (depending on which version you want to develop on) in your favorite IDE (I
   am using IntelliJ IDEA and everything works fine here... Don't know about other IDEs, though!)
4. Your IDE should download and build some stuff. This might take quite some time...
5. Now, you should be able to change the code properly!

To test your changes, you can just do the following:

1. Run `gradlew build` to compile the mod
2. If everything worked fine, you should find the mod jar in either `build/libs/ExpandedArmory-forge-1.5.0.jar`
   or `<PLATFORM>/build/libs/ExpandedArmory-<PLATFORM>-1.5.0.jar`

When you are done with your changes, push them to
a [fork](https://github.com/ThexXTURBOXx/Expanded-Armory-Legacy/fork) of my repository
and [open a PR](https://github.com/ThexXTURBOXx/Expanded-Armory-Legacy/compare/1.7.10...Sunconure11:ExpandedArmory:master)!  
**Make sure to target my repository, not the upstream (original) Expanded Armory repository!**

<!--TODO
### Translation

This project uses [Crowdin](https://crowdin.com/project/balkons-weaponmod-legacy)!  
If you want to translate the mod, feel free to change one of the existing languages there!  
If you want to translate the mod to another language that I have not yet added there,
please [open an issue](https://github.com/ThexXTURBOXx/Balkons-WeaponMod-Legacy/issues/new) to ask me to add it there
first.-->

### Bug Reports and Feature Requests

If you find a bug or want to see something new in the mod, feel free to let me know by
[opening an issue](https://github.com/ThexXTURBOXx/Expanded-Armory-Legacy/issues/new)!
