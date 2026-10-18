# Long Dark Co-op

Online co-op for **The Long Dark** on Steam: up to 4 players in one survival world. You host with Steam lobbies
and invite friends; there are no IP addresses to type and no ports to forward.

> **Early test build.** Expect bugs. Back up your saves before playing
> (`%LOCALAPPDATA%\Hinterland\TheLongDark`).

> **Moved here.** Long Dark Co-op used to be released from `BLUNT-Chief/LongDark-Coop`; from 0.21.0 on it comes
> from here. A game with 0.20.3 or older keeps looking at the old place and won't update by itself. **Run the setup
> below once**, and your game updates itself from here after that. Everyone you play with needs 0.21.0 or newer:
> 0.21.0 can't play together with 0.20.3.

## Install

1. Close The Long Dark.
2. Download **LongDarkCoopSetup.exe** from the [latest release](../../releases/latest) and run it.
   Windows may warn that the app is unrecognized: click **More info**, then **Run anyway**.
3. Check that the game folder it found is right, then click **Install / Update**.

Setup installs MelonLoader 0.7.3 (the mod loader), the mod, and a small updater. After that, the game updates the
mod by itself every time it starts, so you only run setup once.

Requires The Long Dark **2.55** on Steam (Windows). Works alongside other MelonLoader mods, ModSettings included.

## Play

