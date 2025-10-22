# Official Warp Theme Submission Guide

## Step-by-Step Instructions for Submitting to Warp

Based on the [official Warp themes documentation](https://github.com/warpdotdev/themes), follow these steps to submit the Soft Tactile Warp theme collection to the official repository.

---

## Prerequisites

- GitHub account
- Git installed locally
- Python 3 installed (for thumbnail generation)
- Repository: https://github.com/warpdotdev/themes

---

## Submission Steps

### Step 1: Fork the Official Repository

1. Visit https://github.com/warpdotdev/themes
2. Click the **"Fork"** button (top-right)
3. This creates a copy under your GitHub account

### Step 2: Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/themes.git
cd themes
```

Replace `YOUR-USERNAME` with your actual GitHub username.

### Step 3: Create a Feature Branch

```bash
git checkout -b theme/SoftTactileWarp
```

### Step 4: Add Theme Files to Standard Directory

```bash
# Copy all three theme variants to the standard/ directory
cp ~/soft-tactile-warp-theme/soft_tactile_warp_dark.yaml standard/
cp ~/soft-tactile-warp-theme/soft_tactile_warp_light.yaml standard/
cp ~/soft-tactile-warp-theme/soft_tactile_warp_cream.yaml standard/
```

### Step 5: Install Python Dependencies

```bash
pip3 install pillow pyyaml
```

### Step 6: Generate Theme Thumbnails

This is **required** for all submissions:

```bash
python3 ./scripts/gen_theme_previews.py standard
```

This will generate `.svg` preview files for each theme in the `standard/` directory.

### Step 7: Verify Generated Files

```bash
ls -la standard/soft_tactile_warp_*
```

You should see:
- `soft_tactile_warp_dark.yaml`
- `soft_tactile_warp_dark.yaml.svg` (auto-generated)
- `soft_tactile_warp_light.yaml`
- `soft_tactile_warp_light.yaml.svg` (auto-generated)
- `soft_tactile_warp_cream.yaml`
- `soft_tactile_warp_cream.yaml.svg` (auto-generated)

### Step 8: Stage and Commit Changes

```bash
git add standard/soft_tactile_warp_dark.yaml
git add standard/soft_tactile_warp_dark.yaml.svg
git add standard/soft_tactile_warp_light.yaml
git add standard/soft_tactile_warp_light.yaml.svg
git add standard/soft_tactile_warp_cream.yaml
git add standard/soft_tactile_warp_cream.yaml.svg

git commit -m "Add Soft Tactile Warp theme collection

- Three premium neumorphic warm-toned variants
- Dark: Midnight Espresso (rich warm brown)
- Light: Vanilla Latte (creamy vanilla)
- Cream: Sun-Kissed Cappuccino (sun-tanned cream)
- First comprehensive warm coffee/chocolate palette for Warp
- Designed for eye comfort and extended coding sessions
- Zero cool tones - exclusively warm palette
- Enterprise-grade professional aesthetics"
```

### Step 9: Push to Your Fork

```bash
git push origin theme/SoftTactileWarp
```

### Step 10: Create Pull Request

1. Go to your fork on GitHub: `https://github.com/YOUR-USERNAME/themes`
2. You'll see a banner: **"Compare & pull request"** - click it
3. Fill in the PR template:

**Title:**
```
Add Soft Tactile Warp Theme Collection - Warm Neumorphic Themes
```

**Description:**
```markdown
## Theme Collection Overview

Introducing **Soft Tactile Warp** - the first comprehensive warm-toned theme family for Warp Terminal.

### Variants Included

#### 🌙 Soft Tactile Warp Dark - *Midnight Espresso*
- Rich warm brown background (#2b2520)
- Designed for extended coding sessions
- Reduces eye strain through warm coffee-chocolate tones

#### ☀️ Soft Tactile Warp Light - *Vanilla Latte*
- Soft creamy vanilla background (#f5f0e8)
- Professional elegance meets comfortable brightness
- Sophisticated alternative to harsh white themes

#### ☕ Soft Tactile Warp Cream - *Sun-Kissed Cappuccino*
- Warm sun-tanned cream background (#F2E8D9)
- Evokes Mediterranean warmth
- Perfect for all-day comfort

### Why This Collection Matters

- **Market Gap:** First warm brown/coffee-toned theme collection in Warp
- **Health-Focused:** Reduces blue light exposure for 8+ hour coding sessions
- **Neumorphic Design:** Brings soft UI principles to terminal aesthetics
- **Enterprise Ready:** Professional elegance suitable for client-facing work
- **Zero Cool Tones:** Exclusively warm palette (no blues/purples)

### Target Audience
- Developers working late-night hours
- Teams prioritizing developer wellness
- Design-conscious professionals
- Users who find traditional blue/gray themes too cold

### Quality Assurance
- ✅ Follows Warp YAML specification
- ✅ All 16 ANSI colors carefully calibrated
- ✅ Tested across Linux, macOS, Windows
- ✅ Thumbnails generated successfully
- ✅ No background images (pure color themes)
- ✅ MIT licensed

### Repository
https://github.com/bobvasic/soft-tactile-warp-theme

Created by Jelena @ CyberLink Security (https://github.com/jelenastricak)
```

4. Click **"Create pull request"**

### Step 11: Wait for Review

- Warp team typically reviews within 3-7 days
- Be prepared to make adjustments based on feedback
- Monitor your GitHub notifications for comments

---

## Important Notes

### ✅ DO
- Include all three theme variants in one PR
- Generate thumbnails using the provided script
- Follow the exact naming convention used in theme files
- Provide comprehensive PR description
- Be responsive to reviewer feedback

### ❌ DON'T
- Include background images (licensing restrictions)
- Submit without generating thumbnails
- Make multiple PRs for related themes
- Use non-standard YAML formatting

---

## After Submission

Once merged:
- Themes will appear in official Warp themes repository
- Available to all Warp users via `Settings > Appearance`
- Will be included in future Warp releases
- Community can contribute improvements via your repo

---

## Troubleshooting

**Thumbnail generation fails:**
```bash
# Ensure Python dependencies are installed
pip3 install --upgrade pillow pyyaml
```

**YAML validation errors:**
- Ensure all hex colors start with `#`
- Verify `details` is either `darker` or `lighter`
- Check YAML indentation (use spaces, not tabs)

**PR conflicts:**
```bash
# Update your fork with latest changes
git remote add upstream https://github.com/warpdotdev/themes.git
git fetch upstream
git rebase upstream/main
git push origin theme/SoftTactileWarp --force
```

---

## Resources

- **Official Warp Themes Repo:** https://github.com/warpdotdev/themes
- **Warp Documentation:** https://docs.warp.dev/appearance/custom-themes
- **Your Theme Repo:** https://github.com/bobvasic/soft-tactile-warp-theme

---

**Good luck with your submission! 🚀**
