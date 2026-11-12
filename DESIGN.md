---
name: Python Conf Pereira 2026
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c1c7d0'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#8b919a'
  outline-variant: '#41474f'
  surface-tint: '#98cbff'
  primary: '#98cbff'
  on-primary: '#003354'
  primary-container: '#3776ab'
  on-primary-container: '#f5f8ff'
  inverse-primary: '#1d6296'
  secondary: '#6fdf43'
  on-secondary: '#0e3900'
  secondary-container: '#39a900'
  on-secondary-container: '#0c3400'
  tertiary: '#ecc328'
  on-tertiary: '#3c2f00'
  tertiary-container: '#cea700'
  on-tertiary-container: '#4e3e00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#98cbff'
  on-primary-fixed: '#001d33'
  on-primary-fixed-variant: '#004a77'
  secondary-fixed: '#8afd5d'
  secondary-fixed-dim: '#6fdf43'
  on-secondary-fixed: '#052100'
  on-secondary-fixed-variant: '#185200'
  tertiary-fixed: '#ffe082'
  tertiary-fixed-dim: '#ecc228'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#564500'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  headline-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  code-block:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system establishes a high-performance, developer-first identity bridging academic innovation (SENA Regional Risaralda) and global software engineering culture (Python community). The personality is rigorous, modern, and open, balancing institutional authority with energetic developer community ethos. 

The visual style blends dark modern tech minimalism with subtle glassmorphic elements and high-precision code accents. Deep neutral slates host focused accents of Python blue and SENA institutional green, maintaining WCAG AAA compliance across interactive contexts. The system conveys reliability, speed, and forward-looking technical mastery suitable for international developer keynotes, technical workshops, and real-time scheduling.

## Colors

The palette is engineered for high contrast and prolonged viewing in dark environments:
- **Primary (`#3776AB`)**: Python Blue serves as the structural anchor for primary interactive states, navigational headers, active link underlines, and primary badges.
- **Secondary (`#39A900`)**: SENA Green acts as the vibrant affirmative accent, used for live status indicators, registration CTAs, success states, and keynote spotlight treatments. A deeper `#246B00` variant supports high-contrast backgrounds behind white text.
- **Tertiary (`#FFD43B`)**: Python Warm Yellow is reserved for contextual highlights, speaker badges, conference track warnings, and syntax token accents.
- **Neutral Dark (`#0F172A` / `#111827`)**: Layered slate grays build atmospheric depth, avoiding pure pitch black to eliminate eye fatigue.
- **Neutral Light (`#F8FAFC` / `#FFFFFF`)**: Pure white and crisp light slates ensure typography meets 7:1 contrast ratios against dark containers.

## Typography

The typography structure uses `Inter` for all structural content and conversational UI, paired with `JetBrains Mono` for developer annotations, schedules, talk tracks, and technical specifications.

- **Headlines**: Set tightly with negative tracking (`-0.02em`) to provide punchy, editorial impact across conference hero sections.
- **Body**: Generously spaced with a 1.5x line height ratio to guarantee readability across documentation, speaker bios, and abstracts.
- **Labels & Code**: `JetBrains Mono` provides immediate monospaced recognition for timestamps, session rooms (e.g., `EXP-ROOM-01`), syntax highlights, and API payload demos.

## Layout & Spacing

The layout operates on a standard 12-column responsive fluid grid on desktop (`>1024px`), transitioning to an 8-column layout on tablets (`768px-1023px`), and a 4-column layout on mobile devices (`<768px`).

- **Grid Alignment**: Components snap to an 8px base rhythm. Micro-adjustments and badge vertical padding adhere to a 4px sub-grid.
- **Section Margins**: Outer frame padding scales dynamically from `1rem` on mobile to `2rem` on desktop displays to maximize viewport usage for multi-track schedules.
- **Density**: High data density in schedule grids and workshop listings, contrasting with open, generous margins in hero landing sections and keynote profiles.

## Elevation & Depth

Visual hierarchy uses layered dark surfaces combined with subtle glassmorphic translucency rather than heavy opaque drop shadows:

- **Surface Base**: Slate background (`#0F172A`) acts as the canvas.
- **Surface Elevation 1 (Cards & Modules)**: Translucent surface `#1E293B` at 80% opacity paired with `backdrop-filter: blur(12px)`.
- **Surface Elevation 2 (Modals & Overlays)**: Surface `#334155` at 90% opacity with `backdrop-filter: blur(16px)` and an ambient shadow: `0 20px 25px -5px rgba(0, 0, 0, 0.45), 0 8px 10px -6px rgba(0, 0, 0, 0.4)`.
- **Borders & Edge Traces**: 1px subtle gradient borders (`linear-gradient(135deg, rgba(255,255,255,0.12), rgba(55,118,171,0.25))`) to crisply delineate card edges without visually cluttering the layout.

## Shapes

The design uses a clean, engineered corner profile calibrated to `roundedness: 2` (base 0.5rem / 8px). 

- **Inputs, Buttons, and Chips**: Use `0.5rem` (8px) radius, conveying modern utility while remaining crisp.
- **Panels, Glass Cards, and Terminal Blocks**: Use `rounded-lg` (1rem / 16px) for softened, balanced visual containment.
- **Overlays, Floating Modals, and Main Viewports**: Use `rounded-xl` (1.5rem / 24px) for distinct focal isolation.
- **Pills**: Reserved strictly for micro-status indicators (e.g., "LIVE NOW", "KEYNOTE") with fully rounded geometry.

## Components

### Buttons
- **Primary (SENA Green CTA)**: Solid `#39A900` fill with white text (`#FFFFFF`), `font-weight: 600`, 8px roundedness. Hover triggers an elevation glow: `box-shadow: 0 0 16px rgba(57, 169, 0, 0.4)`.
- **Secondary (Python Blue)**: Solid `#3776AB` fill with white text, 8px roundedness. Hover scales brightness by 10%.
- **Ghost / Outlined**: Transparent background with 1px border (`rgba(255, 255, 255, 0.2)`), text in `#F8FAFC`. On hover, fills with `rgba(55, 118, 171, 0.15)` and border transitions to `#3776AB`.

### Chips & Badges
- **Track Indicators**: Compact badge using `JetBrains Mono` 12px. Background at 15% opacity of respective accent color (Blue for Backend/Python, Green for Open Source/SENA, Yellow for Data/AI). Borders match token color at 30% opacity.

### Schedule Cards (Glassmorphism)
- Background: `rgba(30, 41, 59, 0.75)` with `backdrop-filter: blur(10px)`.
- Border: 1px continuous hairline gradient (`rgba(255, 255, 255, 0.08)` to `rgba(55, 118, 171, 0.3)`).
- Padding: `1.5rem` (`space-lg`). Content includes monospaced start/end times in `#FFD43B` and speaker details in `Inter`.

### Form Inputs & Code Search
- Surface: `#0F172A` inset box with `1px` border in `#334155`.
- Focus State: Border snaps to `#3776AB` with a 2px outer ring in `rgba(55, 118, 171, 0.3)`. Text renders in crisp white with `#94A3B8` placeholders.

### Selection Controls
- **Checkboxes & Radios**: 8px rounded checkboxes and circular radios with `#1E293B` unselected fill and `#475569` border. Selected state fills with `#39A900` featuring a white checkmark or center dot.

### Code Snippets & Terminal Blocks
- Dark container (`#0B0F19`) topped by a faux mac/linux window header bar with room for file badges (`main.py`) in `JetBrains Mono`. Syntax highlighting respects Python standard library conventions under AAA contrast standards.