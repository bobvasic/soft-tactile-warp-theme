![Soft Tactile](https://github.com/bobvasic/soft-tactile-warp-theme/blob/c114fe75b603414d39b81c0b083ef9d8b129504b/theme_thumbnail.png)

# Soft Tactile Warp Theme Collection

A premium neumorphic theme collection for [Warp Terminal](https://app.warp.dev/referral/4YXPLX) featuring warm, coffee-inspired tones optimized for extended coding sessions. Designed with eye comfort, visual elegance, and professional aesthetics in mind.

## Design Philosophy

This collection embraces **neumorphism**, **claymorphism**, and **warm pastel design** principles:

- **Warm coffee/chocolate color palette** - zero cool tones
- **Reduced eye strain** through warm color temperature
- **Professional elegance** suitable for enterprise environments
- **Monochromatic harmony** maintaining excellent readability
- **Long-session optimized** for comfortable extended programming
- **Comprehensive coverage** for all lighting conditions and preferences

## Theme Collection — Four Variations, One Philosophy

### 🌙 **Dark** — *Midnight Espresso*

**Background:** `#3a3230` — Rich warm brown (claymorphic)  
**Accent:** `#a89c91` — Creamy taupe  
**Foreground:** `#ede0d2` — Soft beige  
**Details:** Darker

Rich warm brown background with creamy taupe accents and claymorphic depth. Designed for extended coding sessions and late-night work. Reduces eye strain through deep, cozy coffee-chocolate tones with soft clay-like texture. Features carefully calibrated ANSI colors that maintain warmth across all terminal output.

**Technical Highlights:**
- Claymorphic design with tactile depth
- Optimized contrast ratio for extended readability
- All 16 ANSI colors harmonized in warm spectrum
- Zero blue light exposure from color temperature

**Perfect for:** Long hours • Low-light environments • Reducing blue light exposure • Late-night coding

---

### ☀️ **Light** — *Vanilla Latte*

**Background:** `#f5f0e8` — Creamy vanilla  
**Accent:** `#a68a7d` — Warm terracotta  
**Foreground:** `#4a3f38` — Dark coffee  
**Details:** Lighter

Soft creamy vanilla background with warm terracotta accents. Professional elegance meets comfortable brightness. A sophisticated alternative to harsh white themes that won't blind you in bright environments. The warm vanilla base provides excellent readability while maintaining the signature warmth of the collection.

**Technical Highlights:**
- Professional-grade contrast for presentations
- Warm terracotta accents prevent sterile appearance
- Optimized for bright office lighting
- Maintains eye comfort in high-brightness scenarios

**Perfect for:** Daytime work • Bright offices • Client demos • Professional presentations

---

### ☕ **Cream** — *Sun-Kissed Cappuccino*

**Background:** `#F2E8D9` — Sun-tanned cream  
**Accent:** `#BF9969` — Golden coffee crema  
**Foreground:** `#5A4A3A` — Rich espresso  
**Details:** Lighter

Warm sun-tanned cream background with golden coffee crema accents. Evokes Mediterranean warmth—like coffee basking in afternoon sunlight. The coziest light theme imaginable, perfectly balanced between vanilla light and deep chocolate dark themes. Rich espresso foreground provides exceptional contrast against the sun-kissed cream backdrop.

**Technical Highlights:**
- Golden coffee crema creates visual interest
- Mediterranean-inspired warm palette
- Perfect middle ground between light and dark
- Rich espresso text ensures crisp readability

**Perfect for:** All-day comfort • Warm aesthetics lovers • Eye-candy seekers • Creative work

---

### 🍫 **Choco** — *Choco Latte*

**Background:** `#2d1f18` — Deep chocolate brown + **chocolate.png texture**  
**Accent:** `#A68A7D` — Warm terracotta  
**Foreground:** `#E5D5C5` — Creamy beige  
**Details:** Lighter

Dark theme variant with rich chocolate tones extracted from real chocolate imagery. Features an authentic chocolate texture background image for a premium, commercial chocolate look and feel. All-night comfort optimized for late-night coding with warm chocolate aesthetic. Perfect balance between darkness and warmth with authentic cocoa coloring.

**Technical Highlights:**
- **Background image:** Real chocolate texture (chocolate.png) at 100% opacity
- Colors scientifically extracted from actual chocolate photography
- Deep chocolate base (#2d1f18) for optimal darkness with warmth
- Creamy beige text provides luxurious contrast
- Commercial-grade aesthetic inspired by premium chocolate branding

**Perfect for:** Late-night coding • Deep focus sessions • Chocolate aesthetic lovers • Extended comfort • Premium visual experience

---

**All four variants feature:**
- ✨ Zero cool tones — Pure warm palette
- 🎨 Neumorphic & claymorphic design principles
- 💼 Enterprise-grade aesthetics
- 👁️ Eye-comfort optimized for 8+ hour coding sessions
- 🚀 Production-ready quality
- ☕ Coffee/chocolate inspired color harmony
- 🎯 Scientifically calibrated ANSI color palettes
- 🌡️ Warm color temperature throughout (no blue light)
- 📐 Optimized contrast ratios for readability

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
curl -O https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_choco.yaml
# Download chocolate background image for Choco theme
curl -O https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/chocolate.png
```

**Linux:**
```bash
mkdir -p ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/
cd ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/
wget https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_dark.yaml
wget https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_light.yaml
wget https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_cream.yaml
wget https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_choco.yaml
# Download chocolate background image for Choco theme
wget https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/chocolate.png
```

**Windows (PowerShell):**
```powershell
New-Item -Path "$env:APPDATA\warp\Warp\data\themes\" -ItemType Directory -Force
cd "$env:APPDATA\warp\Warp\data\themes\"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_dark.yaml" -OutFile "soft_tactile_warp_dark.yaml"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_light.yaml" -OutFile "soft_tactile_warp_light.yaml"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_cream.yaml" -OutFile "soft_tactile_warp_cream.yaml"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/soft_tactile_warp_choco.yaml" -OutFile "soft_tactile_warp_choco.yaml"
# Download chocolate background image for Choco theme
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/bobvasic/soft-tactile-warp-theme/main/chocolate.png" -OutFile "chocolate.png"
```

Restart Warp Terminal, then activate via `Settings > Appearance > Current Theme`

## Color Specifications

### Dark Theme
| Element | Hex Code | Description |
|---------|----------|-------------|
| Background | `#3a3230` | Rich warm brown (claymorphic) |
| Foreground | `#ede0d2` | Creamy beige text |
| Accent | `#a89c91` | Creamy taupe |
| Cursor | `#c2b4a5` | Soft sand highlight |

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

### Choco Theme
| Element | Hex Code | Description |
|---------|----------|-------------|
| Background | `#2d1f18` | Deep chocolate brown |
| Background Image | `chocolate.png` | Real chocolate texture (100% opacity) |
| Foreground | `#E5D5C5` | Creamy beige |
| Accent | `#A68A7D` | Warm terracotta |
| Cursor | `#B5A798` | Soft sand |

## Key Features

✅ **Eye Comfort First** - Warm color temperature reduces blue light exposure  
✅ **Extended Session Ready** - Designed for 8+ hour coding marathons  
✅ **Enterprise Professional** - Elegant aesthetics suitable for client demos  
✅ **Creamy Pastel Palette** - Coffee/chocolate inspired warm tones  
✅ **High Contrast Text** - Excellent readability without harsh edges  
✅ **ANSI Color Support** - Full terminal color compatibility  
✅ **Neumorphic Design** - Soft, tactile visual language  
✅ **Multiple Variants** - Dark, Light, Cream, and Choco options included  
✅ **Claymorphic Depth** - Warm clay-like texture and depth  
✅ **Premium Textures** - Choco theme features real chocolate background imagery  
✅ **Scientifically Calibrated** - Colors extracted from real-world materials

## Contributing

Contributions and feedback are welcome! Open an issue or submit a pull request at:
https://github.com/bobvasic/soft-tactile-warp-theme

## Official Warp Theme Submission

This theme is **ready for submission** to the [official Warp themes repository](https://github.com/warpdotdev/themes).

### Submission Checklist

- [x] Follows Warp YAML theme specification
- [x] Unique neumorphic & claymorphic warm pastel design
- [x] Professional naming convention
- [x] Four comprehensive variants included
- [x] Comprehensive documentation
- [x] MIT License for open source
- [x] Optimized for eye comfort and long sessions

### For Warp Team Review

**Why This Theme Collection Matters:**

Soft Tactile Warp is the **first comprehensive warm-toned theme family** for Warp Terminal. While the existing theme library excels with cool blue/gray palettes, there's a notable gap for developers seeking warm, eye-comfort optimized alternatives.

This collection now includes **four carefully crafted variants** covering every use case from bright daytime work to late-night coding marathons.

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
- **Four cohesive variants** covering all lighting scenarios and saturation preferences
- **Claymorphic design** bringing tactile depth to terminal aesthetics

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

**Created by:** Bob Vasic (@bobvasic)  
**Design Inspiration:** Neumorphic & claymorphic UI principles, tactile design patterns  
**For:** Warp Terminal Community  
**Repository:** https://github.com/bobvasic/soft-tactile-warp-theme

## Support

For issues or customization requests:
- Open an issue on GitHub: https://github.com/bobvasic/soft-tactile-warp-theme/issues
- Warp Community: https://discord.gg/warpdotdev

---

**Enjoy your soft, tactile terminal experience! 🎨✨**
