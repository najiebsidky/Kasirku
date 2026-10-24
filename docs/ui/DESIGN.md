---
name: Warung POS & Retail System
colors:
  surface: "#fff8f2"
  surface-dim: "#e3d9c8"
  surface-bright: "#fff8f2"
  surface-container-lowest: "#ffffff"
  surface-container-low: "#fdf2e1"
  surface-container: "#f7eddb"
  surface-container-high: "#f2e7d6"
  surface-container-highest: "#ece1d0"
  on-surface: "#201b11"
  on-surface-variant: "#4f4632"
  inverse-surface: "#353024"
  inverse-on-surface: "#faefde"
  outline: "#817660"
  outline-variant: "#d3c5ac"
  surface-tint: "#775a00"
  primary: "#775a00"
  on-primary: "#ffffff"
  primary-container: "#ffc61a"
  on-primary-container: "#6e5400"
  inverse-primary: "#f6be0a"
  secondary: "#5f5e5e"
  on-secondary: "#ffffff"
  secondary-container: "#e2dfde"
  on-secondary-container: "#636262"
  tertiary: "#555f71"
  on-tertiary: "#ffffff"
  tertiary-container: "#c4cee4"
  on-tertiary-container: "#4e586a"
  error: "#ba1a1a"
  on-error: "#ffffff"
  error-container: "#ffdad6"
  on-error-container: "#93000a"
  primary-fixed: "#ffdf98"
  primary-fixed-dim: "#f6be0a"
  on-primary-fixed: "#251a00"
  on-primary-fixed-variant: "#5a4300"
  secondary-fixed: "#e5e2e1"
  secondary-fixed-dim: "#c8c6c5"
  on-secondary-fixed: "#1c1b1b"
  on-secondary-fixed-variant: "#474746"
  tertiary-fixed: "#d9e3f9"
  tertiary-fixed-dim: "#bdc7dc"
  on-tertiary-fixed: "#121c2c"
  on-tertiary-fixed-variant: "#3d4759"
  background: "#fff8f2"
  on-background: "#201b11"
  surface-variant: "#ece1d0"
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: "700"
    lineHeight: 40px
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: "700"
    lineHeight: 32px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: "600"
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: "600"
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: "600"
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: "400"
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: "400"
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: "400"
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: "600"
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: "600"
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: "500"
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system is engineered for micro, small, and medium retail enterprises (warung kelontong & toko retail). The brand personality balances functional practicality, approachable warmth, and sharp speed. It conveys reliability, transparency, and effortless control, allowing shop owners and cashiers to process high-speed daily sales and manage inventories without technical friction.

The visual direction follows **Modern Functional Minimalism** with high-contrast utility accents. It prioritizes ultra-clear tabular structures, legible numeric summaries, glanceable inventory alerts, and rapid touch/click feedback. The golden-yellow core injects optimism and entrepreneurial energy, anchored firmly by rich slate neutrals and crisp borders to prevent eye fatigue during lengthy checkout shifts.

## Colors

The color foundation utilizes a high-contrast warm-amber and deep slate palette tailored for fast recognition in varied lighting environments (from dim kiosks to sunlit shopfronts).

- **Primary (`#FFC61A`)**: Vibrant canary gold used strategically on primary CTAs (e.g., "Bayar", "+ Tambah", "Simpan"), focused indicators, and key operational alerts. Text rendered atop the primary tone must strictly use deep charcoal `#1A1A1A` for WCAG AA compliance.
- **Secondary (`#1A1A1A`)**: Deep onyx used for high-impact structural panels, dark header bars, primary typographic elements, and selected states.
- **Tertiary (`#2D3748`)**: Balanced slate graphite, driving secondary interactive surfaces, table header backgrounds, icons, and supporting structural strokes.
- **Surface & Backgrounds**: Base background sits at crisp off-white (`#F8F9FA`), elevated table/card containers use pure white (`#FFFFFF`), with subtle hairline boundaries (`#E2E8F0`).
- **Semantic Feedback**:
  - Success/Paid: `#16A34A` (Emerald)
  - Low Stock/Warning: `#EA580C` (Warm Amber-Orange)
  - Critical/Error: `#DC2626` (Ruby Crimson)

## Typography

Typography is paired to provide maximum personality in structure and unyielding legibility in numerical data:

