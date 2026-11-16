# FF11 Limit Break

FF11 Limit Break is a Windows launcher for Final Fantasy XI players who use Windower and high-resolution texture mods. It increases the game's internal asset pool to 1 GiB at startup, giving the client more room to load textures and other assets.

<img width="2112" height="1584" alt="Screenshot 2026-11-13 052625" src="https://github.com/user-attachments/assets/b31c3f84-fb1d-4fb0-ad1b-7564fbb6dbf7" />

## What it can help with

A heavily modded client can run out of space in its asset pool. This can cause black or missing scenery and, in some cases, crashes. Limit Break can help when the asset pool is the cause. Other causes of crashes and rendering issues can still occur.
The game can still exhaust the memory pool without custom DAT mods installed, so this can still help with that too.

## Getting started

1. Download a build from **Releases** and extract the entire ZIP.
2. Open **FF11 Limit Break.exe**, select your PlayOnline and FFXI paths, and add your Windower installation.
3. Use **Prepare addon** and follow the included setup instructions. PlayOnline requires the **Large Address Aware (4 GB)** patch.
4. Launch Windower through Limit Break and start PlayOnline. Check for **Armed** before logging in, then look for the **1024 MiB verified** message in-game.

FF11 Limit Break does not have to stay running in the background, it only needs to be used to arm a client during the transition from Windower to Playonline.

The experimental build also supports monitoring clients started from Windower shortcuts, the exe or through another launcher such as Forest.

## Credits and licence

Based on [FFXI Texture Forge](https://github.com/finalpantasy/ffxi-texture-forge) by finalpantasy. See [LICENSE](LICENSE) for the MIT licence.
