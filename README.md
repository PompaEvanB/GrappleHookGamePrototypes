# GrappleHookGamePrototypes
Please note that this is just a prototype. Also, please wait for menu's to completely fade in other wise you may get stuck. Inside of the "nextcheck" folder is where the Sc ene Flow and Cinematics files are located.

# Scene Flow
## Scene types
The Game contains a logo screen, a main title screen, an options screen, a credit screen, and a gameplay screen. (We have actual gameplay but just or the sake of this prototype it links to an empty gmaeplay scene as to not disturb workflow.
## Communication between scenes
You have to press the options button in the main menu scene to get to the options scene. All of the buttons go to their respective scenes, and cannot be reached without the input from the previous scene.
## Reachability
All scenes are available from one another (except for the logo screen but thats not really a player scene).
## Transitions
Scenes have a coordinated fade between them. For example from the main menu to the credits scene has a coordinated fade.

# Cinematics
## Non-interactive cinematic
The games logo fades into and out of existance. Unfortunately there is no "middle" part of the animation unless you count the logo's alpha as the middle part. (please give partial credit)
## Interactive cinematic
The buttons all have hovering and pressed states. There is also a fade in between scenes. The movement of the games title logo makes the main menu feel alive.
## Choreography in code
The title's movement is created using hand coded tweens within unity.
