---
name: Eco-Tech Intelligence
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#3c4a42'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#555f70'
  on-secondary: '#ffffff'
  secondary-container: '#d6e0f4'
  on-secondary-container: '#596374'
  tertiary: '#494bd6'
  on-tertiary: '#ffffff'
  tertiary-container: '#9699ff'
  on-tertiary-container: '#1d17b2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#d9e3f7'
  secondary-fixed-dim: '#bdc7db'
  on-secondary-fixed: '#121c2a'
  on-secondary-fixed-variant: '#3d4757'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-xl:
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
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-margin: 24px
  gutter: 16px
  card-padding: 24px
  section-gap: 40px
---

## Brand & Style
The design system embodies an **Eco-Tech** aesthetic—a fusion of environmental responsibility and high-precision technology. It is designed for municipal and industrial operators who require a professional, reliable, and high-readability interface to manage complex waste logistics.

The visual language is rooted in **Minimalism** with a focus on functional clarity. It uses expansive whitespace to reduce cognitive load, while subtle glassmorphism and soft shadows provide a sense of modern depth. The emotional response is one of calm efficiency, trust, and forward-thinking sustainability.

## Colors
The palette is centered around **Emerald Green**, representing growth and environmental health. This is contrasted against **Charcoal Gray** for high-legibility text and structural elements.

*   **Primary (Emerald):** Used for primary actions, success states, and "Empty" capacity indicators.
*   **Secondary (Charcoal):** Used for typography and iconography to ensure professional grounding.
*   **Background (Light Gray):** A cool, neutral base that allows data visualizations to pop.
*   **Status Tints:** A semantic trio (Green/Amber/Red) is used specifically for fill-level monitoring to provide instant at-a-glance status updates.

## Typography
This design system utilizes **Inter** for all roles. Inter’s tall x-height and systematic spacing provide the "utilitarian yet modern" feel required for data-heavy dashboards.

Headlines use tighter letter-spacing and heavier weights to create a strong visual hierarchy, while body text maintains standard tracking for optimal readability. Labels are frequently used for data metadata and status indicators, often employing a medium weight to stand out against background surfaces.

## Layout & Spacing
The layout follows a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile devices. 

*   **Rhythm:** An 8px base unit governs all dimensions.
*   **Margins:** 24px safe areas on mobile, scaling to 40px or centered max-width (1440px) on desktop.
*   **Dashboard Cards:** Elements are grouped into cards that span 3, 4, 6, or 12 columns depending on the complexity of the data visualization (e.g., small gauges span 3 columns, large line charts span 12).

## Elevation & Depth
Elevation is achieved through a combination of **Tonal Layers** and **Ambient Shadows**.

1.  **Level 0 (Background):** The neutral Light Gray surface.
2.  **Level 1 (Cards/Containers):** Pure white surfaces with a soft, highly diffused shadow (0px 4px 20px rgba(0, 0, 0, 0.05)).
3.  **Level 2 (Interaction/Popovers):** Elements that float above the main UI use a more pronounced shadow (0px 10px 30px rgba(0, 0, 0, 0.08)) and a 1px subtle border (#E5E7EB).

Avoid heavy black shadows; instead, use shadows tinted slightly with the primary or secondary color to maintain the clean, "Eco-Tech" feel.

## Shapes
The design system uses a **Rounded** shape language to appear approachable and modern. 

*   **Standard Components:** Buttons and inputs use a 0.5rem (8px) radius.
*   **Large Components:** Dashboard cards and status containers use "rounded-lg" (16px) or "rounded-xl" (24px) to emphasize the soft, high-tech aesthetic.
*   **Data Elements:** Bar charts should have rounded top caps, and gauge tracks should be fully rounded (pill-shaped) to match the overall softness.

## Components

### Status Indicators
*   **Gauges:** Circular progress indicators with a thick track (12px). The fill color dynamically changes based on capacity: 0-50% (Emerald), 51-80% (Amber), 81-100% (Red).
*   **Status Badges:** Small, pill-shaped chips with a light tinted background and dark text (e.g., Light Green background with Dark Green text for "Empty").

### Data Visualization
*   **Line Graphs:** Use a 3px stroke width for the primary data line. Use a soft Emerald gradient fill beneath the line to create a sense of volume.
*   **Bar Charts:** Use rounded corners on the top of bars. Use Charcoal Gray for axes and grid lines at 10% opacity.

### Interaction Elements
*   **Buttons:** Primary buttons are solid Emerald Green with white text. Secondary buttons use a Charcoal outline. Both feature a subtle lift on hover (increase shadow spread).
*   **Input Fields:** Clean white backgrounds with a 1px Light Gray border that turns Emerald on focus.
*   **Cards:** The primary container for all dashboard content. Cards must have a 24px internal padding and use the Level 1 elevation shadow.

### Specialized Components
*   **Bin Detail Card:** Includes a large gauge, a status badge, and a timestamp of the last collection.
*   **Route Map:** Integrated map view with custom Emerald map pins for smart bin locations.