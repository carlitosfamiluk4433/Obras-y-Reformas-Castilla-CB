---
name: Tierra y Estructura
colors:
  surface: '#fff8f5'
  surface-dim: '#e2d8d2'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf2eb'
  surface-container: '#f6ece6'
  surface-container-high: '#f0e6e0'
  surface-container-highest: '#eae1da'
  on-surface: '#1f1b17'
  on-surface-variant: '#59413a'
  inverse-surface: '#342f2b'
  inverse-on-surface: '#f9efe8'
  outline: '#8d7168'
  outline-variant: '#e1bfb5'
  surface-tint: '#ac3400'
  primary: '#9b2f00'
  on-primary: '#ffffff'
  primary-container: '#c2410c'
  on-primary-container: '#ffece7'
  inverse-primary: '#ffb59d'
  secondary: '#545f73'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f8'
  on-secondary-container: '#586377'
  tertiary: '#824500'
  on-tertiary: '#ffffff'
  tertiary-container: '#a65900'
  on-tertiary-container: '#ffede1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59d'
  on-primary-fixed: '#390c00'
  on-primary-fixed-variant: '#832600'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#fff8f5'
  on-background: '#1f1b17'
  surface-variant: '#eae1da'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-badge:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an architectural, grounded, and unmistakably premium identity for a high-craft construction and remodeling firm. Rooted in the geographic identity of La Sagra and Madrid Sur, the visual language balances regional authenticity (warm earth, clay, mortar, structural stone) with modern architectural precision.

### Design Principles
- **Architectural Solidity:** Layouts and elements should evoke structural integrity. Forms are decisive, stable, and substantial without feeling heavy or industrial.
- **Warm Prestige:** Move deliberately away from cold industrial blues or generic contractor aesthetics. Warm stone, sand, and terracotta convey craftsmanship, high-end materials, and residential warmth.
- **Uncompromising Transparency:** Clear project metrics, license disclosures, guarantee seals, and upfront process breakdowns establish deep institutional trust for homeowners and commercial clients.
- **Purity of Space:** Extensive, deliberate whitespace frames high-resolution architectural photography, letting physical craftsmanship be the hero.

## Colors

The palette draws inspiration directly from regional building materials: fired terracotta tiles (*teja rústica*), deep slate masonry, and sun-baked limestone soils.

### Palette Distribution & Roles
- **Primary (`#C2410C` — Terracotta Cotto):** Reserved strictly for high-priority calls to action (budget requests, quote submission, phone contacts), focal interactive states, and authoritative milestones.
- **Secondary (`#1E293B` — Slate Masonry):** The foundational anchor. Used for high-impact structural typography, header navigation bars, premium dark card treatments, and footer structural blocks.
- **Tertiary (`#D97706` — Ocre Cálido):** Accent tone for warranty highlights, five-star ratings, guarantee stamps, and completion badges.
- **Neutral (`#78716C` — Warm Stone):** Calibrated intermediate tone for secondary labels, breadcrumbs, non-active borders, and metadata.
- **Surface Foundations:**
  - `surface-canvas`: `#FAF9F6` (Alabaster stone background, avoiding sterile pure white).
  - `surface-card`: `#FFFFFF` (Pure white for raised cards to pop cleanly against stone canvas).
  - `surface-subtle`: `#F5F3EF` (Tamped earth tint for alternating section bands and container wells).
  - `text-primary`: `#0F172A` (Deepest charcoal for crisp contrast and WCAG AAA compliance).
  - `text-secondary`: `#475569` (Muted slate for narrative paragraphs and specifications).

## Typography

The type system relies on **Plus Jakarta Sans** throughout, utilizing its geometric structure and subtly rounded vertices to balance structural rigor with warm residential approachability.

### Usage Hierarchy & Rules
- **Headlines & Titles:** Set with negative letter tracking (`-0.01em` to `-0.03em`) and confident font weights (`700` to `800`) to evoke architectural stability.
- **Numbers & Metrics:** High-value data points (years of warranty, completed square meters, budget totals) use `display-hero` with tabular figure alignments (`tnum`).
- **Technical Specifications & Tags:** Micro-copy, category tags, and guarantee labels leverage `label-badge` with uppercase styling and expanded tracking (`0.06em`).

## Layout & Spacing

The layout is built upon an 8pt modular rhythm using a 12-column responsive grid for desktop and a 4-column grid on mobile devices.

### Breakpoints & Layout Adaptations
- **Mobile (< 768px):** 4 columns, `margin-mobile` (20px), `gutter-mobile` (16px). Service comparison cards and before/after modules collapse into full-width stacked views or edge-to-edge horizontally scrolling carousels.
- **Tablet (768px – 1024px):** 8 columns, 24px gutters, 32px margins. Two-column symmetrical service matrices.
- **Desktop (> 1024px, max-width 1320px centered):** 12 columns, `margin` (48px), `gutter` (24px). Asymmetrical editorial layouts pairing bold typography, project specs, and large-format gallery compositions.

