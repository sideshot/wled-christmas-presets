# WLED Elegant Christmas Presets

Sophisticated Christmas LED presets for WLED - no garish red/green flash here. Rich jewel tones, smooth gradients, and warm candlelit vibes.

![WLED](https://img.shields.io/badge/WLED-Compatible-blue)
![LEDs](https://img.shields.io/badge/Tested_on-SK6812_RGBW-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

**Tags:** `wled-presets` `wled` `christmas` `christmas-lights` `sk6812` `rgbw` `led` `esp32` `holiday-lights`

## Why?

The default WLED Christmas presets are... not great. If you prefer the elegance of the built-in "Sunset" gradient over seizure-inducing candy cane strobes, these are for you.

## Presets Included

| Preset | Description |
|--------|-------------|
| **Christmas Ember** | Deep burgundy → orange → wine, slow gradient flow |
| **Mulled Wine** | Rich plum and burgundy with warm accents |
| **Evergreen & Gold** | Forest green + champagne gold + warm white |
| **Champagne Glow** | Warm whites with soft gold sparkles |
| **Winter Jewels** | Sapphire, teal, and ruby aurora sweep |
| **Candlelight Eve** | Heavy warm white with amber flicker |
| **Cranberry Frost** | Pink-red, berry tones with soft white |
| **Midnight Forest** | Deep emerald with forest shadows |
| **Spiced Cider** | Burnt orange, amber, warm gold |
| **Royal Velvet** | Deep purple, magenta, plum gradient |
| **Gilded Pine** | Green with gold twinkles |

Plus an **"Elegant Christmas"** playlist (preset 250) that rotates through all of them with smooth 4-second crossfades.

## Installation

1. Download `presets.json`
2. Open your WLED web interface
3. Go to **Config → Security & Updates → Backup & Restore**
4. Click **Upload presets.json**
5. Done! Find the presets in your presets menu, or activate the "Elegant Christmas" playlist

## Specs

- **Tested on:** SK6812 RGBW, 152 LEDs (~15 ft)
- **Optimized for:** RGBW strips (uses warm white channel)
- **Rotation time:** 2-3 minutes per preset
- **Transition:** 4-second crossfades
- **Vibe:** Slow, elegant, chill

Should work on any WLED-compatible strip. RGB strips will ignore the white channel but colors will still look good.

## Customization

Feel free to adjust:
- `bri` - brightness (0-255)
- `sx` - effect speed (lower = slower)
- `dur` - duration in playlist (seconds)
- `transition` - crossfade time (tenths of seconds, so 40 = 4 sec)

## License

MIT - Do whatever you want with it.

## Contributing

Found a great elegant preset? PRs welcome! Keep the vibe classy - no strobing candy canes.

---

*Made because the default Christmas presets are an assault on good taste.*

---

**Keywords:** WLED Christmas presets, elegant LED presets, SK6812 Christmas, RGBW holiday lights, classy Christmas lights, sophisticated LED effects, warm white Christmas, jewel tone LEDs, WLED playlist, ESP32 Christmas lights
