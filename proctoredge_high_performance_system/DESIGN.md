---
name: ProctorEdge High-Performance System
colors:
  surface: '#111125'
  surface-dim: '#111125'
  surface-bright: '#37374d'
  surface-container-lowest: '#0c0c1f'
  surface-container-low: '#1a1a2e'
  surface-container: '#1e1e32'
  surface-container-high: '#28283d'
  surface-container-highest: '#333348'
  on-surface: '#e2e0fc'
  on-surface-variant: '#c7c4d8'
  inverse-surface: '#e2e0fc'
  inverse-on-surface: '#2f2e43'
  outline: '#918fa1'
  outline-variant: '#464555'
  surface-tint: '#c3c0ff'
  primary: '#c3c0ff'
  on-primary: '#1d00a5'
  primary-container: '#635bff'
  on-primary-container: '#fefaff'
  inverse-primary: '#4c42e9'
  secondary: '#fbd12d'
  on-secondary: '#3b2f00'
  secondary-container: '#dcb500'
  on-secondary-container: '#594700'
  tertiary: '#fbb3c1'
  on-tertiary: '#50212d'
  tertiary-container: '#9f6370'
  on-tertiary-container: '#fffaff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#321ed2'
  secondary-fixed: '#ffe07d'
  secondary-fixed-dim: '#ebc31a'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#564500'
  tertiary-fixed: '#ffd9df'
  tertiary-fixed-dim: '#fbb3c1'
  on-tertiary-fixed: '#360c19'
  on-tertiary-fixed-variant: '#6b3743'
  background: '#111125'
  on-background: '#e2e0fc'
  surface-variant: '#333348'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 84px
    fontWeight: '800'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
  data-mono:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-page: 48px
  section-padding: 80px
---

## Brand & Style

This design system establishes a visual identity that is **energetic, unconventional, and high-performance**. It subverts the traditional "clinical" look of educational software by adopting a bold, high-contrast aesthetic rooted in Neo-Brutalism. The brand communicates a message of "Integrity, without intrusion," utilizing professional but playful illustrative elements to humanize the proctoring experience.

The style is characterized by:
- **Neo-Brutalism:** Thick black borders (3px+), hard drop shadows, and vibrant color blocks.
- **Precision SaaS Utility:** While the marketing and splash elements are playful and irregular, the core dashboard utilizes a rigorous grid to ensure data density and clarity for institutional users.
- **Sophisticated Dark Mode:** A deep indigo foundation that provides a premium, high-end feel while allowing the bold accent colors to pop.

## Colors

The palette is anchored in a sophisticated dark mode, utilizing deep indigos and purples for backgrounds to maintain a "pro" SaaS atmosphere.

- **Primary (Indigo/Purple):** Used for primary actions and brand identity. It provides the depth needed for a high-end dashboard.
- **Secondary (Yellow):** A high-visibility accent for "Live" status indicators, alerts, and critical CTA buttons.
- **Tertiary (Pink/Cream):** Used for decorative elements, secondary cards, and illustrative highlights to soften the brutalist edges.
- **Neutral/Base:** A deep, near-black indigo for the background with cream-tinted off-whites for text to reduce eye strain compared to pure white.

## Typography

This design system uses a dual-font strategy to balance character with utility.

- **Headlines:** Use **Bricolage Grotesque** for its chunky, expressive personality. In marketing sections, headlines should use tight tracking and occasional irregular tilts.
- **UI & Data:** **Hanken Grotesk** provides a clean, contemporary sans-serif experience for high-density data tables and settings.
- **Data Visualizations:** For timestamps and numeric proctoring logs, **Space Grotesk** (defined as `data-mono`) is used to ensure alignment and a "high-tech" feel.

## Layout & Spacing

The layout philosophy transitions from an **experimental, irregular rhythm** in top-level marketing and landing views to a **precise, 12-column fluid grid** within the dashboard.

- **Marketing/Onboarding:** Generous, uneven whitespace. Elements may break the grid or overlap slightly with bold borders to create a tactile, collage-like feel.
- **Dashboard:** Strict 24px gutters. Dashboard widgets are contained within rigid containers.
- **Desktop:** 12-column grid, 48px side margins.
- **Mobile:** 4-column grid, 16px side margins. Headlines scale down significantly (e.g., Display LG to 42px) to maintain readability.

## Elevation & Depth

Depth is conveyed through **Neo-Brutalist physical stacking** rather than light-based shadows.

- **Bold Shadows:** Instead of blurs, use "Hard Shadows"—solid offsets of black or deep indigo at 4px or 8px distances (e.g., `box-shadow: 4px 4px 0px #000`).
- **Surface Layering:** The background is the lowest level. Cards sit on top with a 3px solid border. Active states are indicated by the card "pressing down" (shadow offset moving to 0px).
- **No Blurs:** Avoid Gaussian blurs or glassmorphism. Clarity and sharpness are paramount for a proctoring tool where visual "noise" should be minimized in the data area.

## Shapes

The shape language is "Soft-Brutalist." While the borders are heavy and the shadows are hard, the corners are moderately rounded to maintain a premium SaaS feel.

- **Large Components (Cards, Modals):** `rounded-xl` (1.5rem) to create a friendly, modern container.
- **Small Components (Buttons, Inputs):** `rounded-lg` (1.0rem) for a comfortable touch target.
- **Stroke Weight:** Maintain a consistent 3px border on primary UI elements and 2px on secondary elements.

## Components

### Buttons
- **Primary:** Bright Yellow (#FAD02C) background, black 3px border, black text, 4px hard black shadow.
- **Secondary:** Transparent background, cream border, cream text. On hover, fills with Soft Pink (#FFB7C5).

### Cards & Widgets
- **Style:** Deep Indigo background (#1A1A2E), 3px black border, 8px hard black shadow. 
- **Header:** Use the "peeking character" illustration at the corner of high-priority cards (like "Live Flagged Events") to draw the eye.

### Input Fields
- **Style:** Darker indigo background, 2px cream border. On focus, the border becomes Yellow and the shadow expands.
- **Labels:** Always use `label-bold` above the field for maximum legibility.

### Chips & Status Indicators
- **High Alert:** Bright Yellow background, black text, rounded-full (pill).
- **Integrity Pass:** Soft Pink background, black text.
- **Neutral:** Deep Purple background, white text.

### Narrative Elements
- **Illustrations:** Use thick-lined, "rubber-hose" style characters (similar to the peeking figure) for empty states and onboarding.
- **Tagline Placement:** The "Integrity, without intrusion" tagline should be styled in the display font, placed at the bottom of navigation menus or on login splash screens.