- **Host:** on the main menu choose **CO-OP → HOST A GAME**. That opens the **lobby**, and friends can join right
  away (**INVITE FRIENDS** opens Steam's invite list). Choose a **new game** (mode and start region) or
  **continue** one of your saves, set the world options, and press **START** when everyone's ready: you all load in
  together. (You can also host a game you're already playing: **Esc → CO-OP → HOST THIS GAME**.)
- **Join:** on the main menu choose **CO-OP**; friends who are hosting are listed there. You can also accept a
  Steam invite, or right-click the host in your Steam friends list and choose **Join game**. In the lobby, pick
  your face and colour, chat, and press **READY**. Joining a game that's already running works too: your game
  loads the host's world and puts you next to them.
- **Esc → CO-OP** shows who's playing and where. The host can kick or ban players, choose who can join, and back
  up the world (it's also backed up automatically every 30 minutes).
- **Host console:** the host can press **~** (the key left of 1) for the game's own console commands, such as
  `set_time 12`, `set_weather` or `spawn_wolf`. Type `help` or `search <word>` to find commands, and Esc closes it.

The host's world is the save. Your character (inventory, condition, skills) is kept per player, so it's waiting for
you the next time you join that host.

## Options

**CO-OP → WORLD OPTIONS** (the host's choices apply to everyone):

- **Animals:** fewer, normal, more per player (a quarter more for each extra player), or x1.5, x2 or x3.
- **Respawns:** how quickly hunted-out areas fill up again.
- **Downed for, reviving takes, revived with:** how downed and revive work, or turn downed off.
- **Shared map, backups, players:** whether exploration is shared, how often the world is backed up, and how many
  can join.

**CO-OP → MY OPTIONS:** name tags, edge markers, marks (middle mouse) and teammates on the map, each on or off.

**CHARACTER** (also in the lobby): whose face your friends see on you, one of ten people from the WINTERMUTE story
mode, and your colour (name tag, map icon). Your body wears the clothes you actually have on, in their colours,
moves with recorded human motion, and shows how you're doing: a limp, a hand on broken ribs, shivering in the cold.
Teammates hold the items they actually hold, in their hands (a lit torch, flare or lantern burns and lights them up
as yours does), and you see what they throw fly. Walk up to a teammate and press
Interact to **check on** them. Faces need WINTERMUTE installed; it comes
with The Long Dark, and you can install it from the game's DLC list in Steam.

## What's shared

- Time of day, weather and wind.
- Every place looks the same for everyone: the same bodies, containers, loot and furniture.
- Doors, containers, loose items, fires, broken-down furniture, harvested plants and carcasses.
- Snow shelters, rope climbs, and lanterns, torches, flares and snares left on the ground.
- Rock caches (built, renamed, dismantled) and what's inside them.
- Cooking: a pot or skillet on a fire, what's cooking in it, and taking it out.
- Decorations (nearly anything you can pick up and move around a base) where you put them.
- Spray paint marks and ice fishing holes.
- Locks you pry open, water taken from toilet tanks, aurora power switches, and smoke from a chimney whose
  stove a teammate lit.
- You hear teammates: their footsteps and their shots, where they are. They leave footprints in the snow, and
  their breath shows in the cold.
- Wildlife: each animal runs on the nearest player's game, so wolves stalk and attack whoever they're after.
  Shooting or hitting an animal works from any player's game.
- Sleeping and passing time only start once every player chooses to.

## Finding each other

- Teammates show on the map in their own color, with their names. Someone indoors shows where they went in.
- Name tags show how far away each teammate is. A teammate off screen gets a marker at the edge of your screen
  pointing their way.
- **Middle mouse** marks the spot you're looking at for everyone, for 20 seconds.
- The map is shared: whatever anyone charts with charcoal or discovers shows up on everyone's map.
- **Give an item:** stand next to a teammate (within 3 m), open your backpack, pick the item and choose
  **GIVE TO <NAME>**. It goes straight into their backpack. Hold shift to give the whole stack.

While something takes a moment (joining, receiving the world, waiting for everyone to sleep), a small spinning
ring and a line of text show in the bottom right corner.

## Emotes, sitting and beds

- Hold the radial menu key. In co-op, the Drop Decoy arm is **EMOTES** (Drop Decoy is the first thing inside it):
  wave, come here, cheer, group hug (2 to 4 players), high five, sit, and under **MORE** point, yes and no. You see
  your own emote for a moment from behind, and everyone sees it on you.
- A group emote is offered to teammates nearby: they join with Interact, and you all stand round in a circle.
- **SIT** sits you on the chair, bench, sofa or pew in front of you, facing out of it, or cross-legged on the
  ground. Move or crouch to stand up again. What you hold stays in your hands; a lantern goes down beside you.
- Teammates see you lie in a bed while you sleep or rest in it.
- Teammates are solid: you bump into them instead of walking through.

## Dying

When you would die and a teammate is in the same area, you go down instead, with a countdown on your screen. A
teammate next to you gets a **Revive** prompt; holding Interact (the prompt shows the key) for 4 seconds revives
you. Name tags show how long a downed teammate has left.
If nobody does within 60 seconds, the game's own respawn ("Cheat Death") takes over,
and the gear you lose waits in a recovery camp where you fell. The shared save is never deleted.

**Permadeath worlds** (the host's game has Life After Death off): dying gives you a choice instead of a respawn.
**CHEAT DEATH** gets you back up where you fell, with the game's Cheat Death affliction, and everyone in the world
suffers Diminished State for two days. **SPECTATE** keeps you dead: you watch your teammates from behind them (left
or right click changes who). Leaving and joining again brings back the same choice, or the same spectating.

**Carry a downed teammate:** stand next to them and press **G** to put them over your shoulder. Their countdown
stops while you carry them, and you can take them through doors to shelter. Press **G** again to put them down.
They add 20 kg to your load, and you can't sprint while carrying.

## Uninstall

Run **LongDarkCoopSetup.exe** again and click **Uninstall**. Your saves are not touched. MelonLoader is removed only
if this setup installed it.

## Reporting a bug

Send what happened, plus this file from the game folder (Steam: right-click The Long Dark, then
**Manage → Browse local files**): `MelonLoader\Latest.log`.

---

The Long Dark belongs to Hinterland Studio Inc. This is a free, unofficial fan modification and is not affiliated
with or endorsed by Hinterland.
