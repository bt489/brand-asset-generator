# ShipSignal Brand Guidelines

## Brand Overview

**Brand Name:** ShipSignal
**Tagline:** Skip the research. Start building.
**CTA:** Get tomorrow's ideas
**Website:** shipsignal.ai
**Social:** @shipsignal

**Brand Voice:** Straightforward, data-driven, slightly playful
**Target Audience:** Developers and founders
**Industry:** SaaS

---

## Logo Usage

### Primary Logo
The ShipSignal logo consists of two elements:
1. **Logomark:** A broadcasting signal icon (circle with emanating wave arcs)
2. **Wordmark:** "ShipSignal" in Outfit Bold (700 weight)

### Logo Variants
| Variant | Use Case |
|---------|----------|
| `logo-primary.svg` | Default, full-color on light backgrounds |
| `logo-stacked.svg` | Vertical layouts, square spaces |
| `logomark-only.svg` | App icons, favicons, small spaces |
| `wordmark-only.svg` | When logomark appears separately |
| `logo-monochrome-white.svg` | Dark backgrounds, overlays |
| `logo-monochrome-black.svg` | Single-color printing |
| `logo-monochrome-brand.svg` | Brand color emphasis |

### Clear Space
Maintain clear space around the logo equal to the height of the logomark circle on all sides.

```
    ┌─────────────────────────┐
    │         ○               │
    │   ○ ))) ShipSignal      │
    │         ○               │
    └─────────────────────────┘
    ○ = minimum clear space (1x logomark height)
```

### Minimum Sizes
- **Full logo:** 120px wide (digital), 1 inch (print)
- **Logomark only:** 24px (digital), 0.25 inch (print)
- **Favicon:** 16px minimum

---

## Logo Don'ts

❌ **DO NOT** modify the logo colors
❌ **DO NOT** stretch or distort the logo
❌ **DO NOT** add effects (shadows, gradients, outlines)
❌ **DO NOT** rotate the logo
❌ **DO NOT** change the typeface
❌ **DO NOT** rearrange logo elements
❌ **DO NOT** place on busy backgrounds without contrast
❌ **DO NOT** recreate or redraw the logo

---

## Color Palette

### Primary Colors
| Name | Hex | RGB | Use |
|------|-----|-----|-----|
| Indigo 600 | `#4f46e5` | 79, 70, 229 | Primary brand, CTAs |
| Indigo 500 | `#6366f1` | 99, 102, 241 | Primary accent |
| Indigo 400 | `#818cf8` | 129, 140, 248 | Secondary accent |
| Indigo 300 | `#a5b4fc` | 165, 180, 252 | Light accent |
| Indigo 200 | `#c7d2fe` | 199, 210, 254 | Backgrounds |

### Neutral Colors
| Name | Hex | Use |
|------|-----|-----|
| White | `#ffffff` | Backgrounds, text on dark |
| Gray 900 | `#111827` | Primary text |
| Gray 800 | `#1f2937` | Secondary text, dark UI |
| Gray 100 | `#f3f4f6` | Light backgrounds |

### Gradients
**Primary Gradient:**
```css
background: linear-gradient(135deg, #4f46e5 0%, #6366f1 50%, #818cf8 100%);
```

**Dark Gradient (backgrounds):**
```css
background: linear-gradient(135deg, #1e1b4b 0%, #312e81 50%, #3730a3 100%);
```

---

## Typography

### Primary Typeface
**Outfit** - Google Font
https://fonts.google.com/specimen/Outfit

### Type Scale
| Element | Size | Weight | Line Height |
|---------|------|--------|-------------|
| H1 | 72px | 700 | 1.1 |
| H2 | 48px | 700 | 1.2 |
| H3 | 32px | 700 | 1.3 |
| H4 | 24px | 600 | 1.4 |
| Body Large | 20px | 400 | 1.6 |
| Body | 16px | 400 | 1.6 |
| Small | 14px | 400 | 1.5 |
| Caption | 12px | 400 | 1.4 |

### Font Loading
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;500;600;700&display=swap" rel="stylesheet">
```

---

## Voice & Tone

### Brand Personality
- **Straightforward:** Clear, direct communication. No fluff.
- **Data-driven:** Facts and evidence over opinions.
- **Slightly playful:** Approachable without being silly.

### Writing Guidelines
- Lead with value
- Use active voice
- Keep sentences short
- Avoid jargon (unless audience-appropriate)
- Be confident, not arrogant

### Example Copy
✅ "Skip the research. Start building."
✅ "Get tomorrow's ideas"
✅ "Daily SaaS ideas. Validated. Ready to build."

❌ "We're revolutionizing the way developers..."
❌ "Synergize your development workflow..."

---

## Asset Checklist

### Required for Launch
- [ ] Primary logo on website
- [ ] Favicon set installed
- [ ] OG image configured
- [ ] Social profile pictures uploaded
- [ ] Social cover images set

### Social Platform Specs
| Platform | Profile | Cover/Header |
|----------|---------|--------------|
| X/Twitter | 400x400 | 1500x500 |
| LinkedIn | 400x400 | 1128x191 |
| Instagram | 320x320 | N/A |
| Facebook | 400x400 | 820x312 |
| YouTube | 800x800 | 2560x1440 |

---

## File Organization

```
branding-design/
├── logos/          # All logo variations
├── favicons/       # Favicon system
├── tokens/         # CSS & JSON design tokens
├── web/            # Website assets (OG, headers)
├── social/         # Platform-specific assets
│   ├── twitter/
│   ├── instagram/
│   ├── linkedin/
│   ├── facebook/
│   └── youtube/
├── email/          # Email marketing assets
├── ads/            # Display advertising
├── documents/      # Business documents
├── video/          # Video/motion assets
├── patterns/       # Background patterns
└── specs/          # This documentation
```

---

## Contact

For brand questions or asset requests:
**Website:** shipsignal.ai
**Social:** @shipsignal
