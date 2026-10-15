# 📖 Brand Guidelines Skill

A professional-grade skill that generates comprehensive brand guideline documents for any company, startup, product, or personal brand.

---

## What This Skill Does

When activated, this skill interviews the user (or uses provided context) to gather brand information, then produces a **complete, fully populated brand guidelines document** across 10 key areas:

1. Brand Foundation (mission, vision, values, brand story, personality)
2. Brand Voice & Tone (pillars, tone by context, writing rules, word lists)
3. Logo Usage (variants, clear space, sizing, do's & don'ts)
4. Color Palette (primary, secondary, accent, neutrals — with HEX/RGB/CMYK)
5. Typography (font families, type scale, usage rules)
6. Imagery & Photography (art direction, subject matter, overlays)
7. Iconography & Illustration (style, weight, usage)
8. Digital Applications (website, email, social media specs)
9. Print & Packaging (business cards, letterhead, packaging)
10. Brand Don'ts (common mistakes and corrections)

---

## When to Use This Skill

Trigger this skill when users ask for:
- Brand guidelines / brand guide
- Brand identity document
- Style guide / brand standards
- Brand bible / brand book
- Visual identity documentation
- Brand kit creation
- Defining brand voice, tone, colors, or typography
- Documenting an existing brand

---

## File Structure

```
brand-guidelines/
├── SKILL.md                          # Main skill instructions
├── README.md                         # This file
├── evals/
│   └── evals.json                    # Test cases and assertions
├── references/
│   ├── color-theory.md               # Color psychology, palettes, WCAG
│   ├── typography-guide.md           # Font pairings, type scales, rules
│   └── voice-tone-guide.md           # Voice archetypes, tone charts, writing rules
├── assets/
│   └── intake-form-template.md       # Client intake questionnaire
└── examples/
    └── verdant-brand-guidelines.md   # Full example output (eco brand)
```

---

## Reference Files

| File | When to Consult |
|------|----------------|
| `references/color-theory.md` | When choosing or justifying color palettes; WCAG checks |
| `references/typography-guide.md` | When selecting fonts or defining type scales |
| `references/voice-tone-guide.md` | When crafting voice pillars, tone charts, and writing examples |
| `assets/intake-form-template.md` | When gathering brand information from a client/user |
| `examples/verdant-brand-guidelines.md` | As a reference for output quality and completeness |

---

## Output

The skill produces a complete **Markdown document** with all sections fully populated. No placeholder text. Real HEX codes, real font names, real voice examples.

Export formats available on request:
- Markdown (default)
- PDF
- DOCX

---

## Quality Bar

Every generated document must pass these checks:
- ✅ All 10 sections present and fully written
- ✅ No `[placeholder]` text in the output
- ✅ Valid HEX codes with RGB and CMYK equivalents
- ✅ Named real fonts (Google Fonts preferred)
- ✅ Voice examples feel authentic to the described brand
- ✅ WCAG accessibility noted in color section
- ✅ Channel-specific specs match what the user actually uses

---

## Example Use Cases

- A startup founder who needs brand guidelines before hiring a designer
- A marketing team documenting an existing brand for consistency
- An agency creating a brand bible deliverable for a client
- A freelancer establishing their personal brand identity
- A company rebranding and needing to codify the new direction
