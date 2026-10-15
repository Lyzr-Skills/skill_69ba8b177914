---
name: brand-guidelines
description: >
  Generates comprehensive, professional brand guideline documents for companies, startups, products, or personal brands. 
  Use this skill whenever a user wants to create brand guidelines, a brand identity document, a style guide, brand standards, 
  a visual identity document, brand rules, brand bible, or any document that defines how a brand should look, feel, sound, 
  and communicate. Trigger this skill even when users say things like "help me define my brand", "create branding rules for 
  my company", "document my brand identity", "write a style guide", "make a brand kit", or "set up brand standards". 
  Always use this skill when brand consistency, brand voice, logo usage, color palettes, typography, or brand tone are mentioned 
  together or individually in a branding context.
---

# Brand Guidelines Skill

This skill helps you produce thorough, polished, and ACTIONABLE brand guideline documents that any team member, designer, or external partner can follow. The output should feel like it came from a professional branding agency.

---

## What This Skill Does

When triggered, interview the user (or use available context) to gather brand information, then produce a complete brand guidelines document. The document covers:

- **Brand Foundation** – mission, vision, values, brand story
- **Brand Voice & Tone** – personality, language rules, dos & don'ts
- **Logo Usage** – correct/incorrect usage, spacing, sizing, variants
- **Color Palette** – primary, secondary, and accent colors with HEX/RGB/CMYK values
- **Typography** – font families, hierarchy, usage rules
- **Imagery & Photography** – style, mood, what to avoid
- **Iconography & Illustrations** – style guidelines
- **Digital & Print Applications** – how the brand applies across channels
- **Brand Don'ts** – common mistakes to avoid

---

## Step-by-Step Process

### Step 1: Gather Brand Information

Ask the user for the following (or extract from context if already provided). Gather all in one ask — don't ask one at a time:

```
1. Brand/Company Name
2. Industry or niche
3. Target audience (age, profession, lifestyle, goals)
4. Brand personality (3–5 adjectives, e.g., bold, playful, sophisticated)
5. Brand mission (what you do and why)
6. Brand vision (where you're going)
7. Core brand values (3–5 values)
8. Logo description (if they have one — colors, shape, wordmark vs. icon)
9. Primary color preferences (if any)
10. Preferred font styles (serif, sans-serif, script, etc.)
11. Tone of voice (formal, casual, inspirational, technical, friendly, etc.)
12. Competitors or brands they admire (for style reference)
13. Key channels (website, Instagram, LinkedIn, print, packaging, etc.)
```

If the user has already provided some of this, use it. Only ask for what's missing.

---

### Step 2: Generate the Brand Guidelines Document

Produce a full Markdown document following the **Brand Guidelines Template** below. Fill every section thoughtfully — don't leave placeholders. Use the brand information to make specific, real recommendations for colors, fonts, voice examples, etc.

---

## Brand Guidelines Template

Use this EXACT structure. Expand each section with real, detailed, useful content:

