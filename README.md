# Brand Asset Generator Prompt

Turn one logo into 70+ brand assets using AI.

## What This Does

Give the prompt your logo and it generates:

- **7 Logo Variations** - Primary, stacked, logomark, wordmark, monochrome versions
- **Favicon System** - 16px to 512px, including Apple touch icon
- **Social Media Kit** - Instagram, Facebook, LinkedIn, Twitter/X, YouTube (profiles, covers, templates)
- **Web Assets** - OG images, Twitter cards, loading states, error pages
- **Display Ads** - Leaderboard, rectangles, skyscrapers, mobile banners
- **Business Documents** - Letterhead, business cards, presentation slides
- **Email Assets** - Headers, footers, HTML signature template
- **Video/Motion** - Lower thirds, outros, Zoom backgrounds, podcast covers
- **Design Tokens** - CSS variables, JSON for Figma/design tools
- **Brand Guidelines** - Usage rules, specs, component documentation

## How to Use

1. Copy `branding-agent-prompt.md`
2. Point it at your existing logo file
3. Run it in Claude Code (or adapt for other AI tools)
4. Get your complete brand asset library

## The Prompt

The prompt simulates a full branding team:

- **Brand Strategist** - Ensures consistency across all assets
- **Visual Designer** - Creates production-ready files
- **UX/UI Specialist** - Optimizes for digital interfaces
- **Social Media Expert** - Handles platform-specific requirements
- **Motion Designer** - Video and animation assets
- **Production Specialist** - Ensures correct specs and formats

See `branding-agent-prompt.md` for the full prompt.

## Output Structure

```
branding-design/
├── logos/              # 7 logo variations
├── favicons/           # All favicon sizes
├── tokens/             # CSS + JSON design tokens
├── web/                # OG images, headers, states
├── social/
│   ├── instagram/      # Posts, stories, highlights
│   ├── facebook/       # Cover, posts
│   ├── linkedin/       # Banner, posts
│   ├── twitter/        # Header, posts
│   └── youtube/        # Banner, thumbnails, watermark
├── email/              # Headers, footers, signature
├── ads/                # Display ad sizes
├── documents/          # Letterhead, cards, slides
├── video/              # Lower thirds, outros, backgrounds
├── patterns/           # Brand patterns, gradients
└── specs/              # Guidelines, Figma specs, component specs
```

## File Formats

All assets are SVG for:
- Infinite scalability
- Easy color editing
- Small file sizes
- Convert to PNG/JPG as needed

## Example Output

This repo includes a complete example generated for "ShipSignal" - a fictional notifications product. Use it as reference for what the prompt produces.

## Converting to PNG

SVGs can be converted using:
- **Inkscape** (free, desktop)
- **ImageMagick** (command line)
- **svgtopng.com** (online)
- **Figma** (import and export)

## Customization

The prompt is modular. Skip sections you don't need:
- Only need social? Ask for Phase 3 only
- Just want logos? Stop after Phase 2
- Need ads? Request Phase 3.4 specifically

## Credits

Built with Claude Code by [@BThompson15944](https://x.com/BThompson15944)

## License

MIT - Use freely, attribution appreciated.
