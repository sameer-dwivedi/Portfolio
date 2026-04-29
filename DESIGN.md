---
name: High-Tech Portfolio System
colors:
  surface: '#16111b'
  surface-dim: '#16111b'
  surface-bright: '#3d3741'
  surface-container-lowest: '#110c15'
  surface-container-low: '#1f1a23'
  surface-container: '#231e27'
  surface-container-high: '#2e2832'
  surface-container-highest: '#39323d'
  on-surface: '#eadfed'
  on-surface-variant: '#cfc2d6'
  inverse-surface: '#eadfed'
  inverse-on-surface: '#342e38'
  outline: '#988d9f'
  outline-variant: '#4d4354'
  surface-tint: '#ddb7ff'
  primary: '#ddb7ff'
  on-primary: '#490080'
  primary-container: '#b76dff'
  on-primary-container: '#400071'
  inverse-primary: '#842bd2'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#b7c8e1'
  on-tertiary: '#213145'
  tertiary-container: '#8292aa'
  on-tertiary-container: '#1a2b3e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#ddb7ff'
  on-primary-fixed: '#2c0051'
  on-primary-fixed-variant: '#6900b3'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#16111b'
  on-background: '#eadfed'
  surface-variant: '#39323d'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Plus Jakarta Sans
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  section-gap: 120px
---

## Brand & Style

The design system is engineered to project a persona of technical mastery, precision, and forward-thinking innovation. It caters to a high-tech audience, including recruiters at top-tier engineering firms and potential collaborators in the Web3 and SaaS sectors. 

The aesthetic is rooted in **Glassmorphism** and **High-Contrast Modernism**. By utilizing a "Dark Mode by Default" philosophy, the design system leverages the depth of a deep charcoal void, punctuated by luminous, neon-adjacent accents. This creates a sense of a digital cockpit or an advanced IDE. Visual interest is maintained through subtle motion, background blurs, and the strategic use of light as a material to define hierarchy and state changes.

## Colors

The color palette is built on a foundation of "Deep Space" black to maximize the luminance of the accent colors. 

- **Primary (Electric Purple):** Used for primary actions, branding elements, and active navigation states. It represents the "creative" side of the MERN stack.
- **Secondary (Cyan):** Used for technical details, code snippets, and success states. It represents logic and precision.
- **Neutrals (Slate Grays):** Utilized for borders, secondary text, and low-priority icons to ensure the interface remains sophisticated rather than overwhelming.
- **Interactive Gradients:** Frequently blend Electric Purple and Cyan to signify "Full Stack" connectivity.

## Typography

This design system utilizes **Plus Jakarta Sans** for its exceptional balance of geometric clarity and modern warmth. 

Headlines use tight tracking and heavy weights to create high-impact visual anchors against the dark background. Body text maintains a comfortable line height (1.6) to ensure legibility during long-form project descriptions. Special labels and tags use an uppercase, tracked-out style to mimic technical metadata or terminal output. Use high-contrast white (#FFFFFF) for primary headings and slate-400 (#94A3B8) for secondary body text to maintain a clear reading hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop to maintain a cinematic, curated feel, transitioning to a fluid model for mobile devices. 

- **Grid:** A 12-column grid is used for desktop layouts, with generous gutters to allow the glassmorphic elements "room to breathe."
- **Rhythm:** Spacing follows an 8px base unit. Section-to-section transitions are intentionally large (120px+) to emphasize distinct project phases or skills.
- **Safe Zones:** Content is centered with significant horizontal margins to keep the eye focused on the high-tech core elements.

## Elevation & Depth

In this design system, depth is communicated through **translucency and luminosity** rather than traditional shadows.

1.  **The Base Layer:** The #0A0A0A background acts as the canvas.
2.  **The Glass Layer:** Surfaces use a semi-transparent fill (e.g., `rgba(255, 255, 255, 0.03)`) with a `backdrop-filter: blur(12px)`.
3.  **The Stroke Layer:** A 1px border with a subtle gradient (Top-Left: 10% white, Bottom-Right: 0% white) defines the edges of glass containers.
4.  **The Glow:** Active components emit a soft, localized outer glow (Box-shadow) using the primary or secondary accent colors at low opacity (20%) to simulate light emission.

## Shapes

The shape language is consistently **Rounded**, striking a balance between "industrial" and "user-friendly." 

- **Primary Surfaces:** Use a 1rem (16px) corner radius for cards and major containers.
- **Interactive Elements:** Buttons and tags use a 0.5rem (8px) radius to feel precise and clickable.
- **Accents:** Use circular shapes exclusively for avatars or decorative background orbs that provide the underlying color for glassmorphic blurs.

## Components

### Buttons
Primary buttons feature a vibrant gradient fill (Purple to Cyan) with white text. Secondary buttons use the "Glass" style: a transparent background with a 1px white border and a hover effect that increases the backdrop-blur intensity.

### Cards (Project/Skill)
Cards are the primary showcase for glassmorphism. They must include a subtle internal glow on hover. Content inside should be strictly aligned to the grid, using Cyan for metadata (e.g., "Tech Stack") and Purple for titles.

### Inputs & Fields
Input fields are dark with a 1px slate-800 border. Upon focus, the border transitions to a Cyan gradient and triggers a 4px soft outer glow.

### Chips & Tags
Used for tech stack labels. These are small, low-opacity Cyan or Purple containers with high-contrast text and a 0.25rem radius.

### Interactive Transitions
All hover states should use a `cubic-bezier(0.4, 0, 0.2, 1)` timing function for a "snappy yet smooth" feel. Page transitions should involve subtle Y-axis translations and opacity fades to reinforce the feeling of depth.