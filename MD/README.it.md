# 🌿 BotanyPots - Cobblemon Integrations

Un datapack per Minecraft che aggiunge ricette per piante Cobblemon compatibili con la mod BotanyPots.

[![Versione](https://img.shields.io/badge/versione-1.0.0-blue.svg)]()
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-green.svg)](https://www.minecraft.net/)
[![Pack Format](https://img.shields.io/badge/Pack%20Format-61-lightgrey.svg)]()
[![Licenza](https://img.shields.io/badge/Licenza-MIT-yellow.svg)](../LICENSE)

[![en](https://img.shields.io/badge/lang-en-red.svg)](../README.md)
[![it](https://img.shields.io/badge/lang-it-green.svg)](README.it.md)

> 📝 **Changelog**: Vedi [CHANGELOG.it.md](CHANGELOG.it.md) per la cronologia delle versioni.

## 📋 Descrizione

Questo datapack fornisce ricette personalizzate per coltivare varie piante Cobblemon nei Vasi Botanici. Include ricette per bacche, albicocche, minte e altre colture uniche di Cobblemon, permettendoti di raccogliere oggetti Cobblemon in modo efficiente in vasi botanici compatti.

## ✨ Funzionalità

- **90 Ricette di Colture**: Ricette per bacche, albicocche, minte e altre piante Cobblemon
- **Tempi di Crescita Ottimizzati**: Velocità di crescita bilanciate per un gameplay equo
- **Drop Configurabili**: Ogni pianta fornisce oggetti con probabilità personalizzabili
- **Supporto MegaShowdown**: Ricette aggiuntive per l'addon MegaShowdown

## 🌿 Colture Supportate

### Bacche (68)
Aguav, Apicot, Aspear, Babiri, Belue, Bluk, Charti, Cheri, Chesto, Chilan, Chople, Coba, Colbur, Cornn, Custap, Durin, Enigma, Figy, Ganlon, Grepa, Haban, Hondew, Hopo, Iapapa, Jaboca, Kasib, Kebia, Kee, Kelpsy, Lansat, Leppa, Liechi, Lum, Mago, Magost, Maranga, Micle, Nanab, Nomel, Occa, Oran, Pamtre, Passho, Payapa, Pecha, Persim, Petaya, Pinap, Pomeg, Qualot, Rabuta, Rawst, Razz, Rindo, Roseli, Rowap, Salac, Shuca, Sitrus, Spelon, Starf, Tamato, Tanga, Touga, Wacan, Watmel, Wepear, Wiki, Yache

### Albicocche (7)
Nera, Blu, Verde, Rosa, Rossa, Bianca, Gialla

### Minte (6)
Blu, Ciano, Verde, Rosa, Rossa, Bianca

### Altre Piante Cobblemon (8)
Big Root, Galarica Twig, Hearty Grains, Medicinal Leek, Pep-Up Flower, Revival Herb, Saccharine Sapling, Vivichoke

### Addon MegaShowdown (1)
Max Mushroom

## 📦 Requisiti

- **Minecraft**: 1.21.4+ (o versione compatibile)
- **Mod BotanyPots**: Necessaria per il funzionamento del datapack
- **Mod Cobblemon**: Necessaria per l'esistenza degli oggetti delle colture
- **Forge/Fabric/NeoForge**: A seconda della versione di BotanyPots utilizzata

## 🔧 Installazione

1. Scarica il datapack
2. Posiziona la cartella del datapack nella cartella `datapacks` del tuo mondo
   - Percorso: `.minecraft/saves/[NomeDelTuoMondo]/datapacks/`
3. Ricarica i datapack in gioco usando `/reload` o riavvia il mondo
4. Verifica l'installazione con `/datapack list`

## 🎮 Utilizzo

1. Crea o ottieni un Vaso Botanico (dalla mod BotanyPots)
2. Aggiungi il terreno appropriato (i terreni a base di terra funzionano per tutte le piante Cobblemon)
3. Pianta qualsiasi seme o oggetto supportato
4. Attendi che il vaso faccia crescere e raccolga automaticamente i drop
5. Raccogli bacche, albicocche e altri oggetti dal vaso

## ⚙️ Configurazione

Ogni ricetta può essere personalizzata modificando i file JSON in:

```
data/botanypots/recipe/cobblemon/crops/
data/botanypots/recipe/mega_showdown/crops/
```

Parametri che puoi modificare:
- `grow_time`: Tempo in tick per il ciclo di crescita completo (1200 = 60 secondi)
- `chance`: Probabilità di drop (da 0.0 a 1.0)
- `minRolls`/`maxRolls`: Numero di oggetti droppati per raccolto

## ❓ FAQ

**D: Funziona su mondi esistenti?**
R: Sì, aggiungi il datapack al tuo mondo ed esegui `/reload`.

**D: Posso usarlo con altri datapack?**
R: In generale sì, a meno che un altro datapack non modifichi le ricette Cobblemon di BotanyPots nello stesso namespace.

**D: Funziona senza BotanyPots o Cobblemon?**
R: No. Sia BotanyPots che Cobblemon sono necessari — il datapack sarà inattivo senza di essi.

**D: Posso aggiungere supporto per altre piante Cobblemon?**
R: Sì! Aggiungi nuovi file di ricette JSON in `data/botanypots/recipe/cobblemon/crops/` seguendo il formato esistente.

**D: Cos'è la ricetta MegaShowdown?**
R: La ricetta del Max Mushroom richiede l'addon MegaShowdown. Se non lo hai, la ricetta viene semplicemente ignorata.

## 📄 Licenza

Questo progetto è rilasciato sotto la [Licenza MIT](../LICENSE). Sentiti libero di includerlo nelle tue modpack!

## 👤 Autore

**Franchino961** — [GitHub](https://github.com/Franchino961-DataPack)

## 🤝 Contributi

I contributi sono benvenuti!
- Apri una [Issue](../../issues) per segnalare bug o suggerire nuove ricette
- Apri una [Pull Request](../../pulls) per contribuire

## 💬 Supporto

Se riscontri problemi o hai domande:
- Controlla le [issue esistenti](../../issues)
- Crea una nuova issue includendo: versione di Minecraft, versione di BotanyPots e versione di Cobblemon

## 🔗 Link

- [Mod BotanyPots](https://www.curseforge.com/minecraft/mc-mods/botany-pots)
- [Mod Cobblemon](https://cobblemon.com)

## 📝 Changelog

Vedi [CHANGELOG.it.md](CHANGELOG.it.md) per la cronologia completa delle versioni.

---

> ⚠️ **Nota**: Questo datapack richiede l'installazione di entrambe le mod BotanyPots e Cobblemon. Non funzionerà in Minecraft vanilla.