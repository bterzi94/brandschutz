# Design System — BrandSchutz Beratung

## 1. Visual Theme & Atmosphere

BrandSchutz Beratung communicates authority, trust, and urgency through a dark navy and orange palette. The deep navy (`#001830`) conveys reliability and institutional weight. The orange (`#f04818`) signals urgency and fire — the core product domain. White surfaces keep the design accessible and modern.

The design adapts a clean, structural layout inspired by Coinbase's layout logic — pill buttons, tight headings, alternating dark/light sections — but replaces the blue accent with the brand's orange for CTAs and highlights. Dark sections use `#001830` (brand navy) rather than near-black.

**Key Characteristics:**
- Brand Navy (`#001830`) as primary dark surface and structural color
- Brand Orange (`#f04818`) as the singular CTA/accent color
- Pill buttons (56px radius) in orange — not blue
- White light sections + navy dark sections
- Tight 1.05 line-height on hero headings
- Cool gray secondary surface (`#f0f2f5`) with neutral tint
- Logo: `assets/images/logo-frei.svg` (white paths, transparent BG — use on navy)

## 2. Color Palette & Roles

### Primary
- **Brand Navy** (`#001830`): Dark sections, nav on scroll, footer
- **Brand Orange** (`#f04818`): Primary CTA, accent, highlights
- **Pure White** (`#ffffff`): Primary light surface, text on navy
- **Cool Gray** (`#f0f2f5`): Secondary section background

### Interactive
- **Orange Hover** (`#d13a10`): Button hover (slightly darker orange)
- **Orange Light** (`#fff1ec`): Orange tint surface (alert boxes, badges)
- **Muted** (`#5b616e`): Secondary text, borders at 20% opacity

### Surface
- **Dark Card** (`#0a1f36`): Cards on navy backgrounds
- **Navy Mid** (`#0d2740`): Secondary dark surface
- **Border** (`rgba(0,24,48,0.12)`): Light section borders

## 3. Typography Rules

### Font Families
- **Display**: `CoinbaseDisplay` — hero headlines
- **UI / Sans**: `CoinbaseSans` — buttons, headings, nav
- **Body**: `CoinbaseText` — reading text
- **Icons**: `CoinbaseIcons` — icon font

### Hierarchy

| Role | Font | Size | Weight | Line Height | Notes |
|------|------|------|--------|-------------|-------|
| Display Hero | CoinbaseDisplay | 80px | 400 | 1.00 (tight) | Maximum impact |
| Display Secondary | CoinbaseDisplay | 64px | 400 | 1.00 | Sub-hero |
| Display Third | CoinbaseDisplay | 52px | 400 | 1.00 | Third tier |
| Section Heading | CoinbaseSans | 36px | 400 | 1.11 (tight) | Feature sections |
| Card Title | CoinbaseSans | 32px | 400 | 1.13 | Card headings |
| Feature Title | CoinbaseSans | 18px | 600 | 1.33 | Feature emphasis |
| Body Bold | CoinbaseSans | 16px | 700 | 1.50 | Strong body |
| Body Semibold | CoinbaseSans | 16px | 600 | 1.25 | Buttons, nav |
| Body | CoinbaseText | 18px | 400 | 1.56 | Standard reading |
| Body Small | CoinbaseText | 16px | 400 | 1.50 | Secondary reading |
| Button | CoinbaseSans | 16px | 600 | 1.20 | +0.16px tracking |
| Caption | CoinbaseSans | 14px | 600–700 | 1.50 | Metadata |
| Small | CoinbaseSans | 13px | 600 | 1.23 | Tags |

## 4. Component Stylings

### Buttons

**Primary Pill (56px radius)**
- Background: `#eef0f3` or `#282b31`
- Radius: 56px
- Border: `1px solid` matching background
- Hover: `#578bfa` (light blue)
- Focus: `2px solid black` outline

**Full Pill (100000px radius)**
- Used for maximum pill shape

**Blue Bordered**
- Border: `1px solid #0052ff`
- Background: transparent

### Cards & Containers
- Radius: 8px–40px range
- Borders: `1px solid rgba(91,97,110,0.2)`

## 5. Layout Principles

### Spacing System
- Base: 8px
- Scale: 1px, 3px, 4px, 5px, 6px, 8px, 10px, 12px, 15px, 16px, 20px, 24px, 25px, 32px, 48px

### Border Radius Scale
- Small (4px–8px): Article links, small cards
- Standard (12px–16px): Cards, menus
- Large (24px–32px): Feature containers
- XL (40px): Large buttons/containers
- Pill (56px): Primary CTAs
- Full (100000px): Maximum pill

## 6. Depth & Elevation

Minimal shadow system — depth from color contrast between dark/light sections.

## 7. Do's and Don'ts

### Do
- Use Brand Orange (`#f04818`) for all primary CTAs and highlights
- Use Brand Navy (`#001830`) for dark sections and footer
- Apply 56px radius for all CTA buttons
- Alternate navy and white sections for visual rhythm
- Always use `logo-frei.svg` on navy backgrounds (white paths visible)

### Don't
- Don't use orange decoratively — it means "action/urgency"
- Don't use sharp corners on CTAs — 56px minimum
- Don't place `logo-frei.svg` on white without adding a navy wrapper

## 8. Responsive Behavior

Breakpoints: 400px, 576px, 640px, 768px, 896px, 1280px, 1440px, 1600px

## 9. Agent Prompt Guide

### Quick Color Reference
- Brand CTA: Orange (`#f04818`) — hover: `#d13a10`
- Brand Dark: Navy (`#001830`)
- Background: White (`#ffffff`)
- Secondary surface: `#f0f2f5`
- Text: `#001830` on white / `#ffffff` on navy
- Accent light: `#fff1ec` (orange tint for badges/alerts)
- Logo file: `assets/images/logo-frei.svg`

### Example Component Prompts
- "Create hero: white background. System font 80px, weight 700, line-height 1.05. Pill CTA (#f04818, 56px radius). Hover: #d13a10."
- "Build dark section: #001830 background. 64px white text. Orange accent link (#f04818)."
- "Nav on navy: use logo-frei.svg inline, white nav links, orange CTA button."
