---
name: Luminous Engineering Portfolio
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#bcc9cd'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#869397'
  outline-variant: '#3d494c'
  surface-tint: '#4cd7f6'
  primary: '#4cd7f6'
  on-primary: '#003640'
  primary-container: '#06b6d4'
  on-primary-container: '#00424f'
  inverse-primary: '#00687a'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#c0c1ff'
  on-tertiary: '#1000a9'
  tertiary-container: '#9a9dff'
  on-tertiary-container: '#211cb4'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#acedff'
  primary-fixed-dim: '#4cd7f6'
  on-primary-fixed: '#001f26'
  on-primary-fixed-variant: '#004e5c'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
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
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses a high-craft, technical, and engineering-centric portfolio for a full-stack engineer. The visual identity anchors on precision, performance, and modern digital craft.

- **Brand Personality**: Authoritative, analytical, meticulously structured, and forward-looking. It balances deep technical competence with polished presentation.
- **Target Audience**: Engineering leads, technical recruiters, startup founders, and enterprise clients seeking senior craftsmanship across full-stack web architectures.
- **Emotional Response**: Evokes focus, computational speed, trust, and refined tactile control.
- **Aesthetic Direction**: Deep dark-mode minimalism infused with subtle glassmorphic depth, luminous terminal-inspired accents, micro-borders, and high-legibility geometric typography.

## Colors

The palette is rooted in an abyss-level dark architecture with luminous, high-clarity spectral accents:

- **Canvas & Backgrounds**:
  - Base canvas: `#0B0F17` (Obsidian Void).
  - Elevated surfaces / cards: `#111827` (Charcoal Slate) and `#1E293B` (Muted Indigo Gray).
- **Accents**:
  - Primary (`#06B6D4` - Cyber Cyan): Core interactive touchpoints, active states, key data highlights, and terminal command markers.
  - Secondary (`#10B981` - Emerald Matrix): Status badges, production deployment states, Git commit trees, and validated test indicators.
  - Tertiary (`#6366F1` - Hyper Indigo): Architecture diagrams, stack categorization chips, and secondary hover highlights.
- **Text & Foreground**:
  - Primary text: `#F9FAFB` (98% contrast against base).
  - Secondary text: `#94A3B8` (Subtle metadata, descriptive copy).
  - Tertiary / Muted: `#64748B` (Line numbers, disabled states, grid lines).
- **Borders & Dividers**:
  - Hairline glass stroke: `rgba(255, 255, 255, 0.08)`.
  - Focused / Active border: `rgba(6, 182, 212, 0.45)`.

## Typography

The typographic hierarchy pairs modern geometric display forms with an unyielding, utilitarian body and monospace detailing:

- **Headlines & Display (Plus Jakarta Sans)**: High-precision geometric sans with tightened tracking for punchy, impactful section titles and key project callouts.
- **Body & Paragraphs (Inter)**: Industry-standard neutral grotesque designed for optimal legibility at micro and macro body scales against high-contrast dark backgrounds.
- **Technical & Tags (JetBrains Mono)**: Applied to syntax chips, code snippets, git hashes, terminal inputs, metrics, and technology tag indicators.

## Layout & Spacing

A structured fluid layout grounded in standard 12-column engineering symmetry, fully aligned with Bootstrap's responsive grid system:

- **Breakpoints**:
  - `sm`: 576px
  - `md`: 768px
  - `lg`: 992px
  - `xl`: 1200px
  - `xxl`: 1400px
- **Grid Architecture**:
  - Standard maximum container width: `1280px` for optimal reading length and showcase width.
  - Desktop: 12 columns with `1.5rem` (`24px`) gutters and `2rem` outer margins.
  - Mobile: Single- or two-column stacked layouts utilizing `1rem` gutters and `1.25rem` outer margins.
- **Rhythm**: All layout blocks adhere strictly to an 8pt vertical cadence (base unit `0.5rem` / `8px`), ensuring consistent baseline alignments across asymmetric multi-column project cards and metrics sidebars.

## Elevation & Depth

Visual hierarchy does not rely on conventional drop shadows. Instead, it utilizes surface luminescence, semi-transparent frosted planes, and low-contrast borders:

- **Layer 0 (Canvas Base)**: Flat `#0B0F17`.
- **Layer 1 (Subtle Containers / Panels)**: `#111827` at 70% opacity with `backdrop-filter: blur(12px)` and a continuous hairline border of `rgba(255, 255, 255, 0.06)`.
- **Layer 2 (Interactive Floating Surfaces / Modals / Active Cards)**: `#1E293B` at 80% opacity with `backdrop-filter: blur(20px)`, a `rgba(255, 255, 255, 0.12)` border, and an ambient colored radial glow (`0 0 32px -8px rgba(6, 182, 212, 0.15)`).
- **Layer 3 (Overlays & Tooltips)**: Solid `#0F172A` with a razor-thin `#06B6D4` border accent.

## Shapes

The design uses a refined, modern curvature level (`2` / rounded):

- **Standard Containers & Cards**: `0.5rem` (`8px`) border-radius, imparting a tight, technical hardware feel.
- **Large Panels & Modals (`rounded-lg`)**: `1rem` (`16px`) for primary structural wrappers.
- **Pills & Micro-Badges**: Full pill radials (`9999px`) reserved exclusively for status indicators, micro tech stack tags, and small pill buttons.

## Components

### Buttons
- **Primary Action**: Solid `#06B6D4` background, `#0B0F17` ultra-bold text, `0.5rem` radius, subtle cyan outer glow on hover (`0 0 20px rgba(6, 182, 212, 0.35)`).
- **Secondary Action (Ghost / Wire)**: `rgba(255, 255, 255, 0.04)` fill, `1px solid rgba(255, 255, 255, 0.12)` border, `#F9FAFB` text. Transitions to `border-color: #06B6D4` and cyan text glow on hover.
- **Monospace Action**: JetBrains Mono uppercase, accompanied by terminal prompt icons (`>`, `$`).

### Project & Case Study Cards
- Frosted dark container (`rgba(17, 24, 39, 0.8)`) with `1px` subtle outline (`rgba(255, 255, 255, 0.07)`).
- Card headers feature live stack icons (PHP, JS, CSS, Bootstrap) rendered in low-saturation monochromatic gray that illuminate into full accent color on hover.
- Internal padding matches `space-lg` (`1.5rem`).

### Chips & Badges
- **Tech Stack Badges**: Compact padding (`0.25rem 0.625rem`), JetBrains Mono `12px`, background `rgba(255, 255, 255, 0.05)`, border `rgba(255, 255, 255, 0.1)`.
- **Status Badges (e.g., "Available for Hire", "Production Ready")**: Pill-shaped with a pulsating emerald dot (`#10B981`) and emerald-tinted background `rgba(16, 185, 129, 0.1)`.

### Form Fields & Inputs
- Dark recessed background (`#0A0E17`), `1px solid rgba(255, 255, 255, 0.1)`.
- Focus state: Border shifts to `#06B6D4` with a tight `0 0 0 2px rgba(6, 182, 212, 0.2)` ring.
- Placeholder text in `#64748B`.

### Code Blocks & Architecture Windows
- Styled as terminal panes with simulated macOS window controls (three muted dots: red, amber, green).
- JetBrains Mono typography with customized syntax highlighting optimized for PHP and JavaScript code samples.