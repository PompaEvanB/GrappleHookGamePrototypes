# Final Game
## Core Requirements
### Note
WebGL Unity Tiles have an issue loading, this is an in engine problem not dependant on us and this is a completely visual bug.

### [project archive] The team has submitted a self-contained archive of their design and deployment work (e.g. a repository on GitHub). This archive contains some documentation (e.g. a README.md file) that is immediately visible even to non-technical audiences.
That is this readme hello :-)

### [main game] The documentation links to a deployed version of the main game compatible with mobile browsers.
https://anthony-molle.itch.io/grabble (Password CMPM120)

### [prototypes] The documentation links to the deployed version of three playable prototypes (core gameplay, scene flow, and cinematics). (They don't need to be deployed on the same platform as the main game, but the audience needs to be able to play them by simply clicking a direct link to them.)
Scene Flow and Cinematics: https://pompaevanb.github.io/GrappleHookGamePrototypes/nextcheck/index.html
Core Gameplay: https://anthony-molle.itch.io/grabble
(The Password to the coregameplay is CMPM120)


### [theme] The documentation describes how the theme of "nearby in space, but distant in time" was addressed in the main game's design. (One sentence would be sufficient, but try to keep the description to a single paragraph even if you want to give more detail.)
Our Grappling mechanic involves the grapple hook recalling to the player over time. The player cant use the grappling hook again until it is completely recalled. So although the hook may be nearby, it is distant in the time until you can use it again. 

### [selectable requirements] The documentation describes which of the three selectable requirements your team is attempting to satisfy.
Data-driven experience progression
Procedural graphics
Advanced visual assets

### [contributor credits] The documentation identifies all of the direct contributors to the code and their assigned roles (e.g. "testing lead")
Anthony Molle
Zane Chen Shan
Mason Huang
Evan Pompa

### [asset credits] If the team has built there game using assets created by anyone else (even if those assets were modified before inclusion in the game), the upstream source of those assets should be credited in the documentation as well.
- Music: https://opengameart.org/content/space-boss-battle-theme
- Grapple Sound Effect: https://freesound.org/people/TheFlyFishingFilmmaker/sounds/641696/
- Font: https://www.dafont.com/tallboy.font


### The game was developed using a tool where most game rules are expressed in hand-typed textual program code (e.g. JavaScript or C#).
The Game was developed in C#

### The team's repository directly shows contributions from several team members.
We had two githubs for this project, here is a link to the otherone to see all of the commits. https://github.com/AnthonyMolle/GrappleHookGame

### [self-teaching] The player is capable of learning to play from within the game, without consulting outside instructions. (For example, the game's website might say "a touchscreen is recommended for playing this game" but it should not say "tap and drag on the left side of side of the screen to make your character walk". This message should instead be conveyed inside of the game so that the player can learn this without leaving the full-screen mode.)
There is an ingame tutorial screen on the tutorial tab.

# Selectable Requirements
## Data-driven experience progression
player high score data is stored in a json to be used and referenced later
## Procedural graphics
All of our game tiles are procedurally generated in tile sets at random!
## Advanced visual assets
All of the particle systems are file-based visual assets that aren't images.
