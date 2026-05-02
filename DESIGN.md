---
name: Modern African Minimalism
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1b1b1b'
  on-surface-variant: '#414943'
  inverse-surface: '#303030'
  inverse-on-surface: '#f1f1f1'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3b6751'
  primary: '#001b0f'
  on-primary: '#ffffff'
  primary-container: '#013220'
  on-primary-container: '#6f9c84'
  inverse-primary: '#a2d1b7'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#161709'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a2c1c'
  on-tertiary-container: '#92937e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bdedd2'
  primary-fixed-dim: '#a2d1b7'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#234f3b'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e4e4cc'
  tertiary-fixed-dim: '#c8c8b0'
  on-tertiary-fixed: '#1b1d0e'
  on-tertiary-fixed-variant: '#474836'
  background: '#f9f9f9'
  on-background: '#1b1b1b'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

This design system is built upon the concept of "Modern African Minimalism," a style that fuses the warmth and earthiness of Kenyan heritage with the clean, disciplined lines of contemporary high-end design. The brand personality is professional yet deeply inviting, positioned as a premium service for clients who value both sophistication and a sense of "home."

The aesthetic draws from **Minimalism** for its layout and structural clarity, but integrates **Tactile** elements to avoid the sterility often associated with modernism. It evokes a "slow luxury" feel—intentional, curated, and timeless. The target audience is the discerning Kenyan professional looking for an interior that reflects their success through understated elegance rather than loud ostentation.

## Colors

The palette is anchored in a trio of warm neutrals that provide a soft, luminous foundation. **Warm White** serves as the primary canvas, while **Beige** and **Cream** are used to create subtle depth and "zones" within the UI without relying on heavy lines.

**Deep Green** acts as the primary brand color, representing the lush landscapes of Kenya and providing a sophisticated, grounding anchor for navigation and call-to-action elements. **Gold** is used sparingly as a "high-light" accent for interactive states, borders, or iconography to signify luxury. **Black** is reserved for high-contrast typography and structural elements, ensuring the design remains sharp and professional.

## Typography

This design system utilizes a classic serif/sans-serif pairing to communicate both heritage and modernity. **Noto Serif** is used for headlines; its timeless proportions and elegant strokes suggest an editorial, high-end magazine quality. For the display styles, a slight negative letter-spacing is applied to create a tighter, more "designed" appearance.

**Manrope** provides a functional, highly readable counterpoint for body copy and UI labels. Its geometric yet warm construction maintains the contemporary minimalist vibe. Use `label-caps` for small navigational elements or category tags to introduce a structured, architectural feel to the layout.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop to maintain a curated, gallery-like feel. A 12-column grid is employed with generous 32px gutters to ensure breathable whitespace between content modules. 

Rhythm is established through a strict 8px baseline. Large vertical gaps (120px+) between sections are encouraged to give each project or service room to breathe, reinforcing the "luxurious" and "unhurried" brand promise. Content should often be centered or offset asymmetrically to mimic the organic yet planned feel of interior design.

## Elevation & Depth

Hierarchy is achieved primarily through **Tonal Layers** rather than heavy shadows. Different surfaces are distinguished by shifting between Warm White, Cream, and Beige backgrounds.

When depth is necessary (e.g., for hovering over portfolio cards), use **Ambient Shadows**. These shadows should be extremely diffused, using a low-opacity Deep Green or Gold tint (#013220 at 5-8% opacity) instead of pure gray. This creates a "warm glow" effect that feels like natural sunlight hitting an object, reinforcing the homey aesthetic. **Low-contrast outlines** in Gold or Beige can be used to define form without breaking the minimalist flow.

## Shapes

The shape language is **Soft (0.25rem)**, reflecting an architectural sensibility. While sharp corners can feel too aggressive and fully rounded "pills" feel too casual/tech-focused, the subtle softening of corners suggests craftsmanship and comfort. 

Large-scale images (portfolio shots) should maintain sharp corners to feel like framed art, while interactive components like buttons, input fields, and tags utilize the soft corner radius to invite interaction.

## Components

### Buttons
Primary buttons use a solid Deep Green background with Warm White text. They should be wide with generous internal padding. Secondary buttons use a "Ghost" style with a 1px Gold border and Gold text.

### Cards
Portfolio cards are the centerpiece. They should be borderless with high-quality imagery extending to the edges. Text overlays should use Noto Serif for titles. Use the subtle ambient shadow on hover to "lift" the card toward the user.

### Input Fields
Inputs should be minimalist: a 1px bottom border in Deep Green or Beige, rather than a full box, creates an elegant, high-end stationery feel. Labels use the `label-caps` style for clarity.

### Chips & Tags
Used for "Style Categories" (e.g., "Mid-Century," "Swahili Modern"). These should have a Cream background and Deep Green text, using the soft corner radius defined in the Shapes section.

### Navigation
The navigation bar should be sticky and utilize a semi-transparent Warm White backdrop blur (Glassmorphism) to maintain context as the user scrolls through rich imagery. Links should have a subtle Gold underline on hover.