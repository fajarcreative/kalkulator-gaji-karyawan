---
name: GajiPro Modern Payroll
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#444651'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#006c4a'
  on-secondary: '#ffffff'
  secondary-container: '#82f5c1'
  on-secondary-container: '#00714e'
  tertiary: '#00246b'
  on-tertiary: '#ffffff'
  tertiary-container: '#00389a'
  on-tertiary-container: '#8da9ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#85f8c4'
  secondary-fixed-dim: '#68dba9'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005137'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
  currency-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  currency-body:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system embodies a modern, corporate-grade financial aesthetic tailored specifically for Indonesian enterprise and SME workforce workflows. The target audience encompasses HR administrators, finance managers, and Indonesian employees seeking absolute transparency and compliance in compensation calculations (such as BPJS Ketenagakerjaan, BPJS Kesehatan, PPh 21, and standard overtime structures under PP No. 35/2021).

The visual language follows **Corporate / Modern** principles with subtle tactile crispness:
- **Trustworthy & Authoritative:** High precision, deliberate spacing, and authoritative deep slate-blues evoke regulatory compliance and banking-grade security.
- **Clarity over Flourish:** Unambiguous data structures, tabular alignment for currency values (IDR), and high-contrast typographic balance to eliminate calculation ambiguities.
- **Accessible & Efficient:** Touch targets optimized for rapid single-handed mobile entry, featuring tactile feedback cues, instant numeric recalculations, and clean compartmentalized cards.

## Colors

The palette balances fiscal authority with vibrant operational clarity:

- **Primary (`#1E3A8A`) & Tertiary (`#2563EB`):** Deep navy grounds headers, master actions, primary calculation buttons, and key navigation components. Vivid blue (`#2563EB`) handles interactive links, active control toggles, and focused field states.
- **Secondary (`#059669` / Accent `#10B981`):** Emerald green indicates positive monetary growth, take-home pay (*Total Penghasilan Bersih*), overtime pay incentives (*Gaji Lembur*), and compliant status tags.
- **Neutrals & Canvas:** The canvas sits on ultra-clean slate tinted layers (`#F8FAFC`), surfaces shift to pure white (`#FFFFFF`) for elevation contrast, and body copy is rendered in dark slate (`#0F172A` and `#334155`) with supporting elements in medium slate (`#64748B`). Subtle borders use cool slate borders (`#E2E8F0`).
- **Semantic Accents:** Red-orange (`#DC2626`) is reserved strictly for statutory deductions (*Potongan PPh 21, BPJS*), late penalties, and destructive validation states.

## Typography

The dual-type setup combines the approachable geometric character of **Plus Jakarta Sans** for headlines and primary KPI financial counters with the hyper-legible, tabular-friendly **Inter** for data grids, body copy, and UI labels.

Key rules:
- **Currency & Numerics:** Currency amounts (e.g., `Rp 12.500.000`) always use tabular numerals (`tnum`) in Inter or Plus Jakarta Sans to ensure exact vertical decimal and separator alignment across comparison tables.
- **Hierarchy Distinction:** Headings establish swift context (e.g., *Rincian Gaji Bulanan*), while label tokens are slightly letter-spaced to guide dense form entries without fatigue.

## Layout & Spacing

The layout is built for fluid mobile-first ergonomics, anchored to a disciplined 4px / 8px grid cadence.

- **Mobile Viewport Structure:** Uses a fluid 4-column layout on standard smartphone displays (360px–430px width) with outer margins of `1rem` (16px) and inter-component gutters of `0.75rem` (12px) to maximize horizontal real estate.
- **Safe Zones & Action Anchors:** Calculator actions and total summary ribbons are pinned as a floating bottom navigation bar or bottom sheet container with `env(safe-area-inset-bottom)` offsets.
- **Reflow & Breakpoints:** 
  - Mobile (`< 640px`): Single-column stacked workflow. Form inputs on top, sticky/bottom computation drawer for quick insights.
  - Tablet (`640px - 1024px`): 8-column layout. 2-column split containing parameter entry on the left and sticky live summary sheet on the right.