### Layout Cadence
Section verticals follow a spacious cadence (80px–120px separation) to give each renovation phase, case study, and client testimonial sovereign visual weight.

## Elevation & Depth

Visual hierarchy rejects excessive, synthetic floating effects in favor of tactile surfaces and grounded structural layers.

### Elevation Levels
- **Level 0 (Flat / Canvas):** Applied to the main stone-tinted backdrop (`#FAF9F6`) and background utility bands.
- **Level 1 (Card & Content Blocks):** Pure white background (`#FFFFFF`) with a warm, subtle hairline border (`1px solid #E7E5E4`) and an ambient, stone-tinted soft drop shadow: `0 4px 20px -2px rgba(30, 41, 59, 0.05)`.
- **Level 2 (Hovered Cards & Interactive Modules):** Elevated upon interaction: `0 12px 32px -4px rgba(30, 41, 59, 0.09)`, accompanied by a slight `-2px` Y-axis lift to communicate readiness.
- **Level 3 (Modals, Lead Calculators & Fixed CTAs):** High-priority focus layers utilizing dual shadows: `0 24px 48px -12px rgba(15, 23, 42, 0.18)` layered over a warm backdrop scrim (`rgba(15, 23, 42, 0.6)` with `4px` blur).

## Shapes

The design system employs **Level 2 (Rounded)** curvature. Elements possess substantial, refined curves that soften the architectural solidity of masonry and timber without turning whimsical or playful.

### Corner Radius Mapping
- **Default Elements (`0.5rem` / 8px):** Input fields, form selects, badge containers, secondary buttons, tooltips.
- **Large Surfaces (`1rem` / 16px):** Project cards, testimonial panels, quote calculation widgets, modal dialogues.
- **Extra-Large Focal Elements (`1.5rem` / 24px):** Hero visual containers, interactive before/after renovation comparison blocks, service package highlights.
- **Full Pill (`9999px`):** Status pills, verification seals, and floating mobile quick-contact dials.

## Components

### Buttons
- **Primary CTA ("Solicitar Presupuesto"):** Solid Terracotta (`#C2410C`), crisp white text, `rounded-md` (8px), height 48px (52px on mobile for thumb accuracy). Subtle inner top highlight border (`rgba(255,255,255,0.15)`) for tactile presence. Hover: `#9A3412`.
- **Secondary Action ("Ver Obras Realizadas"):** Deep Slate (`#1E293B`) solid surface with white text, or clean white container with `1.5px` border in `#1E293B`.
- **Tertiary / Direct Contact (WhatsApp / Phone):** Clean sand container (`#F5F3EF`) with slate text, pairing an icon and direct response time indicator.

### Trust Badges & Guarantee Seals
- **Regional & Legal Certification:** Anchored capsules featuring an official shield/check icon, displaying "Inscrito en REA", "Seguro RC 100% Cobertura", or "Garantía 5 Años por Escrito".
- **Styling:** Soft warm-amber or stone background (`#FEF3C7` or `#F5F3EF`), deep amber or slate border (`1px`), text in `label-badge` with bold typographic lockup.

### Renovation Showcase Cards
- **Image Module:** Upper area utilizes a 16:10 or 4:3 aspect ratio architectural photo with `rounded-t-lg`. Hover activates a smooth crossfade to floor plan or secondary finishing detail.
- **Data Strip:** Beneath the project title, include a 3-column pill metric row: *Ubicación* (e.g., Illescas, Getafe, Toledo), *Plazo de Ejecución* (e.g., 6 semanas), and *Tipo de Obra* (Integral / Cocina y Baño).
- **Surface:** Pure white background, `1px` border `#E7E5E4`, subtle hover lift to Elevation Level 2.

### Form Inputs & Cost Calculator Controls
- **Text Inputs:** Height 48px, background `#FFFFFF`, border `1.5px solid #D6D3D1`, text `#0F172A`, placeholder `#A8A29E`. On focus: border transitions to `#C2410C` with a `0 0 0 3px rgba(194, 65, 12, 0.12)` halo ring.
- **Square Meter & Room Sliders:** Custom track in warm stone (`#E7E5E4`), active fill in terracotta (`#C2410C`), with an oversized draggable circular thumb (24px) for intuitive touch usage.

### Before/After Interactive Comparison
- **Split-Screen Slider:** A dual-layer container with a 50% split default, bordered in `#E7E5E4`, controlled by a tactile vertical hairline handle with dual left/right chevrons in `#1E293B`. Top-left and top-right pinned labels ("Estado Previo" / "Resultado Final") styled with `label-badge`.

### Checkboxes & Radios
- **Selection Units:** Custom custom-built 20px squares/circles. When checked, fill with `#C2410C` featuring a crisp white geometric checkmark. Group selections are housed inside selectable card containers that highlight with a terracotta hairline border upon selection.