# Figma Design System Specs

> Complete specifications to rebuild all mockups in Figma or Canva.
> All designs are original — not copied from templates.

---

## 1. Color Tokens

### Palette: Green (MediConnect, EcoStream)
| Token | Hex | Usage |
|-------|-----|-------|
| `green-900` | `#1a3a2e` | Headings |
| `green-700` | `#2d6a4f` | Primary buttons, active states |
| `green-500` | `#40916c` | Hover states |
| `green-300` | `#74a892` | Borders, decorative |
| `green-100` | `#d8eae2` | Tag backgrounds, soft UI |
| `green-50`  | `#f0f5f3` | Sidebar, card backgrounds |

### Palette: Coral (FitTrack, FoodieExpress)
| Token | Hex | Usage |
|-------|-----|-------|
| `coral-800` | `#d04a2a` | Dark hover |
| `coral-600` | `#e85d3a` | Primary accent, CTAs |
| `coral-400` | `#ff7a5a` | Hover, highlights |
| `coral-200` | `#ffc8b8` | Soft backgrounds |
| `coral-100` | `#fce8e0` | Card backgrounds |

### Palette: Gold (CryptoNode)
| Token | Hex | Usage |
|-------|-----|-------|
| `gold-700` | `#c4943a` | Dark variant |
| `gold-500` | `#f0c040` | Primary accent, prices |
| `gold-300` | `#f5d87a` | Hover |
| `gold-100` | `#fce8b8` | Soft bg |

### Palette: Blue (SmartHome)
| Token | Hex | Usage |
|-------|-----|-------|
| `blue-800` | `#1a5ac8` | Dark blue |
| `blue-500` | `#3a86ff` | Toggles active, links |
| `blue-300` | `#6aaaFF` | Hover |
| `blue-100` | `#f0f6ff` | Active card bg |

### Neutrals
| Token | Hex | Usage |
|-------|-----|-------|
| `gray-900` | `#1a1e24` | Body text |
| `gray-700` | `#5a6a7a` | Secondary text |
| `gray-400` | `#aab8c8` | Placeholder, disabled |
| `gray-200` | `#d8e0e8` | Borders |
| `gray-100` | `#eef2f6` | Card borders, dividers |
| `gray-50`  | `#f8fafc` | Page background |

---

## 2. Typography

| Style | Size | Weight | Line Height |
|-------|------|--------|-------------|
| H1 | 48px | 700 | 52px |
| H2 | 36px | 600 | 40px |
| H3 | 24px | 600 | 30px |
| H4 | 18px | 600 | 24px |
| Body | 15px | 400 | 22px |
| Body Small | 13px | 400 | 18px |
| Caption | 12px | 500 | 16px |
| Button | 14px | 500 | 16px |

**Font Stack:** `Inter, -apple-system, sans-serif`

---

## 3. Spacing (4px Base Unit)

| Name | Pixels |
|------|--------|
| `space-1` | 4px |
| `space-2` | 8px |
| `space-3` | 12px |
| `space-4` | 16px |
| `space-5` | 20px |
| `space-6` | 24px |
| `space-8` | 32px |
| `space-10` | 40px |
| `space-12` | 48px |
| `space-16` | 64px |

---

## 4. Component Anatomy

### Buttons
- Padding: 10px 22px
- Radius: 10px
- Font: 14px/500
- Primary: bg `#2d6a4f` / hover `#1e4d38`
- Secondary: bg `#eef2f6` / hover `#d8e0e8`
- Outline: border `1.5px #d8e0e8` / hover border `#2d6a4f`
- Danger: bg `#e85d3a` / hover `#d04a2a`

### Toggle Switch
- Width: 44px / Height: 24px
- Knob: 20px / Radius: 12px
- Active: bg `#3a86ff`

### Cards
- Padding: 20px / Radius: 14px
- Border: 1px `#eef2f6`
- Shadow: 0 4px 12px rgba(0,0,0,0.04)

### Input Fields
- Padding: 12px 16px / Radius: 10px
- Border: 1.5px `#d8e0e8`
- Focus: border `#3a86ff`

### Tags / Badges
- Padding: 4px 14px / Radius: 20px
- Font: 12px/500

---

## 5. Figma Setup Guide

1. Create text styles for all 8 type styles
2. Create color styles for all tokens
3. Frame: 1440px (desktop) / 390px (mobile)
4. Grid: 12 columns / gutter 24px / margins 40px
5. Create components with auto-layout + padding tokens

### Naming Convention
```
Project/
├── Screens/
│   ├── Dashboard
│   ├── Appointments
│   └── Profile
├── Components/
│   ├── Buttons/
│   ├── Cards/
│   ├── Inputs/
│   └── Navigation/
├── Styles/
│   ├── Colors/
│   ├── Typography/
│   └── Effects/
```

---

## 6. Project Design Notes

| Project | Vibe | Key UI Elements |
|---------|------|-----------------|
| **MediConnect** | Calm, accessible | Patient dashboard, appointment cards, doctor grid |
| **FitTrack** | Energetic | SVG progress rings, XP bar, streak badge, workout list |
| **Wanderlust** | Warm, immersive | Full-bleed hero, card grid, gradient overlays |
| **FoodieExpress** | Fast, clean | Map card, order tracking steps, swipe interaction |
| **CryptoNode** | Premium, dark | SVG chart sparkline, ticker pills, coin rows |
| **SmartHome** | Sleek, minimal | Glassmorphism cards, CSS toggles, temp slider |

---

## 7. Canva Import Guide

1. Create a Canva design (Desktop HD or Mobile 360x800)
2. Use hex color codes above in brand palette
3. Set up text styles matching typography scale
4. Build each mockup as a separate page
5. Apply spacing/padding specs
6. Export as PDF or PNG for portfolio

---

*All designs are original — created for UI/UX internship portfolio 2026.*
