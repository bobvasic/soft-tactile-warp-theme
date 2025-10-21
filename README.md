# Soft Tactile Warp Dark

A premium neumorphic dark theme for [Warp Terminal](https://warp.dev) featuring warm, creamy-pastel tones optimized for extended coding sessions. Designed with eye comfort and visual elegance in mind.

## Design Philosophy

This theme embraces **neumorphism** and **warm pastel design** principles:

- **Rich warm brown background** (`#2b2520`) - deeper than standard dark themes
- **Creamy taupe accents** with coffee/chocolate inspired palette
- **Reduced eye strain** through warm color temperature
- **Professional elegance** suitable for enterprise environments
- **Monochromatic harmony** maintaining excellent readability
- **Long-session optimized** for comfortable extended programming

## Theme Showcase

### 🌙 Soft Tactile Warp Dark (PRIMARY)

**Background:** Rich warm brown (`#2b2520`)  
**Accent:** Creamy taupe (`#9b8b7e`)  
**Foreground:** Creamy beige (`#e5d5c5`)  

**Perfect for:**
- Late-night coding sessions
- Reducing blue light exposure
- Professional enterprise environments
- Long-duration programming work
- Developers who prefer warm, cozy aesthetics over cold blue/gray themes

---

### Additional Variants (Bonus)

This repository also includes complementary light variants:

- **Soft Tactile Warp Light** - Creamy vanilla background
- **Soft Tactile Warp Cream** - White coffee cream background

These share the same warm pastel philosophy for users who prefer brighter workspaces.

## Installation

### Method 1: Manual Installation

1. **Create themes directory:**

```bash
# Linux
mkdir -p ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/

# macOS
mkdir -p $HOME/.warp/themes/

# Windows (PowerShell)
New-Item -Path "$env:APPDATA\warp\Warp\data\themes\" -ItemType Directory
```

2. **Copy theme files:**

```bash
# Linux/macOS
cp soft_tactile_warp_*.yaml ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/

# Windows (PowerShell)
Copy-Item soft_tactile_warp_*.yaml "$env:APPDATA\warp\Warp\data\themes\"
```

3. **Activate theme:**
   - Open Warp Terminal
   - Go to `Settings > Appearance > Current Theme`
   - Select "Soft Tactile Warp Dark" or "Soft Tactile Warp Light"

### Method 2: Download from GitHub

```bash
# Linux
cd ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/
wget https://raw.githubusercontent.com/[YOUR-USERNAME]/soft-tactile-warp-theme/main/soft_tactile_warp_dark.yaml

# macOS
cd $HOME/.warp/themes/
curl -O https://raw.githubusercontent.com/[YOUR-USERNAME]/soft-tactile-warp-theme/main/soft_tactile_warp_dark.yaml
```

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
| Background | `#faf7f2` | White coffee cream |
| Foreground | `#4d4238` | Espresso text |
| Accent | `#b59a87` | Caramel latte |
| Cursor | `#a0856f` | Warm caramel |

## Key Features

✅ **Eye Comfort First** - Warm color temperature reduces blue light exposure  
✅ **Extended Session Ready** - Designed for 8+ hour coding marathons  
✅ **Enterprise Professional** - Elegant aesthetics suitable for client demos  
✅ **Creamy Pastel Palette** - Coffee/chocolate inspired warm tones  
✅ **High Contrast Text** - Excellent readability without harsh edges  
✅ **ANSI Color Support** - Full terminal color compatibility  
✅ **Neumorphic Design** - Soft, tactile visual language  
✅ **Multiple Variants** - Dark, Light, and Cream options included

## Screenshots

*[Screenshots will be auto-generated upon PR submission to Warp themes repo]*

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

**Theme Philosophy:**  
Soft Tactile Warp Dark addresses the need for warm, comfortable dark themes that reduce eye strain during extended coding sessions. Unlike traditional blue/gray dark themes, this uses a coffee/chocolate inspired palette that's both professional and cozy.

**Target Audience:**  
- Developers working late-night hours
- Teams seeking reduced blue light exposure
- Professionals wanting elegant, premium aesthetics
- Users who find traditional dark themes too cold or harsh

## Compatibility

- ✅ Warp Terminal (all versions)
- ✅ Linux, macOS, Windows
- ✅ All shell environments (bash, zsh, fish, etc.)

## License

MIT License - Free for personal and commercial use

## Credits

**Created by:** Tim, Senior Enterprise Developer @ CyberLink Security  
**Design Inspiration:** Neumorphic UI principles and tactile design patterns  
**For:** Warp Terminal Community

## Support

For issues or customization requests:
- Open an issue on GitHub
- Contact: [your-email]
- Warp Community: [Discord/Forum link]

---

**Enjoy your soft, tactile terminal experience! 🎨✨**
