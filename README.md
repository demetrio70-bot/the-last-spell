# Oraculum Expanded & Other Improvements

A modular collection of **The Last Spell** gameplay-balance and quality-of-life improvements. Designed to extend Oraculum progression and refine gameplay while keeping the game's core experience recognizable.

This is an **unofficial community project**, not affiliated with Ishtar Games or The Arcade Crew.

## Installation (Windows / Steam)

**Required:** A working installation of **BepInEx 5 (64-bit)** for The Last Spell. These are BepInEx plugins, **not standalone Steam Workshop files**.

1. Install BepInEx 5 (64-bit) into your *The Last Spell* game folder, if it is not installed already. Run the game once and close it. Check that the folder `BepInEx/plugins/` exists.
2. On this GitHub page, click **Code → Download ZIP**, then extract the archive.
3. Open the extracted `plugins` folder and **copy its 12 `.dll` files** to your game's `BepInEx/plugins/` folder. For Steam: right-click *The Last Spell* → **Manage → Browse local files** to locate the game folder.
4. Remove old versions of these same mods to avoid loading duplicate plugins, then launch the game.

**Important:** Copy the DLLs *inside* the `plugins` folder into `BepInEx/plugins/`. Do not copy a nested `plugins/plugins/` folder. You do not need to compile anything.

**Uninstall:** Remove these same DLL files from `BepInEx/plugins/`.

### Included plugins

| DLL | Purpose |
| --- | --- |
| `AttributeRarity.dll` | Refines Oraculum attribute-rarity progression |
| `AttributeRerolls.dll` | Expands attribute reroll progression |
| `AttributeWeight.dll` | Rebalances the weights of individual attributes |
| `BallistaKillReport.dll` | Optional ballista kill-information display |
| `BallistaUpgrade.dll` | Expanded ballista upgrade progression |
| `FairCorpses.dll` | Expanded corpse-generation progression |
| `ItemRarity.dll` | Refines Oraculum equipment-rarity progression |
| `ItemWeight.dll` | Rebalances equipment-model weights |
| `ProtanDangerOverlay.dll` | Optional color-vision-accessibility overlay |
| `SharedExperienceBalance.dll` | Oraculum progression for shared experience |
| `ShopRefreshPricing.dll` | Oraculum progression for shop refresh costs |
| `ShopVisualSort.dll` | Visual category sorting for the shop |

### Notes

- The pack is intended to contain **only the 12 DLLs shown above**; the developer console and experimental OraculumRunTracker diagnostic are **not included**.
- This bundle was prepared from a supplied set of working mod binaries. Compatibility with other gameplay overhauls is not guaranteed.
- Some plugins change game balance and/or Oraculum progression. Consider backing up save files before installing.
- BepInEx is a separate third-party dependency and is **not included**.
- Subscribing to a Steam Workshop page alone **does not install these DLLs**. Please follow the installation steps above.

## Steam Workshop description (copyable)

**Oraculum Expanded & Other Improvements**

A modular collection of Oraculum upgrades, balance adjustments and quality-of-life enhancements for *The Last Spell*.

**Manual installation is required:**
1. Install BepInEx 5 (64-bit) for The Last Spell.
2. Download the files from this GitHub repository: https://github.com/demetrio70-bot/the-last-spell
3. Open the downloaded archive's `plugins` folder and copy all 12 `.dll` files into your game's `BepInEx/plugins/` folder.
4. Remove old duplicate versions of these plugins and start the game.

**Note:** Steam Workshop subscription alone does not install the gameplay DLLs. Please read the GitHub README for the full list of included mods and troubleshooting notes.

*Unofficial community project. Not affiliated with Ishtar Games or The Arcade Crew.*
