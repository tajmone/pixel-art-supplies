# Game Engines for Pixel Art

A curated list of game engines that support Pixel Art graphics — where «game engine» can be interpreted in a non strict manner, including well known middleware and graphics/game libraries, as well as game-oriented programming languages and IDEs.

Originally started as a thread on Cosmigo forum:

- https://community.cosmigo.com/t/game-engines-for-pixel-art/318


-----

**Table of Contents**


<!-- MarkdownTOC autolink="true" bracket="round" autoanchor="false" lowercase="only_ascii" uri_encoding="true" levels="1,2,3,4" -->

- [Game Engines and Pixel Art](#game-engines-and-pixel-art)
- [Game Engines Table](#game-engines-table)
- [Engines That Support Pixel Art](#engines-that-support-pixel-art)
    - [AGS \(Adventure Game Studio\)](#ags-adventure-game-studio)
    - [Anura](#anura)
    - [Construct](#construct)
    - [Ethanon](#ethanon)
    - [Game Maker](#game-maker)
    - [Godot](#godot)
    - [LÖVE](#l%C3%96ve)
    - [PGE](#pge)

<!-- /MarkdownTOC -->

-----



# Game Engines and Pixel Art

Pixel-Art is definitely a determining factor in the choice of a game engine, because some 2D engines can't handle pixel art well — it needs to support pixel perfect graphics, without apllying filters that might distort the pixels, and it should handle well pixel ratios at different screen resolutions, and possibly do a good job in scaling up images.

Some engines might offer Pixel Art support out of the box, while others might need some configuration tweaks or dedicated scripts.

It might be worth also listing 2D Engines that _don't_ support Pixe Art, and explain why — this could spare users the experience of embarking in dead-end attempts to use a given engine.

# Game Engines Table

Here is a table for quick reference of various reknown game engines, further down a more detailed review of some of them.


|    egnine    | pixel-art |      develop games in     | has IDE |        license         |
|--------------|-----------|---------------------------|---------|------------------------|
| [AGS]        | yes       | via GUI and scripts       | yes     | [Artistic License 2.0] |
| [Anura]      | yes       | [FML/FFL]                 | yes     | [zlib]                 |
| [Construct]  | yes       | JS / via GUI menus        | yes     | _commercial_           |
| [Ethanon]    | ???       | [AngelScript]             | yes     | [MIT]                  |
| [Game Maker] | yes       | via GUI / [GML]           | yes     | _commercial_           |
| [GDevelop]   | ???       | via GUI                   | yes     | [MIT]                  |
| [Godot]      | yes       | [GDScript] / C# / C++     | yes     | [MIT]                  |
| [LÖVE]       | yes       | Lua                       | _no_    | [zlib]                 |
| [PGE]        | 100%      | via GUI menus             | yes     | [GPLv3]                |
| [Phaser]     | yes       | JavaScript / [TypeScript] | online  | [MIT]                  |
| [Torque2D]   | ???       | [TorqueScript]            | _no_    | [MIT]                  |
| [Gate]       | 100%      | [Rust]                    | _no_    | [Apache 2.0]           |

[AGS]: http://www.adventuregamestudio.co.uk/ "Visit Adventure Game Studio website"
[Anura]: https://github.com/anura-engine/anura
[Construct]: https://www.scirra.com/
[Ethanon]: http://ethanonengine.com/
[Game Maker]: https://www.yoyogames.com/gamemaker "Visit Game Maker website"
[Gate]: https://github.com/SergiusIW/gate "Visit the Gate project"
[GDevelop]: https://gdevelop-app.com/
[Godot]: https://godotengine.org
[LÖVE]: https://love2d.org
[PGE]: http://wohlsoft.ru/PGE/ "Visit the PGE Project website"
[Phaser]: http://phaser.io/
[Torque2D]: https://github.com/GarageGames/Torque2D

<!-- LANGUAGES -->

[AngelScript]: http://www.angelcode.com/angelscript/
[FML/FFL]: https://frogatto.com/2010/07/18/how-frogatto-formula-language-ffl-works/ "Info about Frogatto Markup Language (FML) and Frogatto Formula Language (FFL)"
[GDScript]: http://docs.godotengine.org/en/3.0/getting_started/scripting/gdscript/gdscript_basics.html "Info about GDScript"
[GML]: https://it.wikipedia.org/wiki/Game_Maker_Language "Wikipedia page on Game Maker Language"
[Rust]: https://www.rust-lang.org "Info about Rust"
[TorqueScript]: https://github.com/GarageGames/Torque2D/wiki/Torquescript-overview "Info about TorqueScript"
[TypeScript]: http://www.typescriptlang.org/ "Info about TypeScript"

<!-- FOSS LICENSE -->

[Apache 2.0]: http://www.apache.org/licenses/LICENSE-2.0.html "Find out more about the Apache 2.0 License"
[Artistic License 2.0]: https://www.perlfoundation.org/artistic-license-20.html "Find out more about the Artistic License 2.0"
[GPLv3]: https://choosealicense.com/licenses/gpl-3.0/ "Find out more about the GNU General Public License v3.0"
[MIT]: https://choosealicense.com/licenses/mit/ "Find out more about the MIT License"
[zlib]: https://en.wikipedia.org/wiki/Zlib_License "Find out more about the zlib License"

# Engines That Support Pixel Art

The following game engines are known to support creation of 2D games with Pixel Art, either out of the box or by tweaking settings.

## AGS (Adventure Game Studio)

- https://github.com/adventuregamestudio/ags
- https://en.wikipedia.org/wiki/Adventure_Game_Studio

AGS is a cross platform open source game engine and IDE for developing click-and-point graphic adventures, supporting Pixel Art. Initially developed in 1997, AGS is actively maintained and updated.

## Anura

- https://github.com/anura-engine/anura

Anura is the game engine used for creating the videogame _[Frogatto & Friends]_ and it's' Pixel Art oriented right out of the box. It's cross platform, open source and free for commercial and non-commercial use.

## Construct

- https://www.scirra.com/

Construct, Construct 2 and 3 support pixel art videogames creation via settings.


## Ethanon

- http://ethanonengine.com/

A cross-platform and open source 2D game engine programmable in [AngelScript] that comes with a full IDE. Compiled games can run Windows, macOS, Android and iOS. Although development seems to have stopped in 2017, the engine is stable and usable in production.

Ethanon is designed with 2D graphics and lights effects in mind: it supports pixel shaders, static and dynamic lights, shadows, normal mapping, height and specular maps, and particles — and it works well with pixel art, especially if you are looking for special light and fire effects. 


## Game Maker

- https://www.yoyogames.com/gamemaker

Game Maker is a family of commercial game engines by YoYo Games.

Game Maker supports Pixel Art.


## Godot

- https://godotengine.org

Godot is a free open source and cross platform game engine supporting both 2D and 3D graphics. It natively supports Pixel Art via custom settings, as well as isometric games. Godot ships with a full IDE.

Third party extensions are freely available to further help in developing isometric games — see the [godot-isometric-framework].

## LÖVE

- https://love2d.org

LÖVE is a free open source and cross platform 2D game engine. Pixel Art support is achived by disabling anti-aliasing and setting scaling filters to "nearest neighbour". Various Pixel Art video games have been creted with LÖVE engine.

LÖVE doesn't have an IDE, and games must be programmed in Lua language. Many [third party libraries][LÖVE libs], frameworks and resource are freely available.


## PGE

- http://wohlsoft.ru/PGE/

PGE (Platform Game Engine) if a free and open source engine and IDE for creating _Super Mario Bros._ style platform games without programming, via the [PGE Editor]'s menus. The PGE engine is 100% pixel art oriented.



<!-----------------------------------------------------------------------------
                               REFERENCE LINKS                                
------------------------------------------------------------------------------>


[Frogatto & Friends]: https://frogatto.com/ "Visit Frogatto's website"

[godot-isometric-framework]: https://github.com/mfdeveloper/godot-isometric-framework "View the project on GitHub"

[LÖVE libs]: https://love2d.org/wiki/Category:Libraries "Visit the Libraries section of LÖVE's Wiki"

[PGE Editor]: https://wohlsoft.ru/pgewiki/PGE_Editor "Visit 'PGE Editor' page on PGE's Wiki"

<!-- eof -->
