---
name: Momentic Technical Interface
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#3e4b35'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#6e7b63'
  outline-variant: '#bdcbaf'
  surface-tint: '#2b6c00'
  primary: '#2b6c00'
  on-primary: '#ffffff'
  primary-container: '#72ff13'
  on-primary-container: '#2e7200'
  inverse-primary: '#61e200'
  secondary: '#5e5e62'
  on-secondary: '#ffffff'
  secondary-container: '#e0dfe3'
  on-secondary-container: '#626266'
  tertiary: '#5b5e66'
  on-tertiary: '#ffffff'
  tertiary-container: '#dfe1ea'
  on-tertiary-container: '#61646c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7fff36'
  primary-fixed-dim: '#61e200'
  on-primary-fixed: '#082100'
  on-primary-fixed-variant: '#1f5100'
  secondary-fixed: '#e3e2e6'
  secondary-fixed-dim: '#c7c6ca'
  on-secondary-fixed: '#1b1b1f'
  on-secondary-fixed-variant: '#46464a'
  tertiary-fixed: '#e0e2eb'
  tertiary-fixed-dim: '#c4c6cf'
  on-tertiary-fixed: '#181c22'
  on-tertiary-fixed-variant: '#44474e'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  metric-display:
    fontFamily: JetBrains Mono
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 3rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies high-precision developer tooling, autonomous engineering infrastructure, and enterprise QA intelligence. Built around an austere yet electric aesthetic, it communicates determinism, speed, and mathematical clarity. 

The visual personality combines strict architectural minimalism with moments of high-energy signaling:
- **High-Contrast Minimalism:** Monochromatic foundational surfaces ranging from stark light canvases to void-like deep blacks (`#0A0A0A`).
- **Precision Engineering Cues:** Hairline structural borders, crisp grid cells, index counters (`01`, `02`), monospaced telemetry data, and tight metric lockups.
- **Electric Accentuation:** High-potency electric lime (`#72FF13`) reserved strictly for primary conversions, active execution states, and critical positive telemetry.
- **Bilingual Rigor:** Built with native parity for Latin and Arabic typography, maintaining exact metric rhythm and tabular alignment across LTR and RTL orientations.

## Colors

The palette operates on extreme dynamic range: high-value neon accents balanced against monochrome neutral structures.

- **Primary (`#72FF13`):** The signature electric lime. Used exclusively for focal call-to-actions, primary interactive triggers, successful test execution badges, and active operational signals. Always pair text over primary with absolute black (`#000000`) for WCAG AAA compliance.
- **Secondary (`#0D0E11`):** Structural obsidian. Provides the definitive canvas for dark developer modules, terminal representations, changelog sections, and hero contrast cards.
- **Tertiary (`#63666E`):** Technical slate. Used for metadata markers, terminal labels, metric keys, breadcrumbs, and inactive index numbering.
- **Neutral (`#F4F4F6`):** Precision bone surface. Establishes the off-white editorial background that softens eye strain while maintaining a sterile laboratory atmosphere.
- **Structural Lines (`#E2E2E6` / `#222429` in dark mode):** Hairline 1px borders dividing tabular grid cells, metric callouts, and modular bento grids.

## Typography

The typographic stack balances editorial precision with technical execution telemetry.

- **Primary Engine:** `Inter` handles all primary headlines, interface controls, and body copy. For Arabic locale deployments (`dir="rtl"`), the system seamlessly swaps to `IBM Plex Sans Arabic`, ensuring optical weight harmony, crisp baseline metrics, and neutral technical tone.
- **Metadata & Telemetry:** `JetBrains Mono` governs status tags, metric readouts, version numbers, index numbering (`01 / author`), keyboard shortcuts, and code blocks.
- **Emphasis Rules:** Headings frequently pair high-contrast weights—utilizing muted lighter typography alongside bold focus keywords (e.g., "Catch **bugs** before they ship").
- **RTL Behavior:** Arabic text mirrors layout orientation while code blocks, CLI syntaxes, and technical IDs strictly remain in LTR orientation within isolated directional contexts (`dir="ltr"`).

## Layout & Spacing

The layout is grounded in a rigorous grid structure inspired by architectural schematics and IDE modular panes.

