---
name: Modern Smart-Campus Booking
colors:
  surface: '#121316'
  surface-dim: '#121316'
  surface-bright: '#38393c'
  surface-container-lowest: '#0d0e11'
  surface-container-low: '#1a1c1e'
  surface-container: '#1f2022'
  surface-container-high: '#292a2c'
  surface-container-highest: '#343537'
  on-surface: '#e3e2e5'
  on-surface-variant: '#c4c6cf'
  inverse-surface: '#e3e2e5'
  inverse-on-surface: '#2f3033'
  outline: '#8e9198'
  outline-variant: '#43474e'
  surface-tint: '#afc8f0'
  primary: '#afc8f0'
  on-primary: '#163152'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#476083'
  secondary: '#b8c8da'
  on-secondary: '#223240'
  secondary-container: '#394857'
  on-secondary-container: '#a7b7c8'
  tertiary: '#66dd8b'
  on-tertiary: '#003919'
  tertiary-container: '#00250e'
  on-tertiary-container: '#119b50'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#d4e4f6'
  secondary-fixed-dim: '#b8c8da'
  on-secondary-fixed: '#0d1d2a'
  on-secondary-fixed-variant: '#394857'
  tertiary-fixed: '#83fba5'
  tertiary-fixed-dim: '#66dd8b'
  on-tertiary-fixed: '#00210c'
  on-tertiary-fixed-variant: '#005227'
  background: '#121316'
  on-background: '#e3e2e5'
  surface-variant: '#343537'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
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
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1440px
  gutter: 24px
  margin-desktop: 40px
  margin-tablet: 24px
  margin-mobile: 16px
  grid-columns: '12'
---

## Brand & Style
The design system embodies a "Futuristic Academic" aesthetic, merging the prestige of a traditional institution with the cutting-edge efficiency of a modern SaaS platform. It targets a tech-savvy student body and faculty who require high-velocity scheduling tools within a premium, focused environment.

The visual direction is rooted in **Glassmorphism**. This approach uses translucency to create a sense of digital depth and "breathability," ensuring that even data-dense dashboards feel light and navigable. The emotional response should be one of confidence, clarity, and technological sophistication, moving away from the clunky, administrative feel of legacy campus portals toward a high-end, responsive workspace.

## Colors
The palette leverages a high-contrast dark mode to emphasize the glass effects. 

*   **Primary (Deep Navy):** Used for the structural foundations, deep backgrounds, and primary navigation surfaces.
*   **Secondary (Slate Blue):** Applied to secondary text, icons, and subtle UI borders to provide a soft contrast against the navy.
*   **Emerald (#50C878):** Reserved for "Active," "Available," and "Success" states. It serves as a high-visibility energetic pulse within the interface.
*   **Gold (#FFD700):** Used sparingly for premium highlights, featured resources, and critical calls to action (CTAs).
*   **Surface:** Semi-transparent whites (e.g., `rgba(255, 255, 255, 0.05)`) are used to create the frosted glass panes.

## Typography
The system utilizes a dual-font strategy. **Montserrat** provides a geometric, bold authority for headlines, evoking the "Institutional" side of the brand. **Inter** handles all functional data and body copy, ensuring maximum legibility across dense booking grids and schedules.

Clear hierarchy is maintained through strict use of weight; labels are often uppercased with increased letter spacing to distinguish them from interactive data points.

## Layout & Spacing
The design system employs a **fluid 12-column grid** for desktop and tablet, transitioning to a single-column stacked layout for mobile. 

A consistent 8px spacing system governs all internal padding. Large margins (40px) on the outer edges of the dashboard ensure the content feels like it is floating over the vibrant background blurs. Content should be grouped in modular glass cards, allowing the layout to reflow naturally based on the screen width.

## Elevation & Depth
Depth is achieved through **Glassmorphism layers** rather than traditional drop shadows. 

1.  **Level 0 (Background):** A deep navy base with large, soft blurs of Emerald and Navy (`blur(100px)`) to create atmospheric movement.
2.  **Level 1 (Panels):** Frosted glass panels using `backdrop-filter: blur(20px)` and a thin, 1px semi-transparent border (`rgba(255, 255, 255, 0.1)`).
3.  **Level 2 (Popovers/Modals):** High-opacity glass with a subtle outer glow (Emerald or Gold) to indicate focus.

Shadows are "ambient" and tinted; instead of black, use a desaturated navy shadow with a high spread and low opacity to maintain the glow effect.

## Shapes
This design system uses a **Rounded** shape language to soften the futuristic aesthetic and make the application feel accessible. 

Main dashboard cards and container panels use `rounded-xl` (1.5rem) to emphasize the "pod" or "module" feel. Buttons and input fields use standard `rounded` (0.5rem) for a precise, professional touch. Avatars and status indicators utilize pill-shapes for instant recognition.

## Components

*   **Glass Cards:** The primary container. Features a subtle linear gradient stroke from top-left (light) to bottom-right (dark) to simulate light hitting glass.
*   **Interactive Buttons:** Primary buttons use a solid Gold or Emerald fill with a slight hover lift and an outer glow. Secondary buttons use a "Ghost Glass" style: transparent with a 1px border.
*   **Booking Grid:** A dense, high-contrast calendar view using Slate Blue for grid lines and vibrant Emerald blocks for "Available" slots.
*   **Input Fields:** Translucent backgrounds with a high-contrast focus state where the border color changes to Emerald and the backdrop blur intensifies.
*   **Status Chips:** Small, pill-shaped indicators with high-vibrancy text colors against a low-opacity version of the same color (e.g., Emerald text on `rgba(80, 200, 120, 0.1)` background).
*   **Hover Effects:** All interactive elements must have a smooth transition (200ms ease-out). Glass cards should slightly increase in opacity or scale (1.02x) when hovered to provide tactile feedback.