- **Headlines & Action Labels (Plus Jakarta Sans)**: Delivers a clean, friendly geometric presence akin to Poppins, offering crisp curves, balanced geometry, and friendly authority for main screen headings, drawer headers, and primary button labels.
- **Body & Tabular Data (Inter)**: Built for micro-legibility and tabular figures (`font-variant-numeric: tabular-nums`). Essential for SKU codes, price calculations (`Rp`), quantity step controls, and line-item totals so digits align predictably across transaction screens.

## Layout & Spacing

The layout adheres to a flexible 12-column grid system tuned for POS desk displays, tablet stands, and widescreen browser windows:

- **Desktop (1024px and above)**: Split-screen POS architecture. Left workspace (search bar, product catalog, quick-select grid/table) spans 8 columns; persistent right checkout panel (active cart, quantity dials, payment keypad, total CTA) takes 4 columns.
- **Tablet / Mobile (< 1024px)**: Single column with collapsable bottom sheet tray for cart and payment triggers.
- **Spacing Rhythm**: Strictly built on an 8px base unit (0.5rem increments). Component padding emphasizes comfortable touch targets (minimum 44px height for interactive cash-register operations) while preventing unnecessary vertical sprawl.

## Elevation & Depth

Elevation in this system uses clean surface layering and low-contrast borders rather than heavy theatrical drop shadows:

- **Canvas (Level 0)**: `#F8F9FA` foundation.
- **Surface Panels (Level 1)**: Crisp white (`#FFFFFF`) cards and table containers framed with a delicate boundary border: `1px solid #E2E8F0`.
- **Raised Interactive Cards (Level 2)**: Active cart summaries, floating product cards, and modal dialogs receive a soft ambient tint: `0 4px 12px -2px rgba(26, 26, 26, 0.06), 0 2px 6px -1px rgba(26, 26, 26, 0.04)`.
- **Checkout Total / Flyout Drawer (Level 3)**: Deep anchored popups and slide-over payment sheets leverage `0 12px 32px -4px rgba(26, 26, 26, 0.14)`.

## Shapes

The design adopts a cohesive `roundedness: 2` (0.5rem / 8px border radius base):

- **Buttons & Form Fields**: `rounded-md` (8px) for comfortable clicking, consistent finger targets, and modern aesthetics.
- **Cards, Drawers & Tables**: `rounded-lg` (12px to 16px) for card containers and modal viewports, providing a soft framing that separates functional modules.
- **Tags & Status Badges**: `rounded-full` (pill shape) for quick recognition of stock alerts, categories, and payment method chips.

## Components

### Buttons

- **Primary ("+ Tambah", "Bayar", "Simpan")**: Solid `#FFC61A` fill, `#1A1A1A` text with bold font weight (`Plus Jakarta Sans, 600`), 8px border radius, minimum height of 44px. Hover state warms to `#F5B800`; active state scales subtly (`scale(0.98)`).
- **Secondary**: Outlined `1px solid #CBD5E1` with `#2D3748` text and white background. Hover fills to `#F1F5F9`.
- **Destructive**: Soft red background (`#FEE2E2`) with `#DC2626` text for deleting line items or voiding bills.

### Product Data Tables

- Header row with subtle grey backing (`#F1F5F9`), uppercase micro-labels (`label-md`), and uppercase tracking.
- Row heights set to 52px for touch-friendliness, equipped with hairline borders (`#E2E8F0`) and alternating hover state (`#F8FAFC`).
- Price and stock numbers aligned right with tabular figures enabled.

### Input Fields & Search Bars

- Background `#FFFFFF` with `1px solid #CBD5E1` borders and 8px corners.
- Search input accompanied by an integrated left-aligned magnifying glass icon and instant clear button.
- Focus state activates a distinct 2px ring: `outline: 2px solid #FFC61A; border-color: #1A1A1A;`.

### Numeric Steppers & Cart Items

- Steppers feature compact `-` and `+` square buttons with strong `#2D3748` boundaries flanking an editable quantity display.
- Active items in the POS cart clearly highlight product name, individual price, quantity multiplier, and calculated line sum.

### Status Chips

- **Aman / Tersedia (In Stock)**: Background `#DCFCE7`, text `#15803D`.
- **Menipis (Low Stock)**: Background `#FEF3C7`, text `#B45309`.
- **Habis (Out of Stock)**: Background `#FEE2E2`, text `#B91C1C`.