- **Grid Architecture:** 12-column responsive fluid grid on desktop bounded by a maximum container width of `1440px`. Column splits prioritize modular technical sections: 4-column feature steps, 2-column comparison blocks, and full-width continuous telemetry ribbons.
- **Architectural Wireframes:** Sections and cards use visible, continuous hairline dividers (`border-t`, `border-b`, `border-r`) rather than detached card geometry. This creates an interconnected tabular matrix reminiscent of CAD layouts or test dashboards.
- **Responsive Adaptations:**
  - **Desktop (1024px+):** 12 columns, `margin: 3rem`, `gutter: 1.5rem`. Multi-column modular panes and side-by-side terminal demos.
  - **Tablet (768px - 1023px):** 6 columns, `margin: 2rem`, `gutter: 1rem`. Two-column stacks with shared horizontal dividers.
  - **Mobile (<768px):** 4 columns, `margin: 1rem`, `gutter: 0.75rem`. Full-width modular blocks stacked vertically; horizontal borders provide separation.

## Elevation & Depth

Visual hierarchy does not rely on traditional fuzzy dropshadows. Depth is articulated through **pure planar contrast, structural borders, and dark modular embeds**:

- **Hairline Boundary Separation:** Surfaces rely on 1px solid borders (`#E2E2E6` in light mode, `#222429` in dark mode) to delineate containers, interactive cards, and toolbars.
- **Dark Inset Panes:** Terminal outputs, code walkthroughs, CLI previews, and simulation sandboxes sit recessed within deep Obsidian (`#0D0E11`) background planes, framed by micro-borders with no blur.
- **Zero-Blur Hover States:** Interactive elements reject heavy atmospheric elevation. On hover, interactive modular cards and buttons register elevation through border luminescence (transitioning from muted slate to `#72FF13` or crisp white) or high-contrast background inversion.

## Shapes

The geometric vernacular is disciplined, calibrated, and technical.

- **Base Radius (0.25rem / 4px):** Applied to buttons, input fields, test item containers, and inner code execution frames. Reinforces engineered precision and structural sturdiness without sharp brutalist discomfort.
- **Pill Badges & Tags (Fully Rounded / 9999px):** Applied selectively to status pills, index banners (e.g., `$250 IN QA CREDITS WHEN YOU SIGN UP`), environment indicators, and test runner badges (`Web`, `iOS`, `Android`).
- **Interactive Windows:** Browser windows, simulated desktop frames, and code sandboxes maintain subtle 6px corner radiuses with discrete window controls (`traffic light` dots or micro status nodes).

## Components

### Buttons
- **Primary Action:** Solid electric lime (`#72FF13`) fill, absolute black (`#000000`) typography, 4px rounded radius, Inter SemiBold 14px. Hover state: subtle brightness boost or scale `1.01`. Focus ring: 2px offset neon lime.
- **Secondary Action:** Transparent fill with 1px border (`#D1D1D6`), dark typography (`#0D0E11`), 4px rounded radius. Hover state: background shifts to `#EDEDF0`.
- **Ghost / Link:** Plain text accompanied by a terminal arrow (`→` or `↗`), monospaced or sans-serif, with an underline trigger on hover.
- **Dark Container Action:** Inverted white or lime outline against black canvases for terminal-bound operations.

### Badges & Status Chips
- **Announcement Pill:** Centered, subtle border outline, 9999px pill radius, housing monospaced or high-density sans copy with micro icon accents.
- **Telemetry & Metric Pills:** Compact, rounded-full chips showing test suites, target operating systems (`Web`, `iOS`, `Android`), or latency metrics. Inactive states feature subdued gray text; active runs pulse with `#72FF13`.

### Interactive Input Fields & Console Prompts
- **Prompt Bars:** Large single-line text inputs (e.g., prompt runners) wrapped in a minimal 1px border container with rounded-lg edges. Houses left-aligned terminal icon, middle placeholder text, and a right-anchored square neon submit button (`#72FF13`).
- **Form Controls:** Checkboxes and radios are minimal, sharp-cornered (2px radius for checkboxes), rendering deep black checkmarks or solid lime dots upon selection.

### Modular Grid Cards & Bento Panes
- **Tabular Metric Cards:** Grid-locked rectangles separated by mutual 1px border lines. Each card features an index tracker (`01 / name`), bold title, body description, and an integrated technical visual or monospaced counter lockup.
- **Interactive Terminal Windows:** Deep obsidian surface (`#0D0E11`), top chrome bar with dot controls and active tab pills, housing high-contrast syntax highlighting (white text, green success cues, red fail alerts, muted gray comments).

### Enterprise Trust & Logo Ribbons
- **Partner Grids:** Strict 1px bordered tile matrix displaying monochrome, muted enterprise client logos. Clean, distraction-free grid alignment without floating drop shadows.