```markdown
# [Brand Name] Brand Guidelines

**Version:** 1.0  
**Last Updated:** [Current Date]  
**Prepared for:** [Brand Name] Team

---

## 📋 Table of Contents
1. Brand Foundation
2. Brand Voice & Tone
3. Logo Usage
4. Color Palette
5. Typography
6. Imagery & Photography Style
7. Iconography & Illustration
8. Digital Applications
9. Print & Packaging
10. Brand Don'ts

---

## 1. 🏛️ Brand Foundation

### Our Mission
[Write a clear, compelling 1–2 sentence mission statement]

### Our Vision
[Write a future-oriented vision statement]

### Brand Story
[Write 2–3 paragraphs telling the brand's story — origin, purpose, and direction]

### Core Values
| Value | What It Means to Us |
|-------|----------------------|
| [Value 1] | [Description] |
| [Value 2] | [Description] |
| [Value 3] | [Description] |

### Brand Personality
We are: **[Adjective 1]**, **[Adjective 2]**, **[Adjective 3]**

Think of our brand as a person: [Describe the brand as a human character — their style, speech, and attitude]

---

## 2. 🗣️ Brand Voice & Tone

### Voice vs. Tone
- **Voice** is who we are — it stays consistent always.
- **Tone** shifts depending on context (celebrating a launch vs. handling a complaint).

### Our Voice Pillars

| Pillar | Description | Do | Don't |
|--------|-------------|-----|-------|
| [Pillar 1] | [What this means] | [Example] | [Counter-example] |
| [Pillar 2] | [What this means] | [Example] | [Counter-example] |
| [Pillar 3] | [What this means] | [Example] | [Counter-example] |

### Tone by Context
| Context | Tone | Example |
|---------|------|---------|
| Marketing copy | [tone] | "[sample line]" |
| Customer support | [tone] | "[sample line]" |
| Social media | [tone] | "[sample line]" |
| Error messages | [tone] | "[sample line]" |
| Celebrations/milestones | [tone] | "[sample line]" |

### Writing Style Rules
- [Rule 1 — e.g., Use active voice]
- [Rule 2 — e.g., Avoid jargon unless addressing specialists]
- [Rule 3 — e.g., Sentences should be short and punchy]
- [Rule 4]
- [Rule 5]

### Words We Love
[List 8–10 words or phrases that feel on-brand]

### Words We Avoid
[List 8–10 words or phrases that feel off-brand]

---

## 3. 🎨 Logo Usage

### Primary Logo
[Describe the primary logo — composition, what it includes, what it represents]

### Logo Variants
| Variant | When to Use |
|---------|-------------|
| Primary (full color) | Light backgrounds, primary marketing materials |
| Reversed (white) | Dark backgrounds |
| Monochrome (black) | Single-color print, embossing |
| Icon only | Small sizes, app icons, favicons, social avatars |

### Clear Space
Always maintain a minimum clear space around the logo equal to **[X]** — typically the height of a key letter in the wordmark. Never crowd the logo with other elements.

### Minimum Size
- **Digital:** No smaller than [X]px wide
- **Print:** No smaller than [X]mm wide

### Logo Do's ✅
- Use on approved backgrounds only
- Maintain aspect ratio at all times
- Use the correct color variant for the background

### Logo Don'ts ❌
- Do not stretch or distort the logo
- Do not add drop shadows or effects
- Do not change the logo colors
- Do not place on busy or clashing backgrounds
- Do not recreate or redraw the logo
- Do not rotate the logo

---

## 4. 🎨 Color Palette

### Primary Colors
These are the foundation of our brand. Use these most.

| Color Name | HEX | RGB | CMYK | Usage |
|------------|-----|-----|------|-------|
| [Name] | #[HEX] | [R, G, B] | [C, M, Y, K] | Primary backgrounds, headlines |
| [Name] | #[HEX] | [R, G, B] | [C, M, Y, K] | CTAs, highlights |

### Secondary Colors
Support the primary palette. Use for variety and depth.

| Color Name | HEX | RGB | CMYK | Usage |
|------------|-----|-----|------|-------|
| [Name] | #[HEX] | [R, G, B] | [C, M, Y, K] | [usage] |
| [Name] | #[HEX] | [R, G, B] | [C, M, Y, K] | [usage] |

### Accent / Neutral Colors
| Color Name | HEX | RGB | Usage |
|------------|-----|-----|-------|
| [Name] | #[HEX] | [R, G, B] | Body text |
| [Name] | #[HEX] | [R, G, B] | Backgrounds, dividers |
| [Name] | #[HEX] | [R, G, B] | White space |

### Color Usage Ratios
- **60%** – Primary color (dominant)
- **30%** – Secondary color (supporting)
- **10%** – Accent color (highlight and CTA)

### Accessibility
All text/background combinations must meet **WCAG AA** contrast standards (minimum 4.5:1 for body text, 3:1 for large text).

---

## 5. ✍️ Typography

### Font Families

#### Primary Typeface — [Font Name]
Used for: Headlines, display text, hero sections  
Style: [Serif / Sans-serif / Slab / etc.]  
Why: [Why this font fits the brand]

**Weights used:**
- Light (300) – large decorative text
- Regular (400) – subheadings
- Bold (700) – headlines and emphasis

#### Secondary Typeface — [Font Name]
Used for: Body copy, UI text, captions  
Style: [Sans-serif / etc.]  
Why: [Why this pairs well]

**Weights used:**
- Regular (400) – body copy
- Medium (500) – labels, UI
- Bold (700) – callouts

#### Accent Typeface — [Font Name] *(optional)*
Used for: Quotes, special callouts, brand moments  
Style: [Script / Display / etc.]

### Type Scale (Desktop)

| Element | Font | Size | Weight | Line Height |
|---------|------|------|--------|-------------|
| H1 | Primary | 56px | Bold | 1.15 |
| H2 | Primary | 40px | Bold | 1.2 |
| H3 | Primary | 28px | Semi-Bold | 1.25 |
| H4 | Secondary | 20px | Medium | 1.3 |
| Body Large | Secondary | 18px | Regular | 1.6 |
| Body | Secondary | 16px | Regular | 1.6 |
| Caption | Secondary | 13px | Regular | 1.5 |
| Label / UI | Secondary | 12px | Medium | 1.4 |

### Typography Do's ✅
- Maintain visual hierarchy at all times
- Use sentence case for most text (not ALL CAPS or Title Case for body)
- Pair primary and secondary fonts for contrast

### Typography Don'ts ❌
- Never use more than 2–3 typefaces in one layout
- Never set body text below 14px
- Avoid justified text (use left-aligned instead)
- Never stretch or condense font letterforms

---

## 6. 📷 Imagery & Photography Style

### Art Direction Principles
[Describe the overall visual feel — e.g., natural light, authentic, cinematic, bright and airy, moody, editorial]

### Subject Matter
- **People:** [How people should appear — candid vs. posed, diverse, lifestyle vs. portrait]
- **Settings/Environments:** [Office, outdoors, urban, studio, etc.]
- **Products:** [How product shots should feel]

### Photography Do's ✅
- [e.g., Use natural lighting whenever possible]
- [e.g., Feature real people, not overly staged stock]
- [e.g., Maintain consistent color temperature]
- [e.g., High resolution — minimum 2000px on shortest side]

### Photography Don'ts ❌
- [e.g., Avoid clichéd stock photography]
- [e.g., No heavy filters or extreme post-processing]
- [e.g., Avoid dark, low-contrast images]

### Image Overlay & Text Treatment
When placing text over images:
- Use a [color] overlay at [X]% opacity
- Ensure text contrast meets WCAG AA standards
- Only use light text on dark images and vice versa

---

## 7. 🔷 Iconography & Illustration

### Icon Style
- **Style:** [Line / Filled / Duotone / Flat / 3D]
- **Stroke weight:** [Consistent weight, e.g., 1.5–2px]
- **Corner style:** [Rounded / Sharp]
- **Size grid:** [24px / 32px / 48px base grid]

### Illustration Style *(if applicable)*
[Describe the illustration aesthetic — e.g., geometric, hand-drawn, flat vector, abstract, data-driven]

### Guidelines
- Icons must be consistent in weight and style across the entire product
- Always use brand colors for icon fills and strokes
- Avoid mixing icon libraries or conflicting styles

---

## 8. 💻 Digital Applications

### Website
- **Background:** [Primary background color]
- **Primary CTA buttons:** [Color, corner radius, typography]
- **Secondary CTA:** [Outline style, color]
- **Navigation:** [Color, font, behavior]
- **Cards/Containers:** [Color, shadow, border radius]

### Email
- Max width: 600px
- Background: [Color]
- Header: Logo centered or left-aligned on [color] background
- Body: [Font], [size], [line height]
- Footer: [Color], [font size], unsubscribe link required

### Social Media

| Platform | Profile Image | Cover/Banner | Post Format |
|----------|--------------|--------------|-------------|
| Instagram | Icon logo, [color] bg | N/A | Square 1:1, vertical 4:5 |
| LinkedIn | Full logo, white bg | Brand imagery + tagline | 1200×627px |
| Twitter/X | Icon logo | Brand color + tagline | 1500×500px |
| Facebook | Full logo | Brand imagery | 820×312px |

### App / Product UI *(if applicable)*
- Follow platform conventions (iOS HIG / Material Design) within brand color and type guidelines
- Use the icon-only logo variant for app icons
- Primary interactive color: [HEX]
- Destructive/error color: #D94F4F (or brand-consistent red)
- Success color: #4CAF50 (or brand-consistent green)

---

## 9. 🖨️ Print & Packaging

### Business Cards
- Size: 3.5" × 2" (standard) or 85mm × 55mm
- Front: Logo, brand color background
- Back: Contact details — name, title, email, phone, website
- Font: [Font], [size]
- Finish: [Matte / Gloss / Soft-touch / Spot UV]

### Letterhead
- Logo top-left or centered
- Brand color header bar
- Footer: address, phone, website, [social handles]

### Packaging *(if applicable)*
- [Describe how brand colors, logo, and typography apply to packaging]
- Minimum logo size: [X]mm
- Required regulatory text placement: [location]

---

## 10. 🚫 Brand Don'ts

These apply across ALL brand applications:

| ❌ Don't | ✅ Instead |
|----------|-----------|
| Use off-brand fonts | Stick to the approved typefaces |
| Use unapproved colors | Refer to the official color palette |
| Stretch or distort the logo | Maintain aspect ratio always |
| Mix photography and illustration carelessly | Keep styles consistent per campaign |
| Use ALL CAPS for body text | Use sentence case |
| Use low-resolution images | Minimum 72dpi digital, 300dpi print |
| Use the wordmark on a busy background | Use on solid or approved gradient backgrounds |
| Improvise brand decisions | When in doubt, consult this document |

---

## Appendix

### Font Downloads / Sources
- [Font 1]: [Google Fonts / Adobe Fonts / Foundry URL]
- [Font 2]: [Source]

### Asset Library
All approved logos, templates, and assets are stored at:  
[Link to brand asset folder / design system / Figma file]

### Questions & Brand Approvals
For brand-related questions or approval of new materials, contact:  
**[Name / Team]** — [email]

---

*This document is a living guide. Updates will be versioned and communicated to all stakeholders.*
```

