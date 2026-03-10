# EvalRig Site — Design System

## Logo
- **Primary lockup**: `logo.svg` — bar chart mark + "EvalRig" wordmark
- **Light background**: `logo-light.svg` — inverted colors for white/light contexts
- **Mark only**: `mark.svg` (64px), `mark-512.png` — icon use without wordmark
- **Favicon**: `favicon.svg` (modern browsers), `favicon-32.png`, `favicon-16.png` (fallback)
- **Apple touch icon**: `apple-touch-icon.png`
- **OG/social image**: `og-image.png` (1200x630)
- **X profile**: `x-profile-400.png` (400x400, circular crop)
- **X banner**: `x-banner-1500x500.png` (1500x500)
- **Full spec**: `evalrig-final-logo-suite.html`

## Colors
| Element | Dark bg (primary) | Light bg (inverted) | Tailwind |
|---------|-------------------|---------------------|----------|
| Top bar | `#CBD5E1` 100% | `#1E293B` 100% | slate-300 / slate-800 |
| Middle bar | `#CBD5E1` 45% | `#1E293B` 50% | slate-300/45 / slate-800/50 |
| Bottom bar + arrow | `#3B82F6` | `#2563EB` | blue-500 / blue-600 |
| "Eval" text | `#F1F5F9` | `#0F172A` | slate-50 / slate-900 |
| "Rig" text | `#3B82F6` | `#2563EB` | blue-500 / blue-600 |

### Site palette (CSS custom properties)
- `--bg`: `#0a0a0b` — page background
- `--surface`: `#141416` — cards, stat boxes
- `--border`: `#23232a` — borders
- `--text`: `#e4e4e7` — primary text
- `--text-muted`: `#8b8b94` — secondary text
- `--accent`: `#6366f1` — links, highlights, CTA
- `--accent-hover`: `#818cf8` — hover states

## Typography
- **Headings (h1, h2), section labels, step numbers**: JetBrains Mono (600/700/800) via Google Fonts
  - Signals "technical tool / precision / data" — fits an AI benchmarking product
  - Logo SVG wordmark also uses JetBrains Mono Bold, -0.5px tracking
- **Body text, tables, descriptions**: System font stack (`-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`)
  - Better readability for data-heavy content

## Logo sizing
- Site header: `80px` height (auto width)
- h1 tagline below: `40px` (28px on mobile)

## Social meta
- Open Graph and Twitter Card meta tags in `<head>`
- OG image: `https://evalrig.ai/og-image.png`
