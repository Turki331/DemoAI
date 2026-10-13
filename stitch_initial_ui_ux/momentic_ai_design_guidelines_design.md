# Design System: Momentic AI Technical Interface

## 1. Overview & Brand Identity
Momentic AI is an agentic quality assurance platform tailored for high-velocity software engineering teams. The visual direction balances **developer-grade utility** with **editorial precision**: high-contrast monochromatic base surfaces accented by a vibrant, electric neon green for high-intent actions, complemented by subtle structural borders, micro-badges, and live telemetry data.

---

## 2. Color System & Tokens

### Primary & Accent Colors
- **Accent / CTA Lime:** `#72FF13` (Signature high-contrast fluorescent green used for primary action buttons, active status indicators, and key highlights)
- **Accent Hover / Pressed:** `#5ED90B` / `#4DB806`
- **Accent Text On Lime:** `#0A0D08` (Deep near-black for maximum WCAG AAA contrast against neon lime)

### Surface & Neutral Hierarchy
- **Base Canvas (Light):** `#FFFFFF` / `#F9F9FB`
- **Surface Low (Subtle Sections):** `#F3F3F5`
- **Surface Elevated / Cards:** `#FFFFFF`
- **Dark Inversion (High-Contrast Sections / Footer):** `#0C0E12` / `#13161C`
- **Border Default:** `#E5E7EB` (Subtle 1px divider lines delineating cards and table rows)
- **Border Subtle:** `#EEF0F2`
- **Border Active / Dark:** `#1F242F` (Used within dark sections)

### Text & Content Colors
- **Text Primary (Light Mode):** `#0D0F12`
- **Text Secondary / Muted:** `#6B7280`
- **Text Tertiary / Metadata:** `#9CA3AF`
- **Text On Dark (Primary):** `#F9FAFB`
- **Text On Dark (Muted):** `#9CA3AF`
- **Status Green / Success:** `#10B981` (and `#72FF13` for system active states)
- **Status Red / Error Triage:** `#EF4444`

---

## 3. Typography & Font Hierarchy

### Typefaces
- **Primary Body & Headings (LTR / English):** `Inter`, `-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, sans-serif
- **Primary Body & Headings (RTL / Arabic):** `IBM Plex Sans Arabic`, `Cairo`, sans-serif
- **Technical & Metric Counters:** `JetBrains Mono`, `Fira Code`, `ui-monospace`, monospace

### Scale & Hierarchy
- **Display Hero:** `48px` - `64px` (Desktop) / `32px` - `40px` (Mobile) | Font-weight: `700` | Line-height: `1.1`
- **H1 Section Titles:** `32px` - `38px` | Font-weight: `700` | Line-height: `1.2`
- **H2 Card / Feature Titles:** `20px` - `24px` | Font-weight: `600` | Line-height: `1.3`
- **H3 Subheadings:** `16px` - `18px` | Font-weight: `600` | Line-height: `1.4`
- **Body Large (Hero Subtitle):** `16px` - `18px` | Font-weight: `400` | Line-height: `1.6`
- **Body Regular:** `14px` - `15px` | Font-weight: `400` | Line-height: `1.5`
- **Caption & Metadata:** `12px` - `13px` | Font-weight: `500` | Monospace or uppercase tracking
- **Micro / Pills:** `11px` | Font-weight: `600` | Letter-spacing: `+0.04em`

---

## 4. Spacing, Radii & Grid System

### Spacing Scale
- `2xs`: `4px`
- `xs`: `8px`
- `sm`: `12px`
- `md`: `16px`
- `lg`: `24px`
- `xl`: `32px`
- `2xl`: `48px`
- `3xl`: `64px`
- `4xl`: `96px`

### Border Radii
- **Tags & Pills:** `9999px` (Full rounded capsule)
- **Buttons:** `8px` - `10px` (Soft rounded rectangular) or pill `9999px` for quick toggle/badges
- **Cards & Banners:** `12px` - `16px`
- **Modal / Inputs:** `8px` - `10px`

### Elevation & Borders
- Flat, engineered look. Minimal heavy drop shadows.
- Separation is predominantly achieved via **1px crisp borders** (`#E5E7EB` or `#1F242F`) rather than diffuse box-shadows.

---

## 5. Key UI Component Specifications

### 1. Primary Action Button (The "Momentic CTA")
- **Background:** `#72FF13`
- **Color:** `#0A0D08`
- **Font:** 14px - 15px, Semi-bold (600)
- **Padding:** `12px 24px` (Desktop) / `14px 20px` (Mobile)
- **Radius:** `10px`
- **Icon:** Directional arrow (`→` in LTR, `←` in RTL)
- **Hover:** Darker neon `#5ED90B` with subtle scale transform (`scale(1.01)`)

### 2. Secondary / Ghost Button
- **Background:** `#FFFFFF` or `#F3F3F5`
- **Border:** 1px solid `#E5E7EB`
- **Color:** `#111827`
- **Padding:** `12px 20px`

### 3. Status Badges & Feature Trackers
- **Format:** Micro-capsule with monospace indexing (e.g., `#01`, `#02`, `v2.4.0`)
- **Background:** Semi-transparent or `#F3F3F5`
- **Border:** 1px solid `#E5E7EB`
- **Typography:** 11px - 12px Mono, `#4B5563`

### 4. Live Telemetry / Metrics Cards
- Grid presentation with top hairline border or card border.
- **Top Value:** Large bold tabular figures (`24px` - `32px`, `font-mono`, weight `700`).
- **Bottom Label:** Small subdued descriptor (`12px` - `13px`, `#6B7280`).

### 5. Client Testimonial Callouts
- Editorial serif or high-contrast sans quote treatment.
- Large quotation styling with inline highlighted key phrases (e.g. bolded or subtle neon green underline).
- Clean author attribution with company badge/wordmark.

---

## 6. Internationalization & RTL Specifications
- **Direction:** `dir="rtl"` with appropriate bidirectional CSS properties (`padding-inline`, `margin-inline`, `inset-inline-start`).
- **Icons & Affordances:** Directional chevrons and flow arrows are flipped for RTL flows. Status dots remain positioned adjacent to the leading edge of text.
- **Language Switcher:** Sticky or header-anchored toggle (`EN` / `العربية`) using a segmented pill container with active state background.
