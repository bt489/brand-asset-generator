# ShipSignal Figma Specifications

## Quick Reference

### Brand Colors (Copy to Figma)
```
Primary:     #4f46e5
Accent:      #6366f1
Light:       #818cf8
Lighter:     #a5b4fc
Pale:        #c7d2fe
Dark BG:     #1e1b4b
Dark Mid:    #312e81
Dark Light:  #3730a3
```

### Typography
**Font:** Outfit (Google Fonts)
**Weights:** 400, 500, 600, 700

---

## Logo Specifications

### Primary Logo (Horizontal)
- **Width:** 200px (at default scale)
- **Logomark:** 50px diameter circle + wave arcs
- **Spacing:** 15px between logomark and wordmark
- **Wordmark:** Outfit Bold, 42px

### Stacked Logo (Vertical)
- **Width:** 140px
- **Logomark:** 70px height
- **Spacing:** 15px below logomark
- **Wordmark:** Outfit Bold, 32px

### Logomark Only
- **Default:** 50x50px
- **Large:** 100x100px
- **Small:** 24x24px

---

## Social Media Dimensions

### X/Twitter
| Asset | Dimensions | Notes |
|-------|------------|-------|
| Profile | 400x400px | Circle crop |
| Header | 1500x500px | Safe zone: center 1200x400 |
| Post | 1200x675px | 16:9 ratio |
| Card | 800x418px | Summary card |

### Instagram
| Asset | Dimensions | Notes |
|-------|------------|-------|
| Profile | 320x320px | Circle crop |
| Square Post | 1080x1080px | Feed |
| Portrait Post | 1080x1350px | 4:5 ratio |
| Story | 1080x1920px | 9:16 ratio |
| Highlight | 110x110px | Circle icons |

### LinkedIn
| Asset | Dimensions | Notes |
|-------|------------|-------|
| Profile | 400x400px | Circle crop |
| Banner | 1128x191px | Company page |
| Post Square | 1200x1200px | Best engagement |
| Post Landscape | 1200x628px | Link preview |

### Facebook
| Asset | Dimensions | Notes |
|-------|------------|-------|
| Profile | 400x400px | Circle crop |
| Cover | 820x312px | Desktop optimized |
| Post | 1200x630px | Standard |

### YouTube
| Asset | Dimensions | Notes |
|-------|------------|-------|
| Profile | 800x800px | Circle crop |
| Banner | 2560x1440px | Safe zone: 1546x423 center |
| Thumbnail | 1280x720px | 16:9 |
| Watermark | 150x150px | Transparent BG |

---

## Web Assets

### Open Graph / Social Sharing
| Asset | Dimensions |
|-------|------------|
| OG Default | 1200x630px |
| Twitter Card | 1200x600px |

### Favicons
| Asset | Dimensions |
|-------|------------|
| favicon.ico | 16, 32, 48px |
| favicon-16.png | 16x16px |
| favicon-32.png | 32x32px |
| favicon-192.png | 192x192px |
| favicon-512.png | 512x512px |
| apple-touch-icon | 180x180px |

---

## Display Ads (IAB Standard)

| Format | Dimensions |
|--------|------------|
| Leaderboard | 728x90px |
| Medium Rectangle | 300x250px |
| Wide Skyscraper | 160x600px |
| Mobile Banner | 320x50px |
| Large Mobile | 320x100px |

---

## Video Assets

| Asset | Dimensions | Notes |
|-------|------------|-------|
| Zoom Background | 1920x1080px | 16:9 HD |
| Lower Third | 480x110px | Overlay element |
| Video Outro | 1920x1080px | End screen |
| Podcast Cover | 3000x3000px | Square, high-res |

---

## Document Templates

| Asset | Dimensions |
|-------|------------|
| Letterhead | 8.5x11" (612x792pt) |
| Business Card | 3.5x2" (252x144pt) |
| Presentation | 1920x1080px (16:9) |

---

## Component Styles

### Buttons

**Primary Button**
- Background: `#4f46e5`
- Text: `#ffffff`, Outfit 600, 16px
- Padding: 16px 32px
- Border Radius: 8px (or full-round: 9999px)
- Hover: `#4338ca`

**Secondary Button**
- Background: transparent
- Border: 2px solid `#6366f1`
- Text: `#6366f1`, Outfit 600, 16px
- Padding: 14px 30px
- Border Radius: 8px

**Ghost Button**
- Background: transparent
- Text: `#6366f1`, Outfit 500, 16px
- Hover: Background `#eef2ff`

### Cards

**Standard Card**
- Background: `#ffffff`
- Border: 1px solid `#e5e7eb`
- Border Radius: 12px
- Shadow: `0 1px 3px rgba(0,0,0,0.1)`
- Padding: 24px

**Feature Card**
- Background: linear-gradient(135deg, `#4f46e5`, `#6366f1`)
- Border Radius: 16px
- Padding: 32px
- Text: `#ffffff`

### Input Fields

- Border: 1px solid `#d1d5db`
- Border Radius: 8px
- Padding: 12px 16px
- Focus Border: `#6366f1`
- Font: Outfit 400, 16px

---

## Spacing Scale

```
4px   - xs
8px   - sm
12px  - md
16px  - base
24px  - lg
32px  - xl
48px  - 2xl
64px  - 3xl
96px  - 4xl
```

---

## Shadow Scale

```css
/* Small */
box-shadow: 0 1px 2px rgba(0,0,0,0.05);

/* Medium */
box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);

/* Large */
box-shadow: 0 10px 15px -3px rgba(0,0,0,0.1);

/* XL */
box-shadow: 0 25px 50px -12px rgba(0,0,0,0.25);
```

---

## Export Settings

### SVG
- Outline strokes: No (keep editable)
- Embed fonts: No (reference Outfit)

### PNG
- Resolution: 2x for retina displays
- Background: Transparent where applicable

### JPG
- Quality: 85-90%
- Use for: Photos, complex gradients, large backgrounds
