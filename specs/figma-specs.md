# ShipSignal Figma Design Specifications

This document provides all specifications needed to recreate the ShipSignal brand assets in Figma or other design tools.

---

## Color Styles

### Create these color styles in Figma:

```
Brand/Indigo-900    #312e81
Brand/Indigo-800    #3730a3
Brand/Indigo-700    #4338ca
Brand/Indigo-600    #4f46e5
Brand/Indigo-500    #6366f1
Brand/Indigo-400    #818cf8
Brand/Indigo-300    #a5b4fc
Brand/Indigo-200    #c7d2fe
Brand/Indigo-100    #e0e7ff
Brand/Indigo-50     #eef2ff

Neutral/Gray-900    #111827
Neutral/Gray-800    #1f2937
Neutral/Gray-700    #374151
Neutral/Gray-600    #4b5563
Neutral/Gray-500    #6b7280
Neutral/Gray-400    #9ca3af
Neutral/Gray-300    #d1d5db
Neutral/Gray-200    #e5e7eb
Neutral/Gray-100    #f3f4f6
Neutral/Gray-50     #f9fafb
Neutral/White       #ffffff

Semantic/Success    #10b981
Semantic/Warning    #f59e0b
Semantic/Error      #ef4444
Semantic/Info       #3b82f6
```

---

## Text Styles

### Font Setup
1. Install "Outfit" from Google Fonts
2. Create these text styles:

| Style Name | Font | Weight | Size | Line Height | Letter Spacing |
|------------|------|--------|------|-------------|----------------|
| Display | Outfit | Bold (700) | 60px | 66px (110%) | -0.02em |
| Heading/H1 | Outfit | Bold (700) | 48px | 60px (125%) | -0.025em |
| Heading/H2 | Outfit | Bold (700) | 36px | 45px (125%) | -0.025em |
| Heading/H3 | Outfit | SemiBold (600) | 30px | 41px (137.5%) | 0 |
| Heading/H4 | Outfit | SemiBold (600) | 24px | 33px (137.5%) | 0 |
| Heading/H5 | Outfit | Medium (500) | 20px | 30px (150%) | 0 |
| Heading/H6 | Outfit | Medium (500) | 18px | 27px (150%) | 0 |
| Body/Large | Outfit | Regular (400) | 18px | 29px (162.5%) | 0 |
| Body/Default | Outfit | Regular (400) | 16px | 24px (150%) | 0 |
| Body/Small | Outfit | Regular (400) | 14px | 21px (150%) | 0 |
| Caption | Outfit | Regular (400) | 12px | 18px (150%) | 0 |
| Label | Outfit | Medium (500) | 12px | 12px (100%) | 0.05em |
| Logo | Outfit | Bold (700) | 32px | Auto | -0.025em |

---

## Effect Styles (Shadows)

```
Shadow/SM
  X: 0, Y: 1, Blur: 2, Spread: 0
  Color: #000000, Opacity: 5%

Shadow/MD
  Layer 1: X: 0, Y: 4, Blur: 6, Spread: -1, Color: #000000 10%
  Layer 2: X: 0, Y: 2, Blur: 4, Spread: -2, Color: #000000 10%

Shadow/LG
  Layer 1: X: 0, Y: 10, Blur: 15, Spread: -3, Color: #000000 10%
  Layer 2: X: 0, Y: 4, Blur: 6, Spread: -4, Color: #000000 10%

Shadow/Brand
  X: 0, Y: 4, Blur: 14, Spread: 0
  Color: #6366f1, Opacity: 25%
```

---

## Logo Construction

### Primary Logo (210 x 50)
1. Create text "ShipSignal" - Outfit Bold, 32px
2. Apply gradient fill: #4f46e5 → #818cf8 (horizontal)
3. Signal Icon (positioned right of text):
   - Dot: Circle, 10px diameter, fill #6366f1, position X: 174, Y: 28
   - Wave 1: Arc stroke, 2px, #818cf8, 50% opacity
   - Wave 2: Arc stroke, 2px, #a5b4fc, 35% opacity

### Signal Icon Only (64 x 64)
1. Signal dot: Circle, 16px diameter, gradient fill
2. Wave 1: Arc, 3px stroke, #6366f1, 100%
3. Wave 2: Arc, 3px stroke, #818cf8, 60%
4. Wave 3: Arc, 3px stroke, #a5b4fc, 35%

### Arc Specifications
Waves are quarter-circle arcs (90°) curving from top to bottom on the right side of the dot.

---

