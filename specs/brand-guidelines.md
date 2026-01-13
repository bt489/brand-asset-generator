# ShipSignal Brand Guidelines

## Brand Overview

**ShipSignal** is a modern, tech-forward brand focused on delivering notifications that matter. Our visual identity reflects clarity, reliability, and seamless communication.

### Brand Personality
- **Modern** - Clean, contemporary design language
- **Reliable** - Trustworthy and dependable
- **Clear** - Simple, straightforward communication
- **Technical** - Sophisticated yet approachable

---

## Logo Usage

### Primary Logo
The primary logo combines the "ShipSignal" wordmark with the signal icon (broadcasting dot with wave arcs). Use this version whenever possible for maximum brand recognition.

### Logo Variations
| Variant | Use Case |
|---------|----------|
| `logo-primary.svg` | Default use on light backgrounds |
| `logo-stacked.svg` | Tight vertical spaces, app icons |
| `logomark-only.svg` | Small spaces, favicons, app icons |
| `wordmark-only.svg` | When the icon would be too small |
| `logo-monochrome-black.svg` | Single-color print, dark backgrounds |
| `logo-monochrome-white.svg` | Dark backgrounds, overlays |
| `logo-monochrome-brand.svg` | Simplified brand color usage |

### Clear Space
Maintain a minimum clear space around the logo equal to the height of the "S" in ShipSignal. This ensures the logo remains visible and uncluttered.

```
┌─────────────────────────────────────┐
│                                     │
│     ╔═══════════════════════╗       │
│     ║   [ShipSignal Logo]   ║       │
│     ╚═══════════════════════╝       │
│                                     │
│  ← Minimum clear space = "S" height │
└─────────────────────────────────────┘
```

### Minimum Sizes
- **Full logo**: 120px wide minimum (digital), 1 inch (print)
- **Logomark only**: 24px minimum (digital), 0.25 inch (print)
- **Favicon**: 16px minimum

---

## Logo Don'ts

❌ **Never do the following:**

1. **Don't stretch or distort** the logo
2. **Don't rotate** the logo at an angle
3. **Don't change the colors** outside approved palette
4. **Don't add effects** (shadows, glows, outlines)
5. **Don't place on busy backgrounds** without sufficient contrast
6. **Don't rearrange** the logo elements
7. **Don't use low-resolution** versions
8. **Don't add text** directly adjacent to the logo
9. **Don't use the old logo** or create variations

---

## Color System

### Primary Palette
| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| Indigo 900 | `#312e81` | 49, 46, 129 | Dark backgrounds, headers |
| Indigo 800 | `#3730a3` | 55, 48, 163 | Secondary dark |
| Indigo 700 | `#4338ca` | 67, 56, 202 | Hover states |
| Indigo 600 | `#4f46e5` | 79, 70, 229 | **Primary brand color** |
| Indigo 500 | `#6366f1` | 99, 102, 241 | **Primary interactive** |
| Indigo 400 | `#818cf8` | 129, 140, 248 | Links, accents |
| Indigo 300 | `#a5b4fc` | 165, 180, 252 | Light accents |
| Indigo 200 | `#c7d2fe` | 199, 210, 254 | Subtle backgrounds |
| Indigo 100 | `#e0e7ff` | 224, 231, 255 | Very light backgrounds |
| Indigo 50 | `#eef2ff` | 238, 242, 255 | Tints, highlights |

### Neutral Palette
| Color | Hex | Usage |
|-------|-----|-------|
| Gray 900 | `#111827` | Primary text |
| Gray 700 | `#374151` | Secondary text |
| Gray 500 | `#6b7280` | Tertiary text |
| Gray 300 | `#d1d5db` | Borders |
| Gray 100 | `#f3f4f6` | Backgrounds |
| White | `#ffffff` | Base backgrounds |

### Semantic Colors
| Color | Hex | Usage |
|-------|-----|-------|
| Success | `#10b981` | Positive actions, confirmations |
| Warning | `#f59e0b` | Caution states |
| Error | `#ef4444` | Errors, destructive actions |
| Info | `#3b82f6` | Informational messages |

### Gradients
```css
/* Primary Gradient */
linear-gradient(90deg, #4f46e5 0%, #818cf8 100%)

/* Light Gradient (for dark mode text) */
linear-gradient(90deg, #818cf8 0%, #c7d2fe 100%)

/* Dark Gradient (backgrounds) */
linear-gradient(90deg, #312e81 0%, #4f46e5 100%)
```

---

## Typography

### Primary Font: Outfit
Outfit is a geometric sans-serif typeface that balances modernity with warmth. It's available on Google Fonts.

**Font Import:**
```css
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700;800&display=swap');
```

### Type Scale
| Style | Size | Weight | Line Height | Use Case |
|-------|------|--------|-------------|----------|
| Display | 60px | 700 | 1.1 | Hero headlines |
| H1 | 48px | 700 | 1.25 | Page titles |
| H2 | 36px | 700 | 1.25 | Section headers |
| H3 | 30px | 600 | 1.375 | Subsections |
| H4 | 24px | 600 | 1.375 | Card titles |
| H5 | 20px | 500 | 1.5 | Small headers |
| Body Large | 18px | 400 | 1.625 | Lead paragraphs |
| Body | 16px | 400 | 1.5 | Default text |
| Body Small | 14px | 400 | 1.5 | Secondary text |
| Caption | 12px | 400 | 1.5 | Labels, metadata |

### Fallback Fonts
```css
font-family: 'Outfit', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
```

---

## Visual Elements

### Signal Icon
The signal icon (broadcasting dot with wave arcs) is our primary visual motif. It represents:
- Communication
- Broadcasting/notifications
- Connectivity
- Activity/engagement

### Usage Guidelines
- The signal icon can be used independently as a logomark
- Waves should always emanate from left to right
- Maintain the proportional relationship between dot and waves
- Use decreasing opacity for outer waves (100% → 60% → 35%)

### Decorative Applications
- Background patterns using signal motif
- Hero section decorations
- Loading animations
- Empty states

---

## Photography & Imagery

### Style Guidelines
- Clean, modern aesthetic
- High contrast with vibrant colors
- Tech/digital themes preferred
- Avoid cluttered or busy compositions
- People should appear professional and approachable

### Image Treatment
- Apply brand gradient overlays when appropriate
- Use indigo color tints for monotone effects
- Maintain adequate contrast for text overlays

---

## File Naming Convention

```
shipsignal-[asset-type]-[variant]-[size].[format]
```

**Examples:**
- `shipsignal-logo-primary-400x100.png`
- `shipsignal-favicon-32.png`
- `shipsignal-og-default-1200x630.png`
- `shipsignal-profile-instagram-320.png`

---

## Contact

For brand questions or asset requests:
- Email: hello@shipsignal.com
- Website: shipsignal.com

---

*Version 1.0 | Last Updated: 2024*
