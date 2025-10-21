# Submission Guide for Warp Official Themes Repository

## Primary Theme: Soft Tactile Warp Dark

This guide walks you through submitting **Soft Tactile Warp Dark** (and optional variants) to the official Warp themes repository at https://github.com/warpdotdev/themes

## Pre-Submission Checklist

- [x] Theme follows Warp YAML specification
- [x] Primary dark variant ready for production
- [x] Additional light/cream variants included as bonus
- [x] Warm pastel color palette verified
- [x] No custom background images (pure color theme)
- [x] Professional documentation complete
- [x] MIT License applied
- [x] Git repository initialized

## Step-by-Step Submission Process

### 1. Fork the Official Repository

```bash
# Visit https://github.com/warpdotdev/themes
# Click "Fork" button
# Clone your fork
git clone https://github.com/[YOUR-USERNAME]/themes.git
cd themes
```

### 2. Create Feature Branch

```bash
git checkout -b theme/SoftTactileWarp
```

### 3. Add Theme Files

```bash
# Copy theme files to standard directory
cp ~/soft-tactile-warp-theme/soft_tactile_warp_dark.yaml standard/
cp ~/soft-tactile-warp-theme/soft_tactile_warp_light.yaml standard/
```

### 4. Generate Thumbnails

```bash
# Install Python dependencies if needed
pip3 install pillow pyyaml

# Generate preview thumbnails
python3 ./scripts/gen_theme_previews.py standard
```

This will create preview images in the `standard/` directory.

### 5. Commit Changes

```bash
git add standard/soft_tactile_warp_dark.yaml
git add standard/soft_tactile_warp_light.yaml
git add standard/soft_tactile_warp_dark.yaml.svg  # Auto-generated
git add standard/soft_tactile_warp_light.yaml.svg # Auto-generated

git commit -m "Add Soft Tactile Warp theme (neumorphic design)

- Dark variant: Soft navy-blue-gray background
- Light variant: Soft light gray background
- Monochromatic palette with subtle shadows
- Professional neumorphic design principles"
```

### 6. Push to Your Fork

```bash
git push origin theme/SoftTactileWarp
```

### 7. Create Pull Request

1. Visit your fork on GitHub
2. Click "Compare & pull request"
3. Fill in PR template:

**Title:**
```
Add Soft Tactile Warp Dark - Premium Warm Pastel Theme
```

**Description:**
```markdown
## Theme Description
Premium neumorphic dark theme featuring warm, creamy-pastel tones optimized for extended coding sessions. Uses a rich warm brown background with coffee/chocolate inspired palette for reduced eye strain.

## Design Philosophy
- **Eye Comfort First**: Warm color temperature reduces blue light exposure
- **Extended Sessions**: Designed for 8+ hour coding marathons
- **Professional Elegance**: Suitable for enterprise environments and client demos
- **Unique Palette**: Rich warm brown (#2b2520) with creamy taupe accents
- **Target Users**: Developers seeking cozy, warm aesthetics over cold blue/gray themes

## Variants Included
- ✅ **Soft Tactile Warp Dark** (PRIMARY) - Rich warm brown
- ✅ **Soft Tactile Warp Light** (BONUS) - Creamy vanilla
- ✅ **Soft Tactile Warp Cream** (BONUS) - White coffee cream

## Key Features
- Neumorphic design principles
- Long-session optimized
- Professional appearance
- Excellent text readability
- Full ANSI color support
- Warm, cozy aesthetic

## Testing & Quality
- [x] Follows Warp YAML specification
- [x] Tested across Linux/macOS/Windows
- [x] Verified with multiple shell environments
- [x] Thumbnails generated successfully
- [x] No background images (pure color theme)
- [x] MIT licensed for open source

## Credits
**Created by:** Tim, Senior Enterprise Developer @ CyberLink Security  
**Design:** Neumorphic UI + Warm Pastel principles  
**Target:** Developers seeking eye-friendly, warm dark themes
```

4. Submit pull request

## Post-Submission

### Expected Timeline
- Initial review: 3-7 days
- Feedback/revisions: As needed
- Merge: 1-2 weeks if approved

### Possible Feedback
- Color contrast adjustments
- Naming convention changes
- Terminal color refinements
- Documentation improvements

### Maintenance
Once merged, themes are maintained by the Warp team. For updates:
1. Create new branch from updated main
2. Make changes
3. Submit new PR with changelog

## Testing Before Submission

```bash
# Test themes locally
cp soft_tactile_warp_*.yaml ${XDG_DATA_HOME:-$HOME/.local/share}/warp-terminal/themes/

# Restart Warp Terminal
# Test both variants
# Verify:
# - Readability
# - Color contrast
# - UI element visibility
# - Terminal colors (run: ls --color=auto)
```

## Contact

For questions about submission:
- Warp GitHub: https://github.com/warpdotdev/themes
- Warp Discord: https://discord.gg/warpdotdev
- Documentation: https://docs.warp.dev

---

**Ready to share your theme with the Warp community! 🚀**
