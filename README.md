# Awesome PICO-8 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

![PICO-8](https://www.lexaloffle.com/gfx/p8_jelpi.gif)
![tools](https://www.lexaloffle.com/gfx/p8_tracker.gif)
![code](https://www.lexaloffle.com/gfx/p8_cast.gif)

A curated list of PICO-8 resources, tutorials, tools and more. Inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 436,352 | 🐛 69 | 📅 2026-01-28 list thing. You might also like [awesome-lua](https://github.com/LewisJEllis/awesome-lua) ⭐ 4,454 | 🐛 47 | 📅 2024-08-11 and [awesome-love2d](https://github.com/JanWerder/awesome-love2d) ⭐ 4,215 | 🐛 0 | 🌐 PowerShell | 📅 2026-01-29.

PICO-8 is a fantasy console for making, sharing and playing tiny games and other computer programs. When you turn it on, the machine greets you with a shell for typing in a subset of [Lua](https://www.lua.org/) commands and provides simple built-in tools for creating your own cartridges.

## Contents

* [Community](#community)
* [Demoscene](#demoscene)
* [Resources](#resources)
* [Tutorials](#tutorials)
* [Tools](#tools)
* [Libraries](#libraries)
* [Assets](#assets)
* [Text Editors Language Support](#text-editors-language-support)
* [Hacks](#hacks---undocumented-pico-8-features)
* [Hardware](#hardware)
* [Articles & Posts](#articles--posts)
* [Talks](#talks)
* [Clones](#clones)
* [Contributing](#i-want-to-contribute)
* [License](#license)

### Community

* [Lexaloffle](https://www.lexaloffle.com)
  * [Blog](https://www.lexaloffle.com/bbs/?uid=1)
  * [PICO-8](https://www.lexaloffle.com/pico-8.php)
  * [Forum/BBS](https://www.lexaloffle.com/bbs/?cat=7)
  * [Twitter](https://twitter.com/lexaloffle)
  * [Facebook](https://www.facebook.com/lexaloffle/)
  * [Youtube](https://www.youtube.com/user/lexaloffletv)
* [Subreddit](https://www.reddit.com/r/pico8/)
* [#pico8 on Twitter](https://twitter.com/hashtag/pico8)
* [#pico8 on Freenode](https://webchat.freenode.net/?randomnick=1\&channels=#pico8\&prompt=1)
* [Pico-8 Console News](https://twitter.com/pico8console)
* [Pico-8 Wiki](https://pico-8.wikia.com/wiki/Pico-8_Wikia)
* [Slack Team](https://slofile.com/slack/pico-8) - PICO-8 Slack chat.
* [Discord Server](https://discord.gg/EwQ86eq) - PICO-8 Discord chat.

### DemoScene

* [Pico-8 demos on Demozoo](https://demozoo.org/platforms/81/)
* [Pico-8 demos on Pouet](https://www.pouet.net/prodlist.php?platform%5B%5D=PICO-8)
* [Article with demoscene effects code](https://medium.com/swlh/creativity-through-limitation-pico-8-fantasy-console-175294e13332)
* [Pico-8 demos on Youtube](https://www.youtube.com/results?search_query=pico+8+demoscene)

### Resources

* [Official Manual](https://www.lexaloffle.com/pico-8.php?page=manual) - Placeholder dump of pico-8.txt! (Proper manual coming soon).
* [PicoZine #1](https://sectordub.itch.io/pico-8-fanzine-1), [#2](https://sectordub.itch.io/pico-8-fanzine-2), [#3](https://sectordub.itch.io/pico-8-fanzine-3) and [#4](https://sectordub.itch.io/-pico-8-zine-4) - PICO-8 Zine is a 48-page fanzine made by and for PICO-8 users.
* [Going from Lua 5.2 to PICO-8's Lua](https://gist.github.com/josefnpat/bfe4aaa5bbb44f572cd0) - This document is here to help folks with a proficiency in Lua understand the limitations and discrepencies between Lua and PICO-8's Lua.
* [Cheat Sheet (printable)](https://ztiromoritz.github.io/pico-8-spick/) - A reduced cheat sheet in a printable format. German and English version available.
* [Cheat Sheet (wallpaper)](https://www.lexaloffle.com/bbs/?tid=28207) - An enhancement of the printable cheat sheet for use as a desktop wallpaper.

### Tutorials

* [Token optimization](https://github.com/seleb/PICO-8-Token-Optimizations) ⭐ 154 | 🐛 0 | 📅 2021-08-06 - tips\&tricks for saving tokens.
* [Newgrounds Medals Tutorial](https://github.com/Bigaston/pico-8-newgrounds-tutorial) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2018-07-23 - a little tutorial to add Newgrounds Medals to PICO-8 games.
* [Music Tracker Tutorial Series](https://www.youtube.com/playlist?list=PLjZAika8vyZkyOjoCp0EbHeIFZ8MLlhvg) - Making audio with PICO-8.
* [Tron Lightcycle game from scratch](https://youtu.be/ZuaLuMhwcc8) - A quick introduction to PICO-8 writing a game from scratch.
* [A PICO-8 Spaceshooter in 16 GIFs](https://ztiromoritz.github.io/pico-8-shooter/) - Screencaptures of writing a Spaceshooter game step by step.
* [Tweetjam, BBS thread](https://www.lexaloffle.com/bbs/?tid=3726) - cards which code fits in a tweet (really useful to learn some fun techniques).
* [Sample code on the BBS](https://www.lexaloffle.com/bbs/?search=sample+code) - the search is not 100% accurate, but some of those cards features some nice tricks you can re-use in your future code.
* [Binary save system](https://ultiman3rd.wordpress.com/2018/02/01/pico-8-binary-save-system/) - Custom game save system that supports various data types
* [Lazy Devs Breakout](https://youtube.com/playlist?list=PLea8cjCua_P0qjjiG8G5FBgqwpqMU7rBk\&si=CaivHwqC6uYjJA21) - step-by-step videos for [roguelikes](https://youtube.com/playlist?list=PLea8cjCua_P3LL7J1Q9b6PJua0A-96uUS\&si=ZYrBbZMJr9ABHsnA), [shmups](https://youtube.com/playlist?list=PLea8cjCua_P3Sfq4XJqNVbd1vsWnh7LZd\&si=bKKGy-2IKwcTQxeF), and more

### Tools

* [picotool](https://github.com/dansanderson/picotool) ⭐ 399 | 🐛 53 | 🌐 Python | 📅 2024-02-03 -  Tools and Python libraries for manipulating Pico-8 game files.
* [picoDeploy](https://github.com/torch2424/picoDeploy) ⚠️ Archived - Deploy Pico-8 carts as standalone applications on desktop (Electron) and mobile (Ionic).
* [Shrinko8](https://github.com/thisismypassport/shrinko8) ⭐ 149 | 🐛 10 | 🌐 Lua | 📅 2026-02-10 - A minifier that aggressively shrinks Pico-8 code size. Also includes a linter and other tools.
* [P8Coder](https://github.com/movAX13h/P8Coder) ⭐ 109 | 🐛 2 | 🌐 C# | 📅 2025-07-22 - A programming tool that replaces the lua code in pico-8 cartridges (p8) with the code you write in P8Coder.
* [midi2pico](https://github.com/gamax92/midi2pico) ⭐ 70 | 🐛 1 | 🌐 Lua | 📅 2020-01-17 - A MIDI to PICO-8 converter.
* [MIDI to PICO-8](https://github.com/andmatand/midi-to-pico8) ⭐ 66 | 🐛 2 | 🌐 Python | 📅 2017-10-21 - A tool to convert MIDI files to PICO-8 music.
* [PICO-EC](https://github.com/JoebRogers/PICO-EC) ⭐ 58 | 🐛 0 | 🌐 Lua | 📅 2019-01-05 - A tiny scene-entity-component library created for the PICO-8 fantasty console.
* [Pico8Utils](https://github.com/josefnpat/pico8utils) ⭐ 55 | 🐛 1 | 🌐 Lua | 📅 2018-08-22 - Compilation of lua scripts based on the unix philosophy for working with .p8 files.
* [p8](https://github.com/jozanza/p8) ⭐ 50 | 🐛 6 | 🌐 TypeScript | 📅 2023-03-06 - A dependency manager and build tool. Lets you share code/sprites, `require()` dependencies, and auto-reload carts on save. Works with any external code editor and supports [MoonScript](https://moonscript.org/).
* [TS-PICO-8](https://github.com/tmountain/pico-8-typescript) ⭐ 44 | 🐛 0 | 🌐 JavaScript | 📅 2025-12-17 - Create PICO-8 games using TypeScript.
* [pico8-deploy](https://github.com/tducasse/pico8-deploy) ⭐ 34 | 🐛 0 | 🌐 Makefile | 📅 2022-03-04 - An easy way to export and deploy PICO-8 projects to itch.io
* [pico2png](https://github.com/briacp/pico2png) ⭐ 28 | 🐛 1 | 🌐 Perl | 📅 2020-04-10 - Spritesheet extraction written in perl.
* [Pico-8 Carts Downloader - Bash ](https://github.com/kikookoubis/pico-8-carts-bash-downloader) ⭐ 22 | 🐛 2 | 🌐 Shell | 📅 2017-03-24 - Downloads cartridge from the BBS (single cart, whole index or dump your favourited entries) & rename them according to their metadata.
* [p8 responsive webplayer transform](https://github.com/benwiley4000/pico8-responsive-webplayer-transform) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2016-10-23 - Python script that makes your HTML export page responsive.
* [pico8Grunt](https://github.com/TeamNoComplyGames/pico8Grunt) ⚠️ Archived - A build system for pico8 games, using gruntjs.
* [p8dl - Carts Downloader - Python](https://github.com/franciscod/p8dl) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2017-09-26 - Downloads cartridges into the correct folder (looks at your config.txt).
* [yap8b](https://github.com/Enerccio/yap8b) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2021-07-04 - Build tool for creating pico carts from multiple source files.
* [Sprite Editor](https://www.lexaloffle.com/bbs/?tid=51270) - Keyboard only 8x8 pixel art tool.
* [Spritesheets and tools for the PICO-8 Palette](https://www.reddit.com/r/pico8/comments/3jhmni/spritesheets_and_tools_for_the_pico8_palette/) - Compilation of works assest and tools using the PICO-8 palette.
* [Color Palette](https://www.romanzolotarev.com/pico-8-color-palette/) - Hex and RGB colors codes for web.
* [PICO-8 font](https://www.lexaloffle.com/bbs/?tid=3760) - by [RhythmLynx](https://www.lexaloffle.com/bbs/?uid=11704).
* [Denote](https://bikibird.itch.io/denote) - Converts MIDI files into SFX data-- interactive and web based.
* [Custom template](https://www.lexaloffle.com/bbs/?tid=31000) - A simple and clean template, that fixes issues with fullscreen, mouse and just looks nice.
* [Fillp Tool](https://seansleblanc.itch.io/pico-8-fillp-tool) - A simple helper tool for generating fillp patterns.
* [Depict](https://bikibird.itch.io/depict) - Converts image into a dithered image using PICO-8 colors and reduces it to a maximum size of 128 x 128.
* [picoCAD](https://johanpeitz.itch.io/picocad) - A PICO-8 program to build and texture lowpoly 3D models.

### Libraries

* [SCUMM-8](https://github.com/Liquidream/scumm-8) ⭐ 351 | 🐛 2 | 🌐 Lua | 📅 2025-08-11 - De-make of the SCUMM engine for making point-and-click classic adventures.
* [Lib-Pico8](https://github.com/clowerweb/Lib-Pico8) ⭐ 194 | 🐛 1 | 🌐 Lua | 📅 2020-02-09 - A Pico-8 library of useful common functions.
* [PICO-Tween](https://github.com/JoebRogers/PICO-Tween) ⭐ 91 | 🐛 0 | 🌐 Lua | 📅 2020-03-25 - A small library of tweening/easing functions for use in the PICO-8 fantasy console, inspired by Robert Penner's easing functions.
* [Pico-Kit](https://github.com/outkine/pico-kit) ⭐ 88 | 🐛 0 | 🌐 Lua | 📅 2019-04-29 - An opinionated collection of Pico-8 helpers that make it easier to get going.  Adds OOP, better debugging, and physics.
* [pico8-physics](https://github.com/jamesedge/pico8-physics) ⭐ 52 | 🐛 0 | 🌐 Lua | 📅 2020-04-04 - Pico8 implementation of Box2d with 8 demos.
* [pico-test](https://github.com/jozanza/pico-test) ⭐ 45 | 🐛 2 | 🌐 JavaScript | 📅 2023-03-19 - PICO-8 testing framework.
* [parens-8](https://github.com/Siapran/parens-8) ⭐ 41 | 🐛 0 | 🌐 Lua | 📅 2025-05-18 - Bypass the Lua token limit with a tiny lisp interpreter/compiler.
* [pico8-missing-builtins](https://github.com/adamscott/pico8-missing-builtins) ⭐ 29 | 🐛 1 | 🌐 Lua | 📅 2019-03-23 - Provides Lua built-in functions to pico8.
* [p8-canvas](https://github.com/Siapran/p8-canvas) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2025-03-08 - A high performance infinite canvas/texture library.

### Assets

* [midilib](https://www.lexaloffle.com/bbs/?cat=7#tag=midilib) - Custom SFX instruments

### Text Editors Language Support

* Visual Studio Code: [pico8-ls](https://github.com/japhib/pico8-ls) ⭐ 105 | 🐛 30 | 🌐 TypeScript | 📅 2025-09-23 - PICO-8 Language Server, providing full language support for the PICO-8 dialect of Lua.
* Vim: [vim-pico8-syntax](https://github.com/justinj/vim-pico8-syntax) ⭐ 65 | 🐛 5 | 🌐 VimL | 📅 2017-09-17
* Emacs: [pico8-mode](https://github.com/Kaali/pico8-mode) ⭐ 32 | 🐛 7 | 🌐 Emacs Lisp | 📅 2023-10-19
* Visual Studio Code / NeoVim / JetBrains / Others： [pico8-definitions](https://github.com/ahai64/pico8-definitions) ⭐ 32 | 🐛 0 | 🌐 Lua | 📅 2025-11-12 - An add-on for sumneko/lua to provide PICO-8 language support.
* Atom: [language-pico8](https://atom.io/packages/language-pico8)
* Sublime: [Sublime PICO-8](https://packagecontrol.io/packages/PICO-8) - PICO-8 plugin for the Sublime Text editor (color scheme, font, build system, code completion, snippets...).

### Programming Fonts

You might be interested to install [pico-8 programming fonts](https://github.com/juanitogan/p8-programming-fonts) ⭐ 120 | 🐛 0 | 📅 2020-05-19 they support the pico-8 custom characters as well as various fonts (bitmap and regular anti-aliased fonts). Check the [BBS thread here](https://www.lexaloffle.com/bbs/?tid=28975).

How to install the font(s):

* **Linux:** copy the files on \~/.fonts and `sudo fc-cache -f -v`
* **Windows:** copy the files on c:/windows/fonts/

### Hacks - undocumented PICO-8 features

* [Mouse](https://www.lexaloffle.com/bbs/?tid=3549) - How to retrieve mouse coordinates (with demo).
* [p8keyboard.js](https://github.com/dppc/p8keyboard.js) ⭐ 22 | 🐛 0 | 🌐 HTML | 📅 2016-06-05 - Javascript "keyboard adapter" for the Pico-8. Send ASCII characters to a Pico-8 program running in a browser.
* [SFX Modifications](https://www.lexaloffle.com/bbs/?tid=3561) - Four effects that can only be applied by modifying memory (with demo).
* [Tracker State/Audio Memory Locations](https://www.lexaloffle.com/bbs/?pid=10719#p10719) - How to access and modify audio data as it is playing.

### Hardware

* [GameShell](https://www.clockworkpi.com/) - A modular handheld game console that allows you to play & modify retro games and DIY new devices. Check the [GameShell Docs](https://github.com/clockworkpi/GameShellDocs/wiki/Running-PICO-8-on-the-GameShell) ⭐ 190 | 🐛 5 | 📅 2021-08-15 for how to run PICO-8 on the GameShell.
* [PocketChip](https://shop.pocketchip.co/) - A handheld designed for playing and coding anywhere. Officially supported by pico-8. [PoketChip version of pico-8](https://www.lexaloffle.com/bbs/?tid=34009)

### Articles & Posts

* [Indie Retro News](https://www.indieretronews.com/2015/10/pico-8-8-bit-fantasy-console-from.html) - A great introduction to PICO-8 by [@ABrugsch](https://twitter.com/ABrugsch).

### Talks

* [Sharing the love](https://www.youtube.com/watch?v=AmMYWD2Zbso) - Making games with PICO-8. linux conf au 2017 - Hobart, Australia

### Clones

* [LIKO-12](https://github.com/RamiLego4Game/LIKO-12) ⚠️ Archived - An open source fantasy computer made using LÖVE with 96kb RAM.
* [PicoLove](https://github.com/picolove/picolove) ⭐ 869 | 🐛 17 | 🌐 Lua | 📅 2024-10-24 - Pico-8 Reimplementation in LÖVE.
* [Pikuseru](https://github.com/PikuseruConsole/pikuseru) ⭐ 113 | 🐛 0 | 🌐 Rust | 📅 2023-12-07 - Open Source Fantasy Console in pure Rust \[Core].
* [TIC-80 by Nesbox](https://nesbox.itch.io/tic) - Tiny Computer, available on HTML 5, Windows, Linux 32/64bit, Android & MacOSX
* [tac08](https://0xcafed00d.itch.io/tac08-rg350) - tac08 is an emulation of the runtime part of the Pico-8 fantasy console, running on RG350 handheld game console.
* [LowRes NX](https://lowresnx.inutilis.com/) - Fantasy Console available on IOS, MacOS, Windows, Linux, and GameShell (BASIC code support)
* [BeetPx](https://beetpx.dev/) - A TypeScript framework for pixel art browser games. Heavily inspired by PICO-8.

### I Want to Contribute!

Great! :smiley:

Please, read the [contribution guidelines](origin/CONTRIBUTING.md) first.

### License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Felipe Bueno](https://twitter.com/felipebueno) has waived all copyright and related or neighboring rights to this work.

See [LICENSE](origin/LICENSE) for more information.