## Elevation & Depth

Visual hierarchy uses **tonal layering combined with soft, low-contrast ambient shadows** to prevent optical noise on numeric-heavy layouts:

- **Level 0 (Base Canvas):** `#F8FAFC` flat surface.
- **Level 1 (Cards & Modules):** Pure `#FFFFFF` surfaces with a 1px border of `#E2E8F0` and an ambient shadow: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`.
- **Level 2 (Summary Cards & Prominent Panels):** Highlights such as the *Total Penghasilan* summary card use an extended soft shadow tinted with slate: `box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Floating Stepper Controls & Sticky Bars):** Elevated interactive elements float above canvas content with: `box-shadow: 0 10px 15px -3px rgba(30, 58, 138, 0.08), 0 4px 6px -4px rgba(30, 58, 138, 0.04)`.

## Shapes

The roundedness level is **Rounded (Level 2)**:
- Standard buttons, input enclosures, and operational chips utilize `0.5rem` (8px) corner radii.
- Content calculation cards, modal sheets, and nested financial summary panels feature `1rem` (16px) radii (`rounded-lg`).
- Stepper buttons and segmented control pills within Golongan chips feature continuous, soft curvature that guarantees pleasant tactile touch zones.

## Components

### 1. Golongan Selector Chips (A, B, C)
- **Container:** Horizontal segment group or flex-wrap chips with `0.5rem` internal radius.
- **Default State:** Background `#F1F5F9`, border 1px solid `#CBD5E1`, text `#475569`, font `label-lg`.
- **Selected State:** Background `#1E3A8A`, border 1px solid `#1E3A8A`, text `#FFFFFF`, with a subtle checkmark icon and slight elevation (Level 1).
- **Sub-label Display:** Displays title and base wage tier (e.g., "Gol. A • Staff").

### 2. Overtime Numeric Stepper & Slider
- **Stepper Control:** A pill-shaped segmented unit with tactile `+` and `-` touch buttons (`44px` height). Center input displays numerical hours (e.g., `4.5 Jam`) with bold tabular typography.
- **Continuous Slider:** Track height of `6px` in `#E2E8F0` with an active fill of `#2563EB`. Slider thumb is a white circular token (`24px`) with a 2px `#2563EB` border and active drop-shadow.

### 3. Summary Breakdown Card (Gaji Pokok, Lembur, Potongan, Total)
- **Enclosure:** Background `#FFFFFF`, 1px border `#E2E8F0`, rounded `1rem`.
- **Line Item Rows:** Flexible row layout containing item title on the left in `#64748B` and currency on the right in `#0F172A` with dotted or soft border divider between entries.
- **Highlight Section (*Total Penghasilan Bersih*):** High-contrast summary band at the card base, filled with soft emerald tint (`#ECFDF5`), bordered by `#A7F3D0`, with prominent value displayed in `#047857` using `currency-display` typography.

### 4. Input Fields
- **Container:** Standard `48px` minimum height for touch accessibility. White background with `#CBD5E1` border.
- **Prefix Handling:** Indonesian Rupiah prefix `"Rp"` statically affixed inside the field with a vertical separator and `#64748B` label text.
- **Focused State:** 2px ring in `#2563EB` with an ambient glow and immediate auto-formatting for thousand separators (e.g., `10.000.000`).

### 5. Buttons
- **Primary:** Full-width `#1E3A8A` solid fill, white text, height `48px`, font `label-lg`. Active hover/press state scales down slightly (`0.98`) to provide crisp mechanical feedback.
- **Secondary / Ghost:** Transparent background with `#2563EB` label or subtle `#E2E8F0` border for exporting slips (PDF/Excel) or resetting parameters.