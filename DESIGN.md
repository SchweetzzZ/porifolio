---
name: Technical Precision
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
  secondary: '#b7c8e1'
  on-secondary: '#213145'
  secondary-container: '#3a4a5f'
  on-secondary-container: '#a9bad3'
  tertiary: '#89ceff'
  on-tertiary: '#00344d'
  tertiary-container: '#009ada'
  on-tertiary-container: '#002d43'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#89ceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#10131a'
  on-background: '#e1e2ec'
  surface-variant: '#32353c'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  code-block:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1120px
  gutter: 24px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
---

## Brand & Style
The brand personality is authoritative yet understated, reflecting the discipline of a Senior Backend Developer. It prioritizes clarity, structural integrity, and performance over decorative flair. The target audience includes technical recruiters, engineering leads, and CTOs who value efficiency and architectural depth.

The design style is **Minimalist with a Technical Edge**. It utilizes high whitespace to ensure focus, a constrained color palette to signal professionalism, and subtle motion to indicate system reactivity. The aesthetic draws from "Developer-centric" modernism—clean lines, precise alignments, and a focus on content hierarchy.

## Colors
The palette is rooted in a **Rich Dark (#0F172A)** background to reduce eye strain and provide a premium canvas. The **Primary Electric Blue (#3B82F6)** is used sparingly for call-to-actions, active states, and critical highlights, ensuring high visibility without overwhelming the layout. 

Secondary and tertiary blues are utilized for code syntax highlighting and subtle UI accents. Neutral grays provide a clear hierarchy for typography, with pure white reserved only for the most important headings.

## Typography
The system uses **Geist** for its exceptional balance of geometric precision and readability, making it ideal for technical portfolios. **JetBrains Mono** is introduced for labels, metadata, and code snippets to reinforce the backend developer persona.

Headlines should be set with tight letter-spacing to appear more impactful. Body text maintains a generous line-height to ensure long-form project descriptions remain legible. Mobile typography scales down significantly to maintain a "single-screen" feel for project introductions.

## Layout & Spacing
This design system utilizes a **Fixed Grid** approach for desktop, centering content within a 1120px container to maintain readability on ultra-wide monitors. A 12-column system is used for project grids, while a 12-column sub-grid handles internal card layouts.

Vertical rhythm is strictly based on an 8px base unit. Section spacing is intentionally generous (120px) to give the developer's work "room to breathe," signaling a high-end, curated portfolio rather than a dense resume. On mobile, margins shrink to 20px, and section padding is reduced to 64px.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Subtle Outlines** rather than heavy shadows. 
- **Level 0 (Background):** #0F172A.
- **Level 1 (Cards/Surface):** #1E293B with a 1px border of #334155.
- **Level 2 (Hovers/Modals):** A subtle glow effect using the primary color at 5% opacity and a slightly brighter border (#475569).

Interactive elements should use a "Lift and Glow" transition: on hover, the border-color transitions to the Primary Blue, and a faint 20px blur of the Primary color appears behind the element.

## Shapes
Shapes are **Soft (4px - 12px)**. This degree of roundedness strikes a balance between the "hardness" of engineering and the "softness" of modern UI. 
- **Buttons and Inputs:** 6px radius for a precise, professional look.
- **Project Cards:** 12px radius to define larger content areas.
- **Tags/Chips:** 4px radius to maintain a modular, technical aesthetic.

## Components

### Buttons
Primary buttons use a solid Primary Blue background with white text. Secondary buttons use a "Ghost" style: a transparent background with a 1px border. Transitions must be instant (150ms) to reflect backend efficiency.

### Project Cards
Large-format cards featuring a header, a brief architectural summary, and a "Tech Stack" footer. The entire card is interactive, using the "Lift and Glow" hover state described in the Elevation section.

### Tabbed Navigation
Used for switching between "Experience," "Education," and "Skills." Tabs are text-only with a 2px bottom indicator that slides into place. Use the `label-sm` typography for tab headers.

### Timelines
Vertical lines should be 1px wide, colored #334155. Significant milestones are marked by a 8px circle. The line should be dashed for "Current" or "Ongoing" roles to signify progress.

### Tech Icons
Icons should be monochrome (Secondary Blue) by default, switching to their brand color only on hover. They should be housed in 32px x 32px subtle containers for uniform alignment.

### Code Snippets
Display key architectural patterns or API designs using a dark-themed syntax highlighter within a Level 1 surface container. Use `code-block` typography for maximum clarity.