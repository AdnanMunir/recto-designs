# Design Context: Recto Designs Revamp

## Design Philosophy
The redesign focuses on a **sleek, visual-first aesthetic** inspired by modern Shopify stores. The goal is to minimize text density and maximize the visual impact of the wooden products.

## Design System

### Typography
- **Headings**: `Space Grotesk` (Google Fonts)
  - Usage: `h1`, `h2`, `h3`, Brand Logo.
  - Characteristics: Geometric, modern, premium feel.
- **Body**: `Inter` (Google Fonts)
  - Usage: Paragraphs, Buttons, Navigation.
  - Characteristics: Clean, highly legible, neutral.

### Color Palette
A "Wood & White" palette designed to let the product photography stand out.

| Token | Value | Description |
|-------|-------|-------------|
| `--color-page` | `#ffffff` | Main page background (Pure White) |
| `--color-surface` | `#f9f8f6` | Section background (Warm Off-White) |
| `--color-surface-alt` | `#f2f0eb` | Secondary section background |
| `--color-primary` | `#1a1a1a` | Primary text and dark elements (Soft Black) |
| `--color-ink-muted` | `#666666` | Secondary text (Medium Grey) |
| `--color-accent` | `#8c735a` | Brand accent (Warm Wood Tone) |
| `--color-border` | `#e5e5e5` | Subtle borders |

### Layout & Spacing
- **Container**: `min(1400px, 94vw)` - Wide layout for immersive visuals.
- **Spacing**: Generous padding (`clamp(6rem, 8vw, 10rem)`) between sections to create "breathing room".
- **Grid**:
  - **Categories**: Masonry-style grid (CSS Grid) with text overlays.
  - **Products**: Clean, uniform grid with minimal metadata.

### UI Components

#### Buttons
- Style: Pill-shaped, uppercase text, wide letter spacing (`0.1em`).
- **Primary**: Solid dark background, white text.
- **Ghost**: Transparent background, dark border.

#### Cards
- **Category Cards**: Full image background, gradient overlay at bottom, text over image. Hover effect: Image scale.
- **Product Cards**: Clean image container (aspect ratio 3:4), title and price below. Minimalist.

#### Hero Section
- Full-screen or near full-screen height (`90vh`).
- Large background image with a subtle dark overlay for text readability.
- Centered or left-aligned bold typography.
