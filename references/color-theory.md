# Color Theory Reference for Brand Guidelines

## Color Psychology Quick Reference

Use this to make informed color recommendations based on brand personality.

| Color | Emotions / Associations | Industries |
|-------|------------------------|------------|
| **Red** | Energy, urgency, passion, boldness | Food, retail, entertainment, sports |
| **Orange** | Enthusiasm, creativity, warmth, approachability | Tech, food, wellness, youth brands |
| **Yellow** | Optimism, happiness, clarity, attention | Retail, food, automotive, education |
| **Green** | Nature, growth, health, sustainability, money | Eco/sustainability, finance, health, food |
| **Blue** | Trust, professionalism, calm, stability | Finance, healthcare, tech, B2B |
| **Purple** | Luxury, wisdom, creativity, spirituality | Beauty, fashion, wellness, education |
| **Pink** | Playfulness, femininity, warmth, romance | Beauty, fashion, lifestyle, food |
| **Brown/Earth** | Warmth, reliability, earthiness, natural | Organic, artisan, outdoors, coffee |
| **Black** | Sophistication, luxury, authority, elegance | Luxury, fashion, tech, premium |
| **White** | Purity, simplicity, cleanliness, space | Healthcare, tech, minimalist brands |
| **Gray** | Neutrality, balance, professionalism | Corporate, tech, automotive |

---

## Recommended Brand Palette Formulas

### Modern & Professional (B2B / SaaS / Finance)
- Primary: Deep Navy `#1A2E4A` or Slate `#2C3E50`
- Secondary: Sky Blue `#3498DB` or Teal `#1ABC9C`
- Accent: Gold `#F39C12` or Coral `#E74C3C`
- Neutrals: Light Gray `#F5F5F5`, Dark Gray `#555555`, White `#FFFFFF`

### Eco / Sustainable / Natural
- Primary: Forest Green `#2D6A4F` or Sage `#74A57F`
- Secondary: Earth Brown `#8B5E3C` or Warm Beige `#D4A373`
- Accent: Golden Yellow `#F4A261` or Terracotta `#E76F51`
- Neutrals: Off-White `#FAF7F2`, Stone `#9B9B9B`

### Bold & Energetic (Consumer / Fitness / Youth)
- Primary: Electric Blue `#0066FF` or Vivid Red `#FF2D55`
- Secondary: Bright Yellow `#FFD60A` or Orange `#FF6B35`
- Accent: Neon Green `#39FF14` or Cyan `#00F5D4`
- Neutrals: Near-Black `#1A1A1A`, White `#FFFFFF`

### Luxury / Premium / Fashion
- Primary: Rich Black `#0D0D0D` or Midnight `#1B1B2F`
- Secondary: Champagne Gold `#C9A84C` or Rose Gold `#C08081`
- Accent: Ivory `#F5F0E8` or Platinum `#E5E4E2`
- Neutrals: Warm White `#FAF9F6`, Charcoal `#333333`

### Playful & Creative (Kids / Education / Entertainment)
- Primary: Bright Purple `#7B2FBE` or Cobalt `#0047AB`
- Secondary: Coral `#FF6B6B` or Sunny Yellow `#FFE66D`
- Accent: Mint `#4ECDC4` or Lime `#A8E063`
- Neutrals: Light Lavender `#F3EFFF`, White `#FFFFFF`

### Health & Wellness / Medical
- Primary: Trust Blue `#1D6FA4` or Calm Teal `#009B8D`
- Secondary: Soft Green `#A8D8B9` or Lavender `#C4AECF`
- Accent: Warm Orange `#F4A261` or Sunshine `#FFC857`
- Neutrals: Clean White `#F8F9FA`, Light Gray `#E9ECEF`

---

## WCAG Accessibility Standards

### Contrast Ratios Required
| Use Case | Minimum Ratio | Recommended |
|----------|--------------|-------------|
| Normal body text (< 18pt) | 4.5:1 | 7:1 |
| Large text (≥ 18pt or 14pt bold) | 3:1 | 4.5:1 |
| UI components & graphical objects | 3:1 | 4.5:1 |

### Quick Contrast Check Rules of Thumb
- **Black text on white:** 21:1 (perfect)
- **Dark Navy on White:** ~14:1 (excellent)
- **Medium Gray (#767676) on White:** exactly 4.5:1 (minimum pass)
- **Yellow on White:** typically fails — avoid
- **White text on pure Red:** borderline — check carefully
- **White on dark colors (navy, forest green, black):** usually passes

### Color Blindness Considerations
- ~8% of males have red-green color blindness — don't rely on red/green alone to convey meaning
- Use patterns, icons, or labels alongside color
- Test palettes with tools like [Coblis](https://www.color-blindness.com/coblis-color-blindness-simulator/)

---

## Converting Between Color Formats

### HEX to RGB
- Split the 6-digit hex into 3 pairs
- Convert each pair from base-16 to base-10
- Example: `#3498DB` → R:52, G:152, B:219

### RGB to CMYK (approximate)
```
R' = R/255, G' = G/255, B' = B/255
K = 1 - max(R', G', B')
C = (1 - R' - K) / (1 - K)
M = (1 - G' - K) / (1 - K)
Y = (1 - B' - K) / (1 - K)
Multiply by 100 for percentages
```

### Common Online Tools
- [Adobe Color](https://color.adobe.com) – palette generation and harmony rules
- [Coolors.co](https://coolors.co) – palette generator
- [Paletton](https://paletton.com) – color scheme designer
- [Contrast Checker](https://webaim.org/resources/contrastchecker/) – WCAG compliance

---

## Color Harmony Rules

| Harmony Type | Description | Best For |
|--------------|-------------|----------|
| **Complementary** | Opposite colors on the wheel | High contrast, bold, CTAs |
| **Analogous** | Adjacent colors on the wheel | Cohesive, calm, natural |
| **Triadic** | Three evenly spaced colors | Vibrant, playful, dynamic |
| **Split-complementary** | One color + two adjacent to its complement | Balanced + interesting |
| **Monochromatic** | Same hue at different shades | Clean, minimal, sophisticated |
| **Tetradic/Square** | Four colors evenly spaced | Complex, rich, needs careful balancing |
