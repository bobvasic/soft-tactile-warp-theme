# Soft Tactile Warp Dark

A premium neumorphic dark theme for [Warp Terminal](https://app.warp.dev/referral/4YXPLX) featuring warm, creamy-pastel tones optimized for extended coding sessions. Designed with eye comfort and visual elegance in mind.

## Design Philosophy

This theme embraces **neumorphism** and **warm pastel design** principles:

- **Rich warm brown background** (`#2b2520`) - deeper than standard dark themes
- **Creamy taupe accents** with coffee/chocolate inspired palette
- **Reduced eye strain** through warm color temperature
- **Professional elegance** suitable for enterprise environments
- **Monochromatic harmony** maintaining excellent readability
- **Long-session optimized** for comfortable extended programming

## Theme Collection — Three Variations, One Philosophy

### 🌙 **Dark** — *Midnight Espresso*

**Background:** `#2b2520` — Rich warm brown  
**Accent:** `#9b8b7e` — Creamy taupe  
**Foreground:** `#e5d5c5` — Soft beige  

Rich warm brown background with creamy taupe accents. Designed for extended coding sessions and late-night work. Reduces eye strain through deep, cozy coffee-chocolate tones.

**Perfect for:** Long hours • Low-light environments • Reducing blue light exposure • Late-night coding

---

### ☀️ **Light** — *Vanilla Latte*

**Background:** `#f5f0e8` — Creamy vanilla  
**Accent:** `#a68a7d` — Warm terracotta  
**Foreground:** `#4a3f38` — Dark coffee  

Soft creamy vanilla background with warm terracotta accents. Professional elegance meets comfortable brightness. A sophisticated alternative to harsh white themes.

**Perfect for:** Daytime work • Bright offices • Client demos • Professional presentations

---

### ☕ **Cream** — *Sun-Kissed Cappuccino*

**Background:** `#F2E8D9` — Sun-tanned cream  
**Accent:** `#BF9969` — Golden coffee crema  
**Foreground:** `#5A4A3A` — Rich espresso  

Warm sun-tanned cream background with golden coffee crema accents. Evokes Mediterranean warmth—like coffee basking in afternoon sunlight. The coziest light theme imaginable.

**Perfect for:** All-day comfort • Warm aesthetics lovers • Eye-candy seekers • Creative work

---

**All variants feature:**
- ✨ Zero cool tones — Pure warm palette
- 🎨 Neumorphic design principles
- 💼 Enterprise-grade aesthetics
- 👁️ Eye-comfort optimized
- 🚀 Production-ready quality

## Installation

### From Official Warp Themes (Coming Soon)

Once merged into the official repository, these themes will be available directly in Warp:
- `Settings > Appearance > Current Theme`
- Search for "Soft Tactile Warp"

### Manual Installation (Current)

**macOS:**
```bash
mkdir -p $HOME/.warp/themes/
cd $HOME/.warp/themes/
curl -O https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_dark.yaml
curl -O https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_light.yaml
curl -O https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_cream.yaml
```

**Linux:**
```bash
mkdir -p ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/
cd ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/
wget https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_dark.yaml
wget https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_light.yaml
wget https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_cream.yaml
```

**Windows (PowerShell):**
```powershell
New-Item -Path "$env:APPDATA\warp\Warp\data\themes\" -ItemType Directory -Force
cd "$env:APPDATA\warp\Warp\data\themes\"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_dark.yaml" -OutFile "soft_tactile_warp_dark.yaml"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_light.yaml" -OutFile "soft_tactile_warp_light.yaml"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_cream.yaml" -OutFile "soft_tactile_warp_cream.yaml"
```

Restart Warp Terminal, then activate via `Settings > Appearance > Current Theme`

## Color Specifications

### Dark Theme
| Element | Hex Code | Description |
|---------|----------|-------------|
| Background | `#2b2520` | Rich warm brown |
| Foreground | `#e5d5c5` | Creamy beige text |
| Accent | `#9b8b7e` | Creamy taupe |
| Cursor | `#b5a798` | Soft sand highlight |

### Light Theme
| Element | Hex Code | Description |
|---------|----------|-------------|
| Background | `#f5f0e8` | Creamy vanilla |
| Foreground | `#4a3f38` | Dark coffee text |
| Accent | `#a68a7d` | Warm terracotta |
| Cursor | `#8e7365` | Rich clay accent |

### Cream Theme
| Element | Hex Code | Description |
|---------|----------|-------------|
| Background | `#F2E8D9` | Sun-tanned cream |
| Foreground | `#5A4A3A` | Rich espresso |
| Accent | `#BF9969` | Golden coffee crema |
| Cursor | `#BF9969` | Golden crema |

## Key Features

✅ **Eye Comfort First** - Warm color temperature reduces blue light exposure  
✅ **Extended Session Ready** - Designed for 8+ hour coding marathons  
✅ **Enterprise Professional** - Elegant aesthetics suitable for client demos  
✅ **Creamy Pastel Palette** - Coffee/chocolate inspired warm tones  
✅ **High Contrast Text** - Excellent readability without harsh edges  
✅ **ANSI Color Support** - Full terminal color compatibility  
✅ **Neumorphic Design** - Soft, tactile visual language  
✅ **Multiple Variants** - Dark, Light, and Cream options included

## Contributing

Contributions and feedback are welcome! Open an issue or submit a pull request at:
https://github.com/bobvasic/soft-tactile-warp-theme

## Official Warp Theme Submission

This theme is **ready for submission** to the [official Warp themes repository](https://github.com/warpdotdev/themes).

### Submission Checklist

- [x] Follows Warp YAML theme specification
- [x] Unique neumorphic warm pastel design
- [x] Professional naming convention
- [x] Multiple variants included
- [x] Comprehensive documentation
- [x] MIT License for open source
- [x] Optimized for eye comfort and long sessions

### For Warp Team Review

**Why This Theme Collection Matters:**

Soft Tactile Warp is the **first comprehensive warm-toned theme family** for Warp Terminal. While the existing theme library excels with cool blue/gray palettes, there's a notable gap for developers seeking warm, eye-comfort optimized alternatives.

**Unique Value Proposition:**
- 🌟 **Market Gap:** First warm brown/coffee-toned theme collection in Warp
- 👁️ **Health-Focused:** Reduces blue light exposure for extended coding sessions (8+ hours)
- 🎨 **Neumorphic Design:** Brings soft UI principles to terminal aesthetics
- 💼 **Enterprise Ready:** Professional elegance suitable for client-facing work
- ☕ **Psychological Comfort:** Evokes warmth and coziness vs cold, clinical feel

**Target Audience:**
- Developers working late-night hours seeking eye-friendly themes
- Enterprise teams prioritizing developer wellness and comfort
- Design-conscious professionals wanting premium aesthetics
- Users who find traditional blue/gray themes too cold or sterile
- Creative developers seeking warm, inviting workspace environments

**Competitive Differentiation:**

Most terminal themes (including Warp's defaults) lean heavily on cool tones. This collection introduces:
- **Warm brown** instead of cold gray/blue
- **Coffee/chocolate** palette instead of neon/cyberpunk
- **Mediterranean warmth** instead of arctic minimalism
- **Three cohesive variants** covering all lighting scenarios

**Production Quality:**
- ✅ Follows Warp YAML specification precisely
- ✅ Tested across Linux, macOS, Windows
- ✅ All 16 ANSI colors carefully calibrated
- ✅ Zero cool tones — exclusively warm palette
- ✅ Professional documentation and presentation
- ✅ MIT licensed for community contribution

## Compatibility

- ✅ Warp Terminal (all versions)
- ✅ Linux, macOS, Windows
- ✅ All shell environments (bash, zsh, fish, etc.)

## License

MIT License - Free for personal and commercial use

## Credits

**Created by:** [Jelena @ CyberLink Security](https://github.com/jelenastricak)  
**Design Inspiration:** Neumorphic UI principles and tactile design patterns  
**For:** Warp Terminal Community

## Support

For issues or customization requests:
- Open an issue on GitHub: https://github.com/bobvasic/soft-tactile-warp-theme/issues
- Email: info@cyberlinksec.com
- Warp Community: https://discord.gg/warpdotdev

---

**Enjoy your soft, tactile terminal experience! 🎨✨**
