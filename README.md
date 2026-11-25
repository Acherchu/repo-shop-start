# Shop Start

![Shop Start](icon.png)

**[Download the latest version](https://github.com/Acherchu/repo-shop-start/releases/latest)**

A R.E.P.O. mod that turns the start of every run into a birthday party in the shop.

## What it does
- **Runs start in the shop**, and the shop is empty (no items for sale).
- If the shop's extraction machine is in the middle of the big room, it's removed.
- A **big birthday dining table** in the middle of the shop: a golden throne at one end, balloons, bunting, a HAPPY BIRTHDAY banner, presents, confetti and party lights.
- **Sit on the chairs**: look at a chair and press **E**. **E** or **Space** stands you up.
- **M drops a present** in front of the golden chair. Click it to open it. **M** again skips whatever is playing. M cycles through eight presents:
  1. **Purple**: a cake. It gets cut and a slice flies to every seat. Click a slice to eat it.
  2. **Yellow**: the lights go out and a summoning circle brings a **blue Scout** with a blue balloon. Any Scout you touch turns blue too, with blue drift sparks.
  3. **Pink**: a disco ball floats up and lights the room while "Happy Birthday (Disco Remix)" plays.
  4. **Black**: a bomb floats up and splits into a swarm that flies at everyone except whoever opened it. Everyone is revived and healed afterwards.
  5. **Green**: a portal frame builds itself past the table. Walk in to visit a blocky world high above the shop, with a big red button and a blue boss.
  6. **Charcoal**: the floor round the table cracks and falls away. You drop into a truck outside a haunted house: hunt the ghost with EMF, thermometer, spirit box and UV (keys 7, 8, 9, 0), then guess it in the journal (J).
  7. **Snowy white**: everyone lands on a beach in front of a huge mountain. Climb it: face rock and **left click** to grab on, **W A S D** to climb, **left click** again to lunge up, **Space** to jump off. Watch the stamina bar, rest on ledges, light campfires as checkpoints. Giant valuables are stuck all over it, and the mountain is different every time. A light beam on the summit (or the beach) brings you back.
  8. **Rainbow**: a rainbow arch over the table, and the opener's colours are corrected for red-green colourblindness until the game closes.
- **P** (host only) loads a different shop.

## Playing with friends
Everyone should have the mod. The host's mod does the shop start, the empty shop, P and spawning the Scout. Presents are shared: when anyone presses M, opens a present or eats a slice, everyone with the mod sees it, including the summoning cutscene, the disco, the haunted house and the mountain.

**Your friends see nothing?** Their mod isn't running. When the shop loads, the host's screen says who has Shop Start running and who doesn't. Everyone needs the same version, and must start R.E.P.O. from Thunderstore Mod Manager / r2modman with **Start modded**. Starting it from Steam runs the game without mods.

## Install (Thunderstore / r2modman)
1. Download `ShopStart-1.6.0.zip` from the Releases page.
2. In Thunderstore Mod Manager or r2modman, pick your R.E.P.O. profile, open **Settings > Import local mod** and choose the zip.
3. Start the game with that profile.

## Manual install
Install BepInExPack for R.E.P.O. Put `ShopStart.dll` **and** `ShopStart-Disco.wav` together in `BepInEx/plugins/ShopStart/`.

Windows Defender or Discord may warn about a new unsigned DLL. This is a false positive.
