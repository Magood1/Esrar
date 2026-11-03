---
name: Israr Neurodiversity System
colors:
  surface: '#f5faff'
  surface-dim: '#cfdce6'
  surface-bright: '#f5faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eaf5ff'
  surface-container: '#e3f0fa'
  surface-container-high: '#ddeaf5'
  surface-container-highest: '#d7e4ef'
  on-surface: '#111d25'
  on-surface-variant: '#3f4947'
  inverse-surface: '#26323a'
  inverse-on-surface: '#e6f2fd'
  outline: '#6f7977'
  outline-variant: '#bfc9c6'
  surface-tint: '#286862'
  primary: '#21625c'
  on-primary: '#ffffff'
  primary-container: '#3d7b75'
  on-primary-container: '#d5fff9'
  inverse-primary: '#94d2cb'
  secondary: '#605887'
  on-secondary: '#ffffff'
  secondary-container: '#d2c8fe'
  on-secondary-container: '#595280'
  tertiary: '#7a5000'
  on-tertiary: '#ffffff'
  tertiary-container: '#976814'
  on-tertiary-container: '#fff5ed'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#afeee7'
  primary-fixed-dim: '#94d2cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#04504b'
  secondary-fixed: '#e6deff'
  secondary-fixed-dim: '#c9c0f5'
  on-secondary-fixed: '#1c1440'
  on-secondary-fixed-variant: '#48416e'
  tertiary-fixed: '#ffddb1'
  tertiary-fixed-dim: '#f7bc63'
  on-tertiary-fixed: '#291800'
  on-tertiary-fixed-variant: '#624000'
  background: '#f5faff'
  on-background: '#111d25'
  surface-variant: '#d7e4ef'
typography:
  display-hero:
    fontFamily: Noto Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: '0'
  display-hero-mobile:
    fontFamily: Noto Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: '0'
  headline-lg:
    fontFamily: Noto Sans
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: '0'
  headline-lg-mobile:
    fontFamily: Noto Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: '0'
  headline-md:
    fontFamily: Noto Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: '0'
  headline-sm:
    fontFamily: Noto Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: '0'
  body-lg:
    fontFamily: Noto Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: '0'
  body-md:
    fontFamily: Noto Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: '0'
  body-sm:
    fontFamily: Noto Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: '0'
  label-lg:
    fontFamily: Noto Sans
    fontSize: 15px
    fontWeight: '500'
    lineHeight: 22px
    letterSpacing: '0'
  label-md:
    fontFamily: Noto Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: '0'
  label-sm:
    fontFamily: Noto Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-tablet: 1.5rem
  gutter-desktop: 2rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system is tailored specifically for the Israr Autism Center (مركز إصرار لدعم أطفال التوحد وصعوبات التعلم), serving neurodivergent children, their families, behavioral therapists, and educators. 

The aesthetic philosophy centers on **Sensory Safety, Gentle Authority, and Warmth**:
- **Sensory Safety:** Elimination of visual agitation, flashing cues, saturated primaries, or aggressive micro-animations. Generous breathing space prevents sensory overwhelm.
- **Biophilic Calming Tone:** Soft herbal, sage, lavender, and warm sand hues grounded by muted organic whites.
- **Clarity and Predictability:** Interfaces favor structured visual anchors, steady hierarchy, and predictable spatial relationships to reduce cognitive fatigue.
- **Bilingual Fluidity:** Seamless right-to-left (RTL) baseline support for Arabic as the primary language alongside balanced English localization.

## Colors

The palette directly addresses sensory sensitivities by substituting clinical starkness and harsh high-vibrancy tones with nature-inspired, de-saturated pigments:

- **Primary (`#3D7B75` - Calming Sage / Deep Teal):** Used for primary touchpoints, active states, key navigation landmarks, and affirmation cues. It conveys safety and steady therapeutic guidance.
- **Secondary (`#7F77A8` - Soft Muted Lavender):** Applied to complementary pathways, developmental milestones, therapy scheduling tags, and reflective states.
- **Tertiary (`#E2A952` - Warm Sand / Soft Ochre):** A non-jarring accent for positive encouragement, developmental progress markers, and warm badges. Never used as an alarming warning sign.
- **Neutral Dark (`#243038` - Deep Slate):** Replaces pure `#000000` to deliver high accessibility contrast (WCAG AAA compliant against white surfaces) without harsh contrast glare.
- **Neutral Background Canvas (`#F4F7F6` - Mint Off-White):** A tranquil base surface that minimizes eye strain and sensory fatigue.
- **Card Surfaces (`#FFFFFF` - Pure White):** Reserved for foreground containers, content groupings, and form modules.
- **Borders & Separators (`#E5EAE8` - Pale Celadon Grey):** Low-contrast structural delimiters that outline sections without creating visual noise.

## Typography

The typographic hierarchy is built on **Noto Sans** (pairing Noto Sans Arabic alongside Latin counterparts) to prioritize legibility, natural open apertures, and steady horizontal rhythms essential for readers with learning difficulties, ADHD, and dyslexia.

