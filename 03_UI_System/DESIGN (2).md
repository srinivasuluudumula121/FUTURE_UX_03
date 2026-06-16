---
name: Executive Operational Minimalist
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#434655'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#747686'
  outline-variant: '#c4c5d7'
  surface-tint: '#2151da'
  primary: '#0037b0'
  on-primary: '#ffffff'
  primary-container: '#1d4ed8'
  on-primary-container: '#cad3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#7f2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#a73400'
  on-tertiary-container: '#ffc9b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b5'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#ffb59c'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#832700'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  xxl: 64px
  container_max: 1200px
  columns: '12'
  gutter: 24px
  margin: 32px
---

## Brand & Style
The design system is engineered for high-velocity B2B operations, specifically tailored for recruitment and CRM workflows where clarity is the primary utility. The brand personality is authoritative yet unobtrusive, prioritizing data density and cognitive ease over decorative elements.

The style is **Professional Minimalism**. It draws inspiration from industry-leading technical platforms like Linear and Stripe, utilizing a rigorous systematic approach to layout. This design system avoids trends like glassmorphism or neomorphism in favor of a "Utility-First" aesthetic: crisp lines, ample negative space used strategically for hierarchy, and a strict adherence to a 4px/8px baseline grid. The emotional response should be one of competence, reliability, and precision.

## Colors
This design system utilizes a high-signal, low-noise palette. 80% of the interface remains within the neutral grayscale spectrum to allow user data and status indicators to stand out.

- **Primary:** A deep, professional blue (#1D4ED8) used for primary actions and active states.
- **Neutrals:** A range of Slate and Zinc tones provide structural depth without adding visual "heat."
- **Semantics:** Status colors (Emerald, Amber, Rose) are reserved strictly for functional feedback—Success, Warning, and Danger.
- **Accents:** Used sparingly to highlight "Hot Leads" or "Priority" items, typically through subtle background tints rather than saturated fills.

## Typography
The system uses **Inter** for its exceptional legibility at small sizes and its neutral, systematic character. 

Hierarchy is established through weight and color rather than drastic size changes. For data-heavy tables and sidebars, `body-sm` (13px) is the standard to optimize information density. Captions and labels use `label-md` with uppercase styling to provide a distinct "meta-data" feel, separating administrative information from primary content. On mobile devices, `display-lg` scales down to 30px to maintain balance.

## Layout & Spacing
The layout follows a **Fixed-Fluid hybrid grid**. The main content area respects a 1200px maximum width for readability on large monitors, centered within a 1440px canvas. 

- **Grid:** A standard 12-column system. 
- **Navigation:** A fixed 240px left-hand sidebar for primary navigation and a 64px top bar for global search and utility.
- **Breakpoints:**
  - **Desktop:** 1200px+ (12 columns, 24px gutter).
  - **Tablet:** 768px - 1199px (8 columns, 16px gutter).
  - **Mobile:** <767px (4 columns, 16px margin, stack layout).
- **Rhythm:** All margins and padding must be multiples of 8px to ensure a clean vertical rhythm.

## Elevation & Depth
Depth is created primarily through **Tonal Layering** and **Micro-Borders** rather than heavy shadows.

- **Level 0 (Base):** White (#FFFFFF) for the main workspace background.
- **Level 1 (Sub-surface):** Soft Gray (#F8FAFC) for sidebars and secondary panels to create structural separation.
- **Level 2 (Cards):** White surfaces with a 1px border (#E2E8F0). Use a very subtle ambient shadow (0px 1px 3px rgba(0,0,0,0.05)) to suggest interactivity.
- **Level 3 (Modals/Popovers):** Standard shadows (0px 10px 15px -3px rgba(0,0,0,0.1)) to draw focus and indicate temporary state.

## Shapes
The system uses **Rounded** geometry (8px radius). This maintains a professional foundation while introducing a more modern, approachable feel that softens the cognitive load of dense data environments.

- **Standard Elements:** 8px (Buttons, Inputs, Badges).
- **Large Elements:** 16px (Cards, Modals, Container segments).
- **Interactive States:** On hover, backgrounds should shift by one tonal step (e.g., White to Slate-50) rather than changing border radius.

## Components

### Buttons
- **Primary:** Solid #1D4ED8, White text. No gradients.
- **Secondary:** White background, 1px #E2E8F0 border, #0F172A text.
- **Ghost:** No border or background, #64748B text. High-contrast blue text on hover.
- **Danger:** Solid #F43F5E for destructive actions.

### Badges (Status Indicators)
Status badges use a "soft pill" style: low-saturation background with high-saturation text for readability.
- **Healthy:** Emerald-100 bg / Emerald-700 text.
- **At Risk:** Amber-100 bg / Amber-700 text.
- **Hot Lead:** Rose-100 bg / Rose-700 text.
- **Completed:** Slate-100 bg / Slate-700 text.

### Tables & Lists
Tables are the workhorse of the system. 
- Headers: `label-md` styling, sticky positioning, subtle bottom border.
- Rows: 56px height, subtle hover highlight (#F8FAFC).
- Cell alignment: Numeric data is tabular-lined; status badges are left-aligned.

### Priority Alert Cards (Component D)
Used in the "Needs Attention Today" panel. 
- Features a thick 4px left-accent border colored by priority level (Red for Overdue, Amber for Waiting Feedback).
- Includes "Quick Action" buttons visible only on hover to reduce visual clutter.

### Visualization
Charts use a muted palette. Use Slate-200 for grid lines. Data series should use Primary Blue, Emerald, and Slate-400. Avoid bright, neon colors in charts to maintain a "Business-First" reporting aesthetic.