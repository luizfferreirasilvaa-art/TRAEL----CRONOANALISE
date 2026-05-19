---
name: Industrial Precision
colors:
  surface: '#0d1321'
  surface-dim: '#0d1321'
  surface-bright: '#333948'
  surface-container-lowest: '#080e1b'
  surface-container-low: '#151b29'
  surface-container: '#191f2d'
  surface-container-high: '#242a38'
  surface-container-highest: '#2f3543'
  on-surface: '#dde2f6'
  on-surface-variant: '#c5c6d0'
  inverse-surface: '#dde2f6'
  inverse-on-surface: '#2a303f'
  outline: '#8e909a'
  outline-variant: '#44464f'
  surface-tint: '#b0c6ff'
  primary: '#b0c6ff'
  on-primary: '#152e60'
  primary-container: '#7a90c7'
  on-primary-container: '#0c2759'
  inverse-primary: '#475d91'
  secondary: '#b3ccc1'
  on-secondary: '#1e352d'
  secondary-container: '#374e45'
  on-secondary-container: '#a5beb3'
  tertiary: '#6adbaf'
  on-tertiary: '#003827'
  tertiary-container: '#28a37b'
  on-tertiary-container: '#003121'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b0c6ff'
  on-primary-fixed: '#001945'
  on-primary-fixed-variant: '#2e4578'
  secondary-fixed: '#cee8dc'
  secondary-fixed-dim: '#b3ccc1'
  on-secondary-fixed: '#081f18'
  on-secondary-fixed-variant: '#354b43'
  tertiary-fixed: '#87f8ca'
  tertiary-fixed-dim: '#6adbaf'
  on-tertiary-fixed: '#002115'
  on-tertiary-fixed-variant: '#00513a'
  background: '#0d1321'
  on-background: '#dde2f6'
  surface-variant: '#2f3543'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
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
  label-md:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Geist
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 12px
    letterSpacing: 0.08em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  grid-gutter: 20px
  canvas-margin: 40px
---

## Brand & Style

This design system is engineered for high-stakes operational environments where clarity, speed of cognition, and reliability are paramount. It adopts an **Expressive Technical** aesthetic, blending the efficiency of a professional ERP with a more modern, nuanced color palette that maintains engineering precision.

The UI evokes a "Modern Control Center" atmosphere—focused and utilitarian, yet visually engaging. It prioritizes information density without sacrificing legibility. Every element is designed to feel like a structural component of a robust system, using clear hierarchies and intentional color hits to guide users through complex logic and data flows.

## Colors

The palette has transitioned to a more expressive set of technical tones. The foundation is built on **Steel Blue** for structural elements, balanced by **Muted Sage** and **Vibrant Emerald** for status and action.

- **Primary (Steel Blue):** Used for main interactive components, active headers, and primary branding elements.
- **Secondary (Sage):** Used for supporting UI elements, secondary containers, and balanced highlights.
- **Tertiary (Vibrant Emerald):** Reserved for success states, critical path completions, and high-visibility flowchart indicators.
- **Neutral (Cool Gray):** Used for borders, inactive states, and secondary icons to maintain a professional, de-saturated backdrop.
- **Backgrounds:** Continues to use a dark, deep-set surface to ensure the expressive primary and emerald accents stand out.

## Typography

The design system utilizes **Inter** for all primary UI and body copy due to its exceptional legibility and neutral, professional tone. For technical data, serial numbers, and industrial identifiers, **Geist** is employed to provide a monospaced, "coded" feel that aligns with engineering standards.

- **Hierarchy:** Use bold weights for headers to maintain high contrast against the dark background.
- **Labels:** Small labels should always be in uppercase with slight letter spacing to mimic industrial equipment marking and engraving.

## Layout & Spacing

The layout is built on a **Strict 12-Column Fixed Grid** for the dashboard components, while the flowchart canvas utilizes a **Fixed Dot-Grid** (20px increments) for element snapping. 

- **Density:** The layout favors a high-density approach. Information should be packed tightly but organized through clear borders and logical grouping.
- **Flowchart Canvas:** The main workspace should have 40px padding from the edge of the viewport. Nodes should snap to the 20px grid to ensure alignment across complex industrial paths.
- **Responsive:** On tablet, the sidebar collapses into an icon-only rail. On mobile, the flowchart is viewed in a read-only zoomable mode with a bottom-sheet for node details.

## Elevation & Depth

To maintain the "technical tool" feel, this design system avoids soft, ambient shadows. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines** to define depth.

- **Level 0 (Canvas):** The darkest surface.
- **Level 1 (Panels):** Slightly lighter surface with a 1px solid border derived from the Neutral palette (#717788).
- **Level 2 (Nodes/Cards):** Higher contrast backgrounds with distinct 2px borders. When a node is active, the border shifts to Steel Blue or Vibrant Emerald depending on state.
- **Floating Elements:** Modals and tooltips use a "Glassmorphism" effect with a heavy backdrop blur (12px) and a subtle 1px white-alpha border to simulate a glass-fronted industrial gauge.

## Shapes

The shape language is **Soft-Technical**. We avoid perfectly sharp corners to ensure the UI feels modern, but keep the radius very tight (4px / 0.25rem) to maintain a sense of structural rigidity and precision.

- **Buttons & Inputs:** Use a 4px radius.
- **Flowchart Nodes:** Use a 4px radius for the main body. Connection points (ports) are perfect circles to differentiate them from the node structure.
- **Progress Bars:** Should be square-ended to look like mechanical indicators rather than consumer-grade sliders.

## Components

### Buttons
- **Primary:** Solid Steel Blue (#6076ac) with high-contrast white text.
- **Secondary:** Transparent with a 2px Cool Gray border.
- **Success/Action:** Solid Emerald (#03936c) for final confirmations or "Go" actions.

### Nodes (Flowchart Cards)
- **Structure:** A header section with an icon, a main body for status data, and footer for timestamps.
- **State Indicators:** A vertical 4px "status bar" on the left edge of the card (Emerald for active/success, Red for fault, Steel Blue for neutral/processing).

### Input Fields
- Dark backgrounds with a 1px border that glows Steel Blue when focused. Labels are always positioned top-left in `label-sm` style.

### Chips & Tags
- Rectangular with 2px radius. Used for "Station IDs" or "Sensor Types." Use high-contrast background tints (e.g., Sage background with dark text).

### Connectivity Lines
- 2px solid lines with orthogonal (right-angle) routing. Use arrows to indicate flow direction. Active flows should "pulse" using a subtle Emerald animation.