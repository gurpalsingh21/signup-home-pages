---
name: Calm Clarity
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
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#515659'
  on-tertiary: '#ffffff'
  tertiary-container: '#696e71'
  on-tertiary-container: '#edf1f5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#dfe3e7'
  tertiary-fixed-dim: '#c3c7cb'
  on-tertiary-fixed: '#171c1f'
  on-tertiary-fixed-variant: '#43474b'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: 0em
  label-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
    letterSpacing: 0.01em
  caption:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1rem
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
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
---

## Brand & Style
The design system embodies modern minimalism with a resolute focus on frictionless onboarding, trust, and cognitive clarity. It targets discerning users interacting with high-utility modern web applications where clarity of intent reduces drop-off rates and inspires confidence.

The aesthetic blends utilitarian simplicity with refined structural hygiene:
- High contrast hierarchy with meticulous typographic balance.
- Uncluttered, purposeful whitespace eliminating sensory noise.
- Tactile, deliberate focus rings and responsive micro-interactions that reassure users during authentication and input sequences.

## Colors
The palette enforces strict structural contrast:
- **Canvas & Backgrounds:** The base viewport sits on `#f8fafc` (slate-50), with `#f1f5f9` (slate-100) utilized for secondary panels, decorative backdrops, and muted interactive states. Elevated sign-up cards and functional modals strictly sit on `#ffffff`.
- **Text & Structure:** Primary text and high-priority labels use `#0f172a` (slate-900). Secondary metadata, helper text, and placeholders use `#64748b` (slate-500). Borders and dividers rely on `#e2e8f0` (slate-200).
- **Accents & Interactions:** `#2563eb` drives primary call-to-action fills, focused form ring highlights, active checks, and primary text links. `#3b82f6` serves as the hover/active transition state.
- **Form States:** Error feedback utilizes `#ef4444` (red-500) paired with `#fef2f2` (red-50) tinted validation backgrounds.

## Typography
Inter delivers systematic clarity across dense forms and minimal structural layouts.
- **Headlines:** Form headers and hero branding leverage tighter letter tracking (`-0.025em` to `-0.015em`) with medium and bold weights to ground the visual hierarchy cleanly.
- **Form Inputs & Labels:** Field labels employ `label-md` (0.875rem, font-weight 500) to ensure immediate scanning legibility. Body text and field inputs default to 0.875rem or 1rem to eliminate auto-zoom triggers on mobile viewports.
- **Numbers & Metadata:** Numerical indicators like password strength criteria and verification codes inherit tabular numeral features (`font-feature-settings: 'tnum' on`).

## Layout & Spacing
The layout model is anchored to a dual-state composition:
- **Desktop (>= 1024px):** Split-screen layout. Left side showcases an accent editorial panel (#f1f5f9 or subtle brand visual); right side houses a centered fixed-max-width (440px) authentication card within a fluid container.
- **Tablet (768px - 1023px):** Centered card layout (max-w-[480px]) with `margin: 2rem` canvas padding over a `#f8fafc` background.
- **Mobile (< 768px):** Single-column stacked fluid layout with `margin-mobile: 1rem`. The authentication surface fills width seamlessly while respecting minimum safe area margins.
- **Form Rhythm:** Strict 16px (`space-md`) vertical separation between standard form fields, expanded to 24px (`space-lg`) between logical sections (e.g., social auth splitters, submission CTA).

## Elevation & Depth
Visual hierarchy relies on low-contrast structural outlines paired with light, diffused ambient elevation:
- **Card Surfaces:** Main auth cards utilize a crisp border (`1px solid #e2e8f0`) complemented by a gentle ambient drop shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.05), 0 2px 4px -2px rgba(15, 23, 42, 0.03)`.
- **Active / Focused Interactive States:** Elevation changes are flattened in favor of clear 2px offset rings (`outline: 2px solid #2563eb; outline-offset: 2px;`) to preserve clean lines without heavy shadows.
- **Floating Modals / Dropdowns:** Elevated components use `box-shadow: 0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.03)` with standard 1px border (#e2e8f0).

## Shapes
The design system standardizes on crisp, controlled corners.
- Default controls, input wrappers, checkboxes, and buttons share an 8px (`rounded-lg` / 0.5rem in CSS implementation) radius.
- Enclosing cards use matching 8px to 12px corners for structural alignment.
- Chips, badge pills, and avatar placeholders use fully rounded geometry (`rounded-full` / 9999px) to establish deliberate contrast against rectangular form structures.

## Components

### Input Fields
- **Dimensions & Geometry:** Strict minimum height of 44px (`min-h-[44px]`), 8px border radius, horizontal interior padding of 14px.
- **Color & Border:** Surface background `#ffffff`, border `1px solid #e2e8f0`, text `#0f172a`, placeholder `#64748b`.
- **Focus State:** Border color shifts to `#2563eb` with an outer focus ring (`box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.2)` or `ring-2 ring-blue-600 ring-offset-2`).
- **Error State:** Border transitions to `#ef4444`, paired with a light red ring tint (`rgba(239, 68, 68, 0.15)`) and inline error caption underneath.

### Buttons
- **Primary CTA:** Minimum height of 44px (`h-11`), filled background `#2563eb`, crisp white text (`#ffffff`), font-weight 500, radius 8px. Hover state shifts to `#1d4ed8`; focus state triggers `#2563eb` 2px ring offset.
- **Secondary / Social Auth:** Border `1px solid #e2e8f0`, surface `#ffffff`, text `#0f172a`. Hover state transitions to background `#f8fafc` and border `#cbd5e1`.
- **Disabled State:** Background `#f1f5f9`, border `#e2e8f0`, text `#94a3b8`, cursor not-allowed.

### Checkboxes & Radios
- **Checkboxes:** Size 18px x 18px, border `1px solid #cbd5e1`, 4px radius. Checked state fills `#2563eb` with sharp white SVG check icon. Focus indicator adds 2px offset ring in `#2563eb`.
- **Alignment:** Aligned to top-start (`items-start`) when paired with multi-line legal or terms of service text labels.

### Social Dividers & Chips
- **Divider:** Subtle `1px solid #e2e8f0` horizontal rules flanking a centered `#64748b` uppercase label-sm (`0.75rem`) reading "OR CONTINUE WITH".
- **Chips / Badges:** 24px height, background `#f1f5f9`, text `#0f172a`, radius 9999px, padding 2px 8px.

### Cards & Accent Panels
- **Auth Card:** Background `#ffffff`, border `1px solid #e2e8f0`, padding 32px (`space-xl`) on desktop, 20px on mobile.
- **Side Panel (Desktop):** Background `#f1f5f9`, structural border-right `1px solid #e2e8f0`, housing subtle brand typography and onboarding narrative.