- **Line Height & Rhythms:** Elevated line-height values (1.6x to 1.75x across body levels) guarantee clear word boundary distinction in complex Arabic scripts (Nastaliq/Naskh-derived modern glyphs) without line collisions.
- **Weights:** Typography uses Medium (`500`) and Semi-Bold (`600`) in place of heavy black weights to eliminate ocular heaviness.
- **RTL Baseline Behavior:** Numbers, dates, and measurement values default to localized directional numbers with consistent baseline alignment alongside Arabic letterforms.

## Layout & Spacing

The layout embraces calm predictability using a 12-column adaptive fluid grid with generous outer borders and consistent gutter spacing:

- **Desktop (1024px+):** 12-column grid, max-width of 1280px to prevent uncomfortably long line lengths, 3.5rem outer canvas margins, and 2rem gutters.
- **Tablet (768px - 1023px):** 8-column grid, 2rem margins, and 1.5rem gutters.
- **Mobile (320px - 767px):** 4-column fluid grid, 1rem margins, and 1.25rem gutters.
- **Vertical Spacing:** Modules adhere strictly to standard step-ups (`space-md` for grouped items, `space-lg` for card internal padding, and `space-xl` between modular sections). Cramped density is strictly prohibited to maintain open breathing zones for cognitive ease.

## Elevation & Depth

To prevent visual anxiety, this system rejects high-contrast cast shadows, skeuomorphic bevels, and artificial floating planes. Depth is established through **Tonal Stratification and Whispered Boundaries**:

- **Ground Level:** Mint off-white `#F4F7F6` canvas provides a grounded, non-reflective base.
- **Surface Elevation (Cards & Panels):** Pure white `#FFFFFF` crisp container layers framed by a subtle 1px border (`#E5EAE8`).
- **Ambient Presence (No Harsh Drops):** For floating modaled surfaces or selected elevated cards, use an ultra-diffused tint shadow:
  - `box-shadow: 0 8px 30px -4px rgba(61, 123, 117, 0.06), 0 2px 6px -1px rgba(36, 48, 56, 0.03);`
  - The drop uses a sage tint (`rgba(61, 123, 117, ...)`) rather than charcoal or black, eliminating harsh edges.
- **Layering Over Modals:** Semi-opaque tinted backdrop overlays (`rgba(36, 48, 56, 0.25)`) with an 8px soft blur filter to dim distractions gently without severe darkness.

## Shapes

The shape system expresses physical softness, tactile gentleness, and approachable friendliness:

- **Cards & Primary Modules:** Fixed `20px` border radius (`rounded-xl` in implementation scale) to remove sharp corners that register unconsciously as abrasive.
- **Buttons & Interactive Controls:** `12px` to `16px` curvature (`rounded-lg`), facilitating easy touch and tap targets for fine-motor accommodations.
- **Badges, Tags, and Visual Progress Indicators:** Pill-form (`9999px`) roundedness to represent continuous progress and non-punitive feedback.

## Components

### Buttons
- **Primary:** Background `#3D7B75`, text `#FFFFFF`, border-radius 14px, minimum touch target height of 48px. State changes rely on subtle lightness transitions (`#346863`), never sudden high-contrast flashes or aggressive scale jumps.
- **Secondary:** Background `#F4F7F6`, text `#3D7B75`, subtle outline 1px solid `#3D7B75` with 14px radius.
- **Tertiary / Soft Action:** Background `rgba(127, 119, 168, 0.12)`, text `#7F77A8`, zero border, 14px radius.

### Cards
- Constructed with `#FFFFFF` backgrounds, `20px` border radius, and a gentle `1px solid #E5EAE8` outline.
- Internal padding defaults to `space-lg` (24px).
- Interactive cards elevate only through subtle border darkening (`#3D7B75` at 40% opacity) and the diffuse sage ambient shadow.

### Form Inputs & Text Fields
- Surface `#FFFFFF`, border `1.5px solid #E5EAE8`, height 48px, border radius 12px, text `#243038`.
- Focus states introduce an ergonomic 3px gentle aura: `box-shadow: 0 0 0 3px rgba(61, 123, 117, 0.20)` with border `#3D7B75`. Red error states are softened to warm terracotta tones rather than aggressive neon red, paired with supportive explanatory text.

### Chips & Badges
- **Status & Category Chips:** Pill-shaped, padding 6px 14px, typography `label-md`. 
  - Behavioral Milestone: Background `rgba(226, 169, 82, 0.15)`, text `#99691F`.
  - Therapy Session: Background `rgba(127, 119, 168, 0.15)`, text `#5C5485`.
  - Active Support: Background `rgba(61, 123, 117, 0.15)`, text `#2B5854`.

### Lists & Activity Schedules
- Visual day schedules and sensory routines employ segmented card rows separated by `space-sm` (8px). 
- Every list item incorporates paired iconographic communication alongside text labels to assist children and non-verbal communicators.

### Checkboxes & Radio Controls
- Minimum hit-box area of 44x44px. Visible mark is 22x22px with 6px rounded corners (checkboxes) and concentric circles (radios).
- Active fill: `#3D7B75` containing clean `#FFFFFF` icon checkmarks.