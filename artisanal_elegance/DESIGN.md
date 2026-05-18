---
name: Artisanal Elegance
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#444840'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#75786f'
  outline-variant: '#c5c8bd'
  surface-tint: '#546349'
  primary: '#28351f'
  on-primary: '#ffffff'
  primary-container: '#3e4c34'
  on-primary-container: '#acbc9d'
  inverse-primary: '#bbccac'
  secondary: '#725a38'
  on-secondary: '#ffffff'
  secondary-container: '#fcdaaf'
  on-secondary-container: '#775e3c'
  tertiary: '#363126'
  on-tertiary: '#ffffff'
  tertiary-container: '#4e473b'
  on-tertiary-container: '#bfb6a6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e8c7'
  primary-fixed-dim: '#bbccac'
  on-primary-fixed: '#121f0b'
  on-primary-fixed-variant: '#3d4b33'
  secondary-fixed: '#ffddb2'
  secondary-fixed-dim: '#e1c298'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#594323'
  tertiary-fixed: '#ece1d1'
  tertiary-fixed-dim: '#cfc5b5'
  on-tertiary-fixed: '#201b11'
  on-tertiary-fixed-variant: '#4c463a'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  headline-xl:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 80px
  content-gap: 32px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: auto
  max-width: 1200px
---

## Brand & Style

The design system is rooted in a "Sophisticated Organic" aesthetic. It evokes a sense of high-end craftsmanship, tactile quality, and timeless hospitality. The target audience values intentionality, heritage, and the beauty of natural materials.

The visual style leans heavily into **Minimalism** with **Tactile** accents. This means using generous whitespace and clean layouts while incorporating textures that mimic premium stationery or natural linens. The interface should feel like a high-end editorial magazine—unhurried, professional, and curated.

## Colors

The palette is anchored by a deep, earthy moss green that serves as the primary brand signature. This is balanced by a range of warm, light neutrals that provide a soft, welcoming backdrop.

- **Primary (Deep Moss):** Used for key branding elements, primary buttons, and high-level headers.
- **Secondary (Muted Gold/Tan):** Used for subtle accents, icons, or secondary interactive elements to suggest warmth and wood-like tones.
- **Tertiary (Warm Beige):** Used for surface-level containers and dividers to maintain a soft contrast against the cream background.
- **Neutral (Warm Cream):** The foundation of the design system, used for global backgrounds to avoid the clinical feel of pure white.
- **Text:** Deep charcoal (#2A2A2A) is used instead of pure black to maintain a softer, more organic reading experience.

## Typography

The typography strategy relies on the contrast between the authoritative, literary feel of **Libre Caslon Text** and the modern, approachable clarity of **Plus Jakarta Sans**.

Headlines should always utilize the serif typeface to reinforce the artisanal brand identity. Large display text benefits from a slight negative letter spacing to feel more "locked-in" and editorial. Body text uses the sans-serif for high legibility, especially on smaller screens. Labels and small metadata utilize uppercase styling with generous tracking to create a "gallery label" effect.

## Layout & Spacing

This design system employs a **fixed grid** model for desktop to maintain the feel of a curated catalog, transitioning to a fluid model for mobile devices.

The layout uses a 12-column grid on desktop with a maximum width of 1200px. Spacing is intentionally generous (the "breathable" luxury approach). Vertical rhythm is established using 8px increments, with larger 80px gaps between major sections to allow the eye to rest and focus on one artisanal element at a time. On mobile, margins are reduced to 20px, and content primarily stacks in a single column to maintain focus on high-quality imagery.

## Elevation & Depth

Hierarchy in this design system is achieved through **Tonal Layers** rather than heavy shadows. 

- **Surface Levels:** The base layer is the Warm Cream neutral. Raised elements like cards or modals use the Tertiary Beige or white to create a subtle "paper-on-table" depth.
- **Ambient Shadows:** When shadows are necessary for functional clarity (like a dropdown or a floating action button), they must be extremely diffused with low opacity (5-8%) and a slight tint of the primary green to ensure they feel organic rather than digital.
- **Low-Contrast Outlines:** Subtle 1px borders in a slightly darker tan are preferred over shadows to define boundaries without adding visual "weight."

## Shapes

The shape language is **Soft**. To reflect the architectural and furniture-based nature of the brand, we avoid overly "bubbly" or circular buttons.

Standard UI elements like buttons and input fields use a 4px (0.25rem) radius. This provides a gentle touch that feels hand-finished while maintaining the structural integrity of a professional design. Larger components like images or content cards may scale up to an 8px radius, but should never reach "pill" shapes, as that contradicts the sophisticated serif-led aesthetic.

## Components

### Buttons
Primary buttons are solid Deep Moss with Warm Cream text. They should feel substantial. Secondary buttons use the Muted Gold as an outline or as a text link with a subtle underline to denote interactivity.

### Cards
Cards should be used sparingly to highlight specific services or furniture pieces. They feature a very light Tertiary Beige background and 0.5px subtle borders. Imagery within cards should have a consistent aspect ratio (usually 4:5 or 3:2) to mimic photography prints.

### Input Fields
Inputs are minimalist, utilizing a bottom-border only or a very light tonal background. Focus states shift the border color to the primary Deep Moss.

### Lists & Navigation
Navigation items use the Label-MD style (uppercase, tracked out) to feel like a high-end menu. Lists should have generous vertical padding (16px+) to ensure the "artisanal" feel isn't lost in a crowded interface.

### Chips & Tags
Used for categories like "Furniture," "Events," or "Decor." These should be styled as "pill-lite"—rounded corners but with a primary green text on a light beige background, avoiding heavy fills.