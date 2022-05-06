# TSPUD-Extract
This repository is a community-ran guide to help you extract assets from The Stanley Parable: Ultra Deluxe. Anyone is welcome to submit a PR and help make this more complete!

No assets from the game will be shared here, you have to buy the game on Steam to follow these instructions.

**⚠️ Spoilers for the game ahead ⚠️**

## Table of Contents
- [Setting Everything Up](#setting-everything-up)
- [Models / Meshes](#models--meshes)
- [Images / Textures](#images--textures)
  - [Posters](#posters)
- [Audio](#audio)
- [Linux](#linux)

# Setting Everything Up
First, be sure you have a Steam version of The Stanley Parable: Ultra Deluxe installed.

You can download many tools, but I recommend [AssetStudio](https://github.com/Perfare/AssetStudio/releases) for a free and simple way to get started.

If you use Linux, you can still follow along by doing [these steps](#linux) first.

Once installed, you can click `File` > `Load folder` and choose the `The Stanley Parable Ultra Deluxe_Data` folder, which should be in `C:\Program Files\Steam\steamapps\common\The Stanley Parable Ultra Deluxe` on Windows and `/home/$USER/.local/share/Steam/steamapps/common/The Stanley Parable Ultra Deluxe` on Linux.

Soon, everything should load, and you, in the `Asset List` tab, should now have a list of all assets in the game.

In the `Filter Type` dropdown you can choose which types of assets you want to see. You can use the search bar to search for an asset name of the filtered type.

Once you find what you want, select your assets to export and `Right Click` > `Export selected assets`, then pick a spot to export them and enjoy your newly exported assets!

# Models / Meshes

| Human-readable name | Name | Path ID | Notes |
|---|---|---|---|
|Figley / Stanlurine / Mini-Stan / Collectible | default | 234 | There is also another Figley model, but lower res |

# Images / Textures

| Human-readable name | Name | Path ID | Notes |
|---|---|---|---|
|Collectible Background (when you find a Figley)|figley_background_pattern|148|This is a tiling/repeatable texture!|
|Credits QR code for the website|credits_qr_website|99||
|Credits QR code for the Discord server|credits_qr_discord|107||

### Posters

| Human-readable name | Name | Path ID | Notes |
|---|---|---|---|
|"The end is never the end...again" poster|nc2-tsp2-poster-08-again-framed|484||
|"They're back. Two doors" poster|nc2-tsp2-poster-01-twodoors-framed|325||
|"427" poster|nc2-tsp2-poster-10-427-framed|428|The fact that the 427 poster's Path ID is 428 and not 427 hurts me.|
|"Figurine Finders Comittee" poster|poster_clues_meeting|922||
|Two Stanleys poster|nc2-tsp2-poster-09-twostanleys-framed|520||
|Brain with ride side in red|nc2-tsp2-poster-06-brain-framed|524|There is an E on this poster. I am unsure as to why. Maybe we will never know.|

# Audio
| Human-readable name | Name | Path ID | Notes |
|---|---|---|---|
|Music in the Epilogue|epilogue_mzp3|541||

# Linux
[AssetStudio](https://github.com/Perfare/AssetStudio/releases) is not available on Linux, but if you use [Wine](https://winehq.org) (be sure to use a version after `wine-5.17`, I recommend using the latest stable version), you should be able to get it running and follow the same steps in [Setting Everything Up](#setting-everything-up).
