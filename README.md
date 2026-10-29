# Polaris Tweaks

Your **technical survival companion** for Minecraft Java **1.21.1** (Fabric): safety, quality of life and technical
tools that improve vanilla survival **without cheating**. It comes with a searchable menu, configuration profiles and a
HUD editor, all with an arctic look.

> Polaris Tweaks is closed-source software: this repository only publishes the compiled builds
> ([Releases](https://github.com/RaulDevStack/polaris-tweaks/releases)). The source code is not public.
> It is based on [Polaris Client](https://github.com/RaulDevStack/polaris-client), with the cheat modules removed.

## Philosophy

Polaris Tweaks gives you information, comfort and safety. It does not give you an unfair mechanical advantage:

- No combat modules, no flying, no speed hacks, no X-ray, no ore or chest finders, no fast break or fast place.
- Everything runs on the client and works on vanilla servers. Nothing is installed on the server.
- A few modules can still be against the rules of some servers (Free Camera, Entity ESP, Fullbright, No Fog and
  Enhanced Placement's block orientation). Free Camera and Entity ESP warn you when you turn them on. Check the rules of
  your server before using them.

## Requirements

| | |
|---|---|
| Minecraft | 1.21.1 |
| [Fabric Loader](https://fabricmc.net/use/) | 0.20.1 or newer |
| [Fabric API](https://modrinth.com/mod/fabric-api) | 0.116.17+1.21.1 or newer |
| Java | 21 |

## Installation

1. Install Fabric Loader for Minecraft 1.21.1.
2. Download `polaris-tweaks-<version>_1.21.1.jar` from the [releases](https://github.com/RaulDevStack/polaris-tweaks/releases).
3. Put the `.jar` and Fabric API in the `mods` folder of your Minecraft installation.
4. Launch the game with the Fabric profile.

## Usage

- **Right Shift** opens the menu (the key can be changed in *Settings*). There is also a **✦ Polaris** button on the
  title screen and the pause screen.
- Press **F1** to hide the HUD modules, as with the Minecraft HUD. They are also hidden while the menu is open.
- Start typing with the menu open to search for a module. Click a row to configure it; click the switch or right-click
  the row to toggle it. Every module can have its own key (toggle or hold).
- **HUD editor**: *Settings* → *Edit HUD Layout*. Drag elements around, use the mouse wheel to resize them and
  right-click to send them back to their automatic position.
- Settings are stored in `config/polaristweaks/` and support multiple profiles.

### Default keys

| Key | Action |
|---|---|
| Right Shift | Open the menu |
| N / B | Waypoints menu / quick waypoint |
| M | Open the full-screen world map (Minimap) |
| R | Sort the open inventory or chest (Inventory Sorter) |
| C | Zoom (hold) |
| Left Alt | Switch the block orientation while placing (Enhanced Placement) |

All of them can be changed in the module settings.

## Modules

### Building

| Module | What it does |
|---|---|
| Enhanced Placement | Splits the face you aim at into a center square and four border zones. Click the center to place in front of the face as usual, or a border zone to place beside the targeted block. Shows the zone, a grid and a preview of the real block shape and orientation. |
| Fixed Placement | Stops misplaced blocks when you build fast: it re-checks the face you aim at, skips clicks that cannot place anything, ignores accidental double clicks and discards stray blocks when you place in a straight line. |

**Block orientation.** Pistons, observers, droppers, stairs and similar blocks face where you look. Enhanced Placement
can make them face the side where you place them (default) or the face you aim at (hold the orientation key). Your
camera never moves: the mod only tells the server the needed look for a fraction of a second while it places the block.
Turn off *Orient Blocks* if a server does not like it.

### Technical

| Module | What it does |
|---|---|
| Spawn Rings | Rings with the mob spawning radii around you: 24, 32 and 128 blocks. |
| Redstone Inspector | Power, delay, mode and direction of the redstone block you look at, signal strength over redstone dust and the blast radius of TNT. |

### Player

| Module | What it does |
|---|---|
| Danger Alerts | Warns you before things go wrong: lava, void, creepers, mobs behind you, low health, hunger, durability and air. |
| Auto Eat | Eats automatically when you are hungry. |
| Auto Elytra | Puts on your elytra and opens it when you fall from high up. |
| Auto Totem | Keeps a totem of undying in your offhand. |
| Auto Tool | Switches to the best tool when breaking a block. |
| Auto Refill | Refills a used-up hotbar stack with another stack of the same item. |
| Auto Sprint | Always sprints when moving forward. |

### World

| Module | What it does |
|---|---|
| Waypoints | Saved points with their own menu, quick waypoints, beams and death waypoints. |
| Portal Linker | Shows where each Nether portal leads and warns about mislinked portals. |
| Auto Replant | Replants crops when you harvest them. |
| Weather & Time | Client-side time of day and weather. |

### Render

| Module | What it does |
|---|---|
| Entity ESP | Highlights entities by category with a thin colored outline and an adjustable fill, or with boxes. |
| Fullbright | Lights up dark areas without changing your brightness setting. |
| No Fog | Removes or reduces fog by type. |
| Light Level Overlay | Marks where monsters can spawn. |
| Chunk Borders | Shows chunk borders. Its slime chunk mode turns them green while you stand in a slime chunk (it reads the seed in a local world; on a server you type the seed in the module settings). |
| Item Physics | Items on the ground lie flat instead of floating and spinning. |
| Health Bar | Floating health bar over the entity you look at. |
| Connected Glass | Joins matching glass blocks and panes by removing the frame between them. |
| Clear Water, Clear Weather, Clean Screen | More transparent water, more translucent rain and snow, and fewer effects covering the screen. |
| Custom Skybox, Custom Clouds, Custom Block Highlight | Configurable skies, clouds and block outline. |

### Camera

| Module | What it does |
|---|---|
| Zoom | Zooms in while the key is held. |
| Free Camera | A camera independent from your position. |
| Orbital Camera | A third-person camera that orbits 360 degrees around you. |

### HUD

FPS, Coordinates, Speed, CPS, Day Counter, Clock, Compass, Ping, Armor Status, Potion Effects, Held Item Info, Block
Info, Target HUD, Keystrokes, Crosshair, Module List, **Death Compass** (arrow and distance back to where you died),
**TPS**, **Items Per Hour** (farm counter), **Entity Counter** (loaded entities by type, to find laggy farms) and a
**Minimap** with a full-screen world map.

### Misc

Notifications, Inventory Sorter, Inventory Tweaks (mouse wheel and Shift+drag to move items), Shulker Preview, Better
Tooltips (food values, durability, fuel), Chat Utilities and Chat Animations.

## Languages

The module names are always shown in English. Descriptions and help texts are available in English and Spanish and
follow the language of the game.

## License

Copyright (c) 2026 RaulDevStack. All rights reserved. See [LICENSE](LICENSE).
