---
name: Metro Drive Academy
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#434655'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#1d4ed8'
  on-secondary: '#ffffff'
  secondary-container: '#4069f2'
  on-secondary-container: '#fffbff'
  tertiary: '#943700'
  on-tertiary: '#ffffff'
  tertiary-container: '#bc4800'
  on-tertiary-container: '#ffede6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea7'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b7c4ff'
  on-secondary-fixed: '#001551'
  on-secondary-fixed-variant: '#0039b5'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7d2d00'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-lg:
    fontFamily: Open Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Open Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Open Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Open Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Open Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Open Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  label-md:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Open Sans
    fontSize: 12px
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
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

The design system establishes a luminous, trustworthy, and modern educational environment tailored for driving instruction and certification. The target audience encompasses new student drivers, licensing candidates, instructors, and fleet administrators seeking clarity, efficiency, and authoritative guidance.

The UI evokes safety, confidence, and absolute clarity. By adhering to a refined Modern Corporate and Clean Functional aesthetic, the experience relies on pure, brilliant whites, sharp slate-black typography, crisp borders, and authoritative blue accents. The visual field eliminates visual noise, ensuring critical instructions, driving modules, schedule booking, and verification workflows are immediately legible and reassuring.

## Colors

The palette is anchored by crisp, high-contrast values designed to maximize daylight readability and functional hierarchy:

- **Primary Canvas & Surfaces:** Absolute Pure White (`#ffffff`) serves as the base layer, creating an expansive, clean field of focus.
- **Surface Containers:** Soft gray neutral tints (`#f9fafb` and `#f3f4f6`) define distinct card bodies, data tables, and subtle compartmentalized sections without creating visual weight.
- **Typography & High-Contrast Elements:** Crisp, deep blacks (`#111827` for dominant headings, `#1f2937` for standard copy, and `#4b5563` for secondary descriptors) provide optimal contrast ratios exceeding WCAG AAA standards.
- **Interactive Accents:** Vivid Blue (`#2563eb`) drives primary interactive controls, state highlights, and focus states, transitioning to Royal Blue (`#1d4ed8`) on active and hover states.
- **Borders & Dividers:** Subtle, structural borders use `#e5e7eb`, producing defined, hairline separations across the entire application.

## Typography

The typography relies entirely on Open Sans, chosen for its open apertures, high legibility across screens, and neutral, professional character. 

Headings command attention through deliberate weight distribution (`600` and `700`) and tighter letter spacing on larger sizes, maintaining a structured, academic look. Body typography balances line height at 1.5x font size to facilitate effortless reading of instructional modules, driving laws, and scheduling guidelines. Form labels, status indicators, and button controls utilize semi-bold tracking for instantaneous recognition.

## Layout & Spacing

The layout is built upon an 8-point rhythmic grid and a responsive 12-column layout container (collapsing to 8 columns on tablet and 4 columns on mobile). 

- **Desktop (>= 1024px):** 12-column fluid structure constrained to a maximum content width of 1280px, flanked by `2rem` margins and `1.5rem` gutters.
- **Tablet (768px - 1023px):** 8-column layout utilizing `1.5rem` margins and `1rem` gutters.
- **Mobile (< 768px):** 4-column layout utilizing `1rem` margins and `1rem` gutters.

Spacing tokens dictate intentional white space to avoid visual clutter. Card interiors, structured forms, and data grids rely on `space-md` (16px) and `space-lg` (24px) padding to create an airy, unhurried, and disciplined visual cadence.

## Elevation & Depth

This design system rejects heavy, dark drop shadows in favor of a crisp architectural approach based on low-contrast outlines, tonal surface shifts, and minimal ambient lighting.

- **Primary Elevation (Flat / Base):** Pure white `#ffffff` canvas with no shadow. Structural segregation is achieved using crisp 1px borders of `#e5e7eb`.
- **Secondary Elevation (Cards & Panels):** Subtle contrast is delivered via `#f9fafb` fills bounded by 1px borders in `#e5e7eb`.
- **Elevated Interactive Objects (Dropdowns, Dialogs, Floating Navbars):** Surface uses `#ffffff` bounded by a 1px `#e5e7eb` border paired with an ultra-soft ambient shadow: `0px 4px 20px -2px rgba(17, 24, 39, 0.05)`.
- **Focus & Selection Depth:** Focused interactive elements avoid fuzzy halos; they receive an explicit 2px outline in Primary Blue (`#2563eb`) offset by 2px white space.

## Shapes

The design system implements a controlled, modern rounded corner philosophy (`level 2`). Standard controls, input boxes, badges, and default action elements feature an 8px (`0.5rem`) corner radius. Larger structural containers, dashboards, and curriculum cards leverage 16px (`1rem`) corner radii.

This balanced curvature softens the clinical precision of pure white and hairline gray borders, yielding an approachable yet rigorously organized user experience suitable for safety-oriented vehicle education.

## Components

- **Buttons:**
  - *Primary Button:* Solid `#2563eb` background, `#ffffff` text, 8px radius, height 44px, horizontal padding `1.25rem`. Hover transitions to `#1d4ed8`.
  - *Secondary Button:* Transparent background, `#111827` text, 1px border `#e5e7eb`. Hover transitions to `#f9fafb` surface with `#111827` border.
  - *Destructive / Danger:* Solid `#dc2626` background, `#ffffff` text.

- **Input Fields & Selectors:**
  - Background `#ffffff`, text `#111827`, placeholder `#9ca3af`.
  - 1px border `#e5e7eb` resting. Active/Focus state uses 1px `#2563eb` with a 3px ring of `#2563eb` at 15% opacity. Standard height: 44px.

- **Cards & Data Modules:**
  - Surface: `#ffffff` or minimal soft gray `#f9fafb`.
  - Defined by a clean 1px border `#e5e7eb`, 16px rounded corners, and interior padding of `1.5rem`.
  - Interactive cards introduce a subtle border shift to `#2563eb` on hover.

- **Chips & Badges:**
  - Metric status, module tags, and lesson stages utilize 6px radius tags.
  - Informational tag: `#eff6ff` background with `#1d4ed8` text and 1px border `#dbeafe`.
  - Neutral tag: `#f3f4f6` background with `#374151` text and 1px border `#e5e7eb`.

- **Checkboxes & Radios:**
  - Base state: `#ffffff` background with 1.5px border `#d1d5db`, 4px radius (checkbox) or circular (radio).
  - Selected state: Solid `#2563eb` fill with a crisp white inner icon or dot.

- **Curriculum & Booking Specifics (Domain Components):**
  - *Lesson Progress Bar:* Height 8px, `#f3f4f6` track, filled with `#2563eb` indicator and 9999px pill rounding.
  - *Instructor Card:* Minimalist horizontal layout, soft gray container (`#f9fafb`), border `#e5e7eb`, featuring license credential chips and high-contrast text.