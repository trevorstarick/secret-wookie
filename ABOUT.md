#SECRET-WOOKIE
The game takes place on a planet in a space station, hundreds of years abandoned. The player crash lands on the planet and takes refuge in an abandoned wing of the upper levels of the space station. 

##Description and inspiration
The game will be of the adventure/survival/sandbox/platformer genre and can be played in many different ways. Players can either decide to play it in a Diablo style where you run through the lower levels of the station, leveling up and equipping yourself with better weapons/tools. Players can also play it in a Minecraft/Terraria style where they loot the surrounding area for tools/weapons/materials to make their base stronger or build/unlock new parts of the station. Players can also play the game in an EVE style where they build a spacecraft and fly around looting other bases/planets and upgrading their ship. Inspirations for the game will be mostly from FTL/EVE for the space aspects of the game, Terraria/Minecraft for the sandbox/survival aspects of the game and, Diablo for the dungeon crawler aspects of the game. The probability of references to these inspirations and other games/pop culture will be high but these references will not be so many to disturb the player’s experience.

##Release model
The initial Alpha release will be a playable model of the Beta/Final release. Players will be able to move around, explore, craft and fight. Releases closer to Beta will include the ability to start upgrading small sections of the station and possible the construction of a ship. Beta will include the ability to fully upgrade the station and the construction of a ship. 

##Space tavel and Multiplayer
Space travel will allow players to explore new planets to get new resources or tools. Players will also be able to use space travel to discover other players in the full release, which will include multiplayer. For players to use Multiplayer they must first opt-in. Opting-in allows other players to discover their planet and make contact. Players can either ally with others or raid each other’s bases. Other player’s planets can only be accessed by allied players (at all times) or by neutral/enemy players (when a player is on that planet and is either the owner or part of a colony). Allied players can trade resources or tools and invite other players to their planet to start a colony. Cross platform multiplayer may be added in the future allowing console owners to play with non-console (PC/Mac/Linux) owners.

##World generation and game design
###WORLD GENERATION
World generation has two possibilities:

######*WORLD GEN A:*

*The first two floors are accessible/played like Terraria in a 2D platformer style to make it easier to access building, upgrading and crafting. All floors below are procedurally generated isometric 2D dungeons.*

######*WORLD GEN B:*

*The whole world is a procedurally generated isometric 2D space.*

######*WORLD GEN C:*

*The whole world is done in Limbo's style of paralax scrolling and contrast meets Terraria's 2D platformer style.*

Procedural dungeon generation algorithms are explained thoroughly in the following link as well as a good example written in JavaScript:
	http://redd.it/1dlwc4
###DESIGN
NPC's design, building design, and colours are all randomly generated. As the player delves deeper into the planet/space station the player can uncover new wings, which have new resources, tools and NPCs. Resources and tools can be used to upgrade and rebuild the first two floors or craft new items. NPCs can be hostile, neutral or passive. Hostile NPCs will attack on sight; neutral NPCs can be friendly until provoked. Both will drop experience and/or loot on getting killed. Neutral and passive NPC's can be used to barter for new items, resources or quests.  Experience is given for multiple tasks such as exploring, building and fighting. Experience is used to increase skill levels. 
###ENDGAME
Endgame is when the user dies, upgrades the base enough to live or builds a ship to leave the planet. If the player builds a ship, they have a chance to win (ship survives and gets back home) or the ship explodes, runs out of fuel or lands on another planet. The positive endgames (upgrade the base or builds a ship) allow the user the option to continue their current game or start a new one. [New Game+?]

##Soundtrack
The soundtrack for the game will be in chiptunes and inspired by FTL, Portal, Deus Ex and Phantasy Star Online. The ambient soundtrack will change based on where the player is. For example, if the player is in the station the soundtrack will sound a certain way. If the player is outside the station or in the lower levels the soundtrack will change to compliment the special mood. The following link is the inspiration for the whole game and this should be reflected in the soundtrack: 	https://soundcloud.com/fuckmylife/moog-bass-modular

##Art
The art style of the game will be 8/16 bit pixel art. The genre will be space themed but has the potential to differ based on how planets are generated. There is the possibility that stations are textured based on the surrounding resources and colours. All planetary colour schemes will be randomly generated from an algorithm so that there are no clashing colours. As players explore more of the station the textures will start to change to a more degradated style to compliment the fact that the station has been abandoned for some time.

##Programing and tech stuff
The game will be coded in either a combination of SDL and OpenGL or using the Unity framework/SDK. It will be primarily developed for the PC/Mac demographics with the possibility of Linux support. After the major part of the game is developed a team may start working on mobile or console versions/ports of the game. The ability to interact between console and PC/Mac players would be an amazing feature but would require both the console and PC/Mac players to interact through a third-party service. Users may have the option to save one or more saves on the cloud and this would be required for the planned multiplayer features. The mobile players would have a ‘lite’ version of the game similar to what Minecraft PE and Terraria Mobile are to their desktop counterparts. Native support for controllers (Xbox 360 and SNES USB) will be available as well as the possibility for the Oculus Rift however the usability will be limited as this is a 2D game and isometric 2D landscapes converted to 3D are not that amazing. Controls will be ‘simple’ and similar to those explained in the following link:
	http://youtu.be/8FpigqfcvlM
