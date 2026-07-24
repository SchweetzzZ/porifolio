---
name: Obsidian Blueprint
colors:
  surface: '#10131a'
  surface-dim: '#10131a'
  surface-bright: '#363941'
  surface-container-lowest: '#0b0e15'
  surface-container-low: '#191b23'
  surface-container: '#1d2027'
  surface-container-high: '#272a31'
  surface-container-highest: '#32353c'
  on-surface: '#e1e2ec'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#e1e2ec'
  inverse-on-surface: '#2e3038'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#b1c6f9'
  on-secondary: '#182f59'
  secondary-container: '#304671'
  on-secondary-container: '#9fb5e7'
  tertiary: '#ffb786'
  on-tertiary: '#502400'
  tertiary-container: '#df7412'
  on-tertiary-container: '#461f00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#b1c6f9'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#304671'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#ffb786'
  on-tertiary-fixed: '#311400'
  on-tertiary-fixed-variant: '#723600'
  background: '#10131a'
  on-background: '#e1e2ec'
  surface-variant: '#32353c'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  code-sm:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 64px
  section-padding: 120px
---

## Brand & Style

The design system is engineered for a high-end backend developer portfolio, prioritizing technical maturity and precision. It employs a **Modern Minimalism** aesthetic with a focus on deep verticality and structural clarity. The visual narrative is built on the concept of "the terminal at night"—high-contrast text against an expansive, dark void, punctuated by functional color.

The target audience consists of technical recruiters and engineering leads who value efficiency, clean code, and architectural rigor. The UI should evoke a sense of calm, focused expertise and uncompromising quality through generous whitespace and a restricted, premium color palette.

## Colors

The palette is centered on a "Deep Night" foundation. The primary background (#0B0F1A) provides an ink-black canvas that makes code and typography pop. 

- **Primary Accent**: A vibrant, high-energy Blue (#3B82F6) used exclusively for interactive elements, focus states, and key call-to-actions.
- **Surface Strategy**: We use a tiered gray system. `surface-1` (#111827) for containers and `surface-2` (#1F2937) for borders and dividers.
- **Typography**: Pure white is avoided to reduce eye strain; instead, use Off-White (#F9FAFB) for headings and Muted Gray (#9CA3AF) for body text to establish a clear information hierarchy.

## Typography

This design system utilizes **Inter** for all primary communication due to its exceptional legibility and neutral, professional tone. To lean into the "developer" aesthetic, **Geist** (or a similar high-quality monospaced font) is used for labels, metadata, and code snippets.

- **Display**: Reserved for the hero section; tight tracking and heavy weight convey confidence.
- **Body**: Set with generous line-height (1.6) to ensure long-form technical case studies remain readable.
- **Labels**: Always use the monospaced font in uppercase for a technical, "instrument cluster" feel.

## Layout & Spacing

The layout follows a **Fixed Grid** approach for desktop to maintain a controlled, editorial feel, transitioning to a fluid single-column for mobile.

- **Vertical Rhythm**: A strict 8px base unit is used. Sections are separated by large gaps (120px+) to emphasize the minimalist "premium" aesthetic.
- **Content Width**: Information-heavy sections (like blog posts) should be constrained to a 720px readable width, while project galleries utilize the full 1200px container.
- **Mobile Reflow**: On mobile, horizontal padding reduces to 16px, and stack spacing scales down by 25% to maintain density.

## Elevation & Depth

This design system avoids traditional shadows in favor of **Tonal Layers** and **Subtle Outlines**. Depth is communicated through luminosity rather than blur.

- **Surface Levels**: Elements "closer" to the user are rendered in slightly lighter grays (#111827).
- **Borders**: Interactive cards and containers use a 1px solid border (#1F2937).
- **Interactive State**: On hover, the border color should shift to the primary blue (#3B82F6) at 50% opacity, creating a "glow" effect that feels technical and reactive.
- **Glassmorphism**: Use backdrop filters (blur: 12px) sparingly for navigation bars to maintain context of the background content during scroll.

## Shapes

The shape language is defined by **Large Radii (2xl)**. Despite the technical nature of the site, the rounded corners prevent the UI from feeling "sharp" or "aggressive," landing instead on a "refined and approachable" tone.

- **Standard Containers**: Use 1rem (16px) for cards and sections.
- **Buttons & Inputs**: Use 0.75rem (12px) to maintain a cohesive look with larger containers.
- **Code Blocks**: Should match the 1rem radius to soften the technical content.

## Components

- **Buttons**: Primary buttons are solid Blue (#3B82F6) with white text. Secondary buttons use a ghost style (border-only) with the primary blue for text and border.
- **Cards**: Project cards feature a subtle gradient background (from #111827 to #0B0F1A) and a 1px border. No shadows.
- **Inputs**: Field backgrounds should be darker than the surface they sit on. The focus state is a 2px blue border.
- **Chips/Tags**: Small, monospaced text inside a subtle gray capsule. Used for tech stack listing (e.g., "Go", "Kubernetes").
- **Code Snippets**: Styled to look like a terminal window with three decorative window controls (red, yellow, green) in the top-left corner.
- **Status Indicators**: Use a small "pulsing" dot next to "Available for work" text to add a sense of liveness to the portfolio.