---

## Output Format

- Deliver the brand guidelines as a **formatted Markdown document**
- Offer to also export as **PDF** or **DOCX** if the user requests
- All color values must include HEX, RGB, and CMYK
- All font recommendations should be **free or widely available** (Google Fonts preferred) unless the user specifies custom fonts
- Ensure the document is COMPREHENSIVE — every section fully filled, no "[placeholder]" text left in the final output

---

## Quality Checklist

Before delivering, verify:
- [ ] All sections are fully populated with specific, real content
- [ ] No "[placeholder]" text remains
- [ ] Color HEX codes are valid and aesthetically coherent
- [ ] Font pairings make visual sense for the brand personality
- [ ] Voice examples feel authentic to the brand
- [ ] Logo usage rules are clear and enforceable
- [ ] The document is readable and well-structured
- [ ] WCAG accessibility note is included in the color section

---

## Example Interaction

**User:** "Can you create brand guidelines for my startup called 'Verdant'? We make eco-friendly home products. Our audience is environmentally conscious millennials. We want to feel fresh, modern, and trustworthy."

**Skill behavior:**
- Recognizes missing details (logo, specific colors, fonts)
- Asks ONE grouped set of questions to fill the gaps
- Produces a complete brand guideline doc with earth-tone palette, clean sans-serif fonts, nature-inspired imagery guidelines, and a warm-but-authoritative voice

---

## Notes for Edge Cases

- **No logo yet?** Describe ideal logo concepts and provide direction for when they work with a designer.
- **Existing brand, needs documentation?** Extract the brand rules from what they share and formalize them.
- **Rebranding?** Acknowledge the old brand briefly, then focus on the new direction.
- **Very early-stage startup?** Lean into recommendations; they may not have answers for everything — make smart defaults.
