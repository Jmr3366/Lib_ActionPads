
# Lib_ActionPads
![alt text](https://github.com/Jmr3366/Lib_ActionPads/blob/main/LibActionPads.webp?raw=true)

This is an drop in library token to be used within the Maptool VTT application.
It provides an easy to use GUI Overlay to quickly create:

- Doors Menu (video tutorial https://www.youtube.com/watch?v=svNanE0mjP4 )
  - Doors (Windows)
    - **Open, Cracked, Closed** states with option for a **Keyhole**
    - **Hinge, Slide, Lift** with option to make **Secret**
    - Each state can be **Animated**
    - **Locks** GM or **player inventoried** keys that are dropped / selected
    - With **Vision and Movement Blocking** options
    - **Interactive** and responsive **Door Actuator** options
    - ***Drawbridge*** type door
    - **Windows** 
    - **Custom Door Assets** Support (also includes generic and simple options) 
    - Simple and Generic doors are built-in and optional


- Step-On Menu (video tutorial https://www.youtube.com/watch?v=UmZwGRVfFYM )
  - Moved Under (tokens to go Opaque or Invisible)
    - **Roofs & Trees**
    - **Multiple Roof Token** support
    - **Multiple Entry & Exit** support
    - **Custom Roof, Tree Assets** Support (selected tokens can also be used)
  - Moved On To Detection
    - **Generic Trigger** moved on or off 
    - **Up / Down Stairs** in-map teleports 
  - Traps (pads can support player property checks)
    - **Generic Trap** to stop token movement
    - **Trigger Pad** additional pad to trigger trap
    - **Detection Pad** additional pad to check for trap
    - **Disable Pad** additional pad to disable a trap
    - Trigger once or many
    - Easy to reset, check who's hit
    - Animated trap support that tracks who's it (rolling boulders, shooting arrows, etc)


- Toolbox Menu
  - Sound Pads with distance detection, plays audio volume based off distance
  - Simple Vehicle Support (limited functionality)
  - GM - See All token 
    - Creates a token with common GM macros
  - Movie Maker 
    - Records and plays back to all connected players, token movement (including fade to and from black, audio support)
      - You record several "legs" of token movement to create a final movie
  - Token ID and Asset ID output    


- Config Menu
  - Doors
    - Knock, Listen, Pry, Pick, Attack, Peephole, and more
    - Locks, Locks with Keys (one or more per door, all must be used to unlock)
  - Linking
    - You can linkg doors, traps, moved over/onto
  - Sounds
    - Nearly all "actions" support mp3 audio playback
  - Custom Macros
    - Nearly all "actions" support a custom macro or evalMacro
  - Images
    - Nearly all "actions" support a change to token image
  

Many features can be linked together such that a series of actions can take place by player token movement or player interactions.
GMs retain full control

Other features that are under development include (these may not all be realized)
    
- Interaction Menu
  - Click on support
    - turn on Lights, open Dialogs, move tokens, loot items from map
  - Support to grab and drop items from the map
    - potential for interactive "buy/sell" market as player can drop an item on a pad to begin interaction workflow
  - Player backpack support so items grabbed are tracked per "looter"
  - Custom and selected tokens can be set as interaction tokens
