# 🌿 BotanyPots - Cobblemon Integrations

A Minecraft datapack that adds Cobblemon plant recipes for the BotanyPots mod.

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)]()
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-green.svg)](https://www.minecraft.net/)
[![Pack Format](https://img.shields.io/badge/Pack%20Format-61-lightgrey.svg)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[![en](https://img.shields.io/badge/lang-en-red.svg)](README.md)
[![it](https://img.shields.io/badge/lang-it-green.svg)](Docs/README.it.md)

> 📝 **Changelog**: See [CHANGELOG.en.md](Docs/CHANGELOG.en.md) for version history.

## 📋 Description

This datapack provides custom recipes for growing various Cobblemon plants in Botany Pots. It includes recipes for berries, apricorns, mints, and other unique Cobblemon crops, allowing you to efficiently farm Cobblemon items in compact botany pots.

## ✨ Features

- **90 Crop Recipes**: Recipes for berries, apricorns, mints and other Cobblemon plants
- **Optimized Growth Times**: Balanced growth rates for fair gameplay
- **Configurable Drops**: Each plant provides items with customizable chances
- **MegaShowdown Support**: Additional recipes for the MegaShowdown addon

## 🌿 Supported Crops

### Berries (68)
Aguav, Apicot, Aspear, Babiri, Belue, Bluk, Charti, Cheri, Chesto, Chilan, Chople, Coba, Colbur, Cornn, Custap, Durin, Enigma, Figy, Ganlon, Grepa, Haban, Hondew, Hopo, Iapapa, Jaboca, Kasib, Kebia, Kee, Kelpsy, Lansat, Leppa, Liechi, Lum, Mago, Magost, Maranga, Micle, Nanab, Nomel, Occa, Oran, Pamtre, Passho, Payapa, Pecha, Persim, Petaya, Pinap, Pomeg, Qualot, Rabuta, Rawst, Razz, Rindo, Roseli, Rowap, Salac, Shuca, Sitrus, Spelon, Starf, Tamato, Tanga, Touga, Wacan, Watmel, Wepear, Wiki, Yache

### Apricorns (7)
Black, Blue, Green, Pink, Red, White, Yellow

### Mints (6)
Blue, Cyan, Green, Pink, Red, White

### Other Cobblemon Plants (8)
Big Root, Galarica Twig, Hearty Grains, Medicinal Leek, Pep-Up Flower, Revival Herb, Saccharine Sapling, Vivichoke

### MegaShowdown Addon (1)
Max Mushroom

## 📦 Requirements

- **Minecraft**: 1.21.4+ (or compatible version)
- **BotanyPots Mod**: Required for the datapack to function
- **Cobblemon Mod**: Required for crop items to exist
- **Forge/Fabric/NeoForge**: Depending on your BotanyPots version

## 🔧 Installation

1. Download the datapack
2. Place the datapack folder in your world's `datapacks` folder
   - Location: `.minecraft/saves/[YourWorldName]/datapacks/`
3. Reload datapacks in-game using `/reload` or restart the world
4. Verify installation with `/datapack list`

## 🎮 Usage

1. Craft or obtain a Botany Pot (from the BotanyPots mod)
2. Add appropriate soil (dirt-based soils work for all Cobblemon plants)
3. Plant any supported seed or item
4. Wait for the pot to grow and automatically harvest drops
5. Collect berries, apricorns, and other items from the pot

## ⚙️ Configuration

Each crop recipe can be customized by editing the JSON files in:

```
data/botanypots/recipe/cobblemon/crops/
data/botanypots/recipe/mega_showdown/crops/
```

Parameters you can adjust:
- `grow_time`: Time in ticks for full growth cycle (1200 = 60 seconds)
- `chance`: Drop probability (0.0 to 1.0)
- `minRolls`/`maxRolls`: Number of items dropped per harvest

## ❓ FAQ

**Q: Does this work on existing worlds?**
A: Yes, add the datapack to your world and run `/reload`.

**Q: Can I use this with other datapacks?**
A: Generally yes, unless another datapack modifies BotanyPots Cobblemon recipes in the same namespace.

**Q: Does this work without BotanyPots or Cobblemon?**
A: No. Both BotanyPots and Cobblemon are required — the datapack will be inactive without them.

**Q: Can I add support for other Cobblemon plants?**
A: Yes! Add new JSON recipe files in `data/botanypots/recipe/cobblemon/crops/` following the existing format.

**Q: What is the MegaShowdown recipe?**
A: The Max Mushroom recipe requires the MegaShowdown addon. If you don’t have it, the recipe is simply ignored.

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to include it in your modpacks!

## 👤 Author

**Franchino961** — [GitHub](https://github.com/Franchino961-DataPack)

## 🤝 Contributing

Contributions are welcome!
- Open an [Issue](../../issues) to report bugs or suggest new recipes
- Open a [Pull Request](../../pulls) to contribute

## 🗨️ Support

If you encounter any issues or have questions:
- Check [existing issues](../../issues)
- Create a new issue including: Minecraft version, BotanyPots version and Cobblemon version

## 🔗 Links

- [BotanyPots Mod](https://www.curseforge.com/minecraft/mc-mods/botany-pots)
- [Cobblemon Mod](https://cobblemon.com)

## 📝 Changelog

See [CHANGELOG.en.md](Docs/CHANGELOG.en.md) for full version history.

---

> ⚠️ **Note**: This datapack requires both the BotanyPots mod and Cobblemon mod to be installed. It will not work in vanilla Minecraft.