## Asset Dimensions

### Favicons
| Asset | Size | Corner Radius |
|-------|------|---------------|
| favicon-16.svg | 16 x 16 | 3px |
| favicon-32.svg | 32 x 32 | 6px |
| favicon-192.svg | 192 x 192 | 32px |
| favicon-512.svg | 512 x 512 | 80px |
| apple-touch-icon.svg | 180 x 180 | 30px |

### Social Media
| Platform | Asset | Dimensions |
|----------|-------|------------|
| Universal | Profile | 400 x 400 |
| YouTube | Profile | 800 x 800 |
| Instagram | Profile | 320 x 320 |
| Instagram | Post Square | 1080 x 1080 |
| Instagram | Post Portrait | 1080 x 1350 |
| Instagram | Story | 1080 x 1920 |
| Facebook | Cover | 820 x 312 |
| Facebook | Post | 1200 x 630 |
| LinkedIn | Banner | 1128 x 191 |
| LinkedIn | Post Square | 1200 x 1200 |
| LinkedIn | Post Landscape | 1200 x 628 |
| Twitter/X | Header | 1500 x 500 |
| Twitter/X | Post | 1200 x 675 |
| YouTube | Banner | 2560 x 1440 |
| YouTube | Thumbnail | 1280 x 720 |
| YouTube | Watermark | 150 x 150 |

### Web
| Asset | Dimensions |
|-------|------------|
| OG Image | 1200 x 630 |
| Twitter Card | 1200 x 600 |
| Header Logo | 160 x 40 |

### Display Ads
| Format | Dimensions |
|--------|------------|
| Leaderboard | 728 x 90 |
| Medium Rectangle | 300 x 250 |
| Wide Skyscraper | 160 x 600 |
| Mobile Banner | 320 x 50 |
| Mobile Banner Large | 320 x 100 |

### Documents
| Asset | Dimensions |
|-------|------------|
| Letterhead | 612 x 792 (US Letter at 72dpi) |
| Business Card | 252 x 144 (3.5" x 2" at 72dpi) |
| Presentation | 960 x 540 (16:9) |

### Video
| Asset | Dimensions |
|-------|------------|
| Lower Third | 1920 x 1080 |
| Video Outro | 1920 x 1080 |
| Zoom Background | 1920 x 1080 |
| Podcast Cover | 3000 x 3000 |

---

## Gradient Definitions

### Primary Gradient
```
Type: Linear
Angle: 90° (horizontal, left to right)
Stops:
  0%: #4f46e5
  100%: #818cf8
```

### Light Gradient (Dark mode text)
```
Type: Linear
Angle: 90°
Stops:
  0%: #818cf8
  100%: #c7d2fe
```

### Dark Gradient (Backgrounds)
```
Type: Linear
Angle: 135° (diagonal)
Stops:
  0%: #312e81
  50%: #4f46e5
  100%: #6366f1
```

### Radial Gradient
```
Type: Radial
Center: 50% 50%
Stops:
  0%: #6366f1
  100%: #4f46e5
```

---

## Component Specifications

### Buttons
| Variant | Background | Text | Border Radius | Padding |
|---------|------------|------|---------------|---------|
| Primary | #6366f1 | #ffffff | 9999px (full) | 16px 32px |
| Secondary | transparent | #6366f1 | 9999px | 16px 32px |
| Ghost | transparent | #6b7280 | 8px | 12px 24px |

### Cards
```
Background: #ffffff
Border: 1px solid #e5e7eb
Border Radius: 12px
Padding: 24px
Shadow: Shadow/MD
```

### Input Fields
```
Background: #ffffff
Border: 1px solid #d1d5db
Border Radius: 8px
Padding: 12px 16px
Height: 48px
Focus Border: #6366f1
```

---

## Spacing Scale

| Token | Value |
|-------|-------|
| space-1 | 4px |
| space-2 | 8px |
| space-3 | 12px |
| space-4 | 16px |
| space-5 | 20px |
| space-6 | 24px |
| space-8 | 32px |
| space-10 | 40px |
| space-12 | 48px |
| space-16 | 64px |
| space-20 | 80px |
| space-24 | 96px |

---

## Border Radius Scale

| Token | Value |
|-------|-------|
| radius-sm | 4px |
| radius-md | 6px |
| radius-lg | 8px |
| radius-xl | 12px |
| radius-2xl | 16px |
| radius-3xl | 24px |
| radius-full | 9999px |

---

*For questions about implementation, refer to the design tokens in `/tokens/` folder.*
