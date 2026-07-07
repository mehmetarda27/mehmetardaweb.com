---
name: Arda Studio Core
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a1700'
  on-tertiary-container: '#b87500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
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
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 120px
---

## Brand & Style

The design system is engineered to evoke a sense of high-end digital craftsmanship, precision, and modern authority. It targets sophisticated business owners and tech startups looking for a premium web presence. 

The aesthetic identity is a fusion of **Corporate Modernism** and **Glassmorphism**. It relies on deep tonal depth, expansive whitespace, and meticulous typographic hierarchy. The emotional response is one of trust and "engineered beauty"—where every pixel feels intentional and every interaction feels fluid. Visual interest is generated through the interplay of solid, dark surfaces and translucent, light-refracting overlays.

## Colors

The palette is anchored by **Deep Midnight Blue (#0F172A)**, used for primary surfaces and high-contrast text to establish a premium, grounded foundation. **Electric Blue (#3B82F6)** serves as the primary action color, providing a vibrant, tech-forward energy. **Gold (#F59E0B)** is used sparingly for high-value accents, badges, and expertise markers.

The background logic utilizes a "Layered White" approach:
- **Base:** Pure White (#FFFFFF) for maximum clarity.
- **Surface:** Slate-50 (#F8FAFC) for section differentiation.
- **Translucent:** White at 70% opacity with a 20px backdrop blur for glassmorphic cards.

## Typography

This design system employs a high-contrast typographic scale. **Montserrat** is reserved for headlines to project strength and architectural stability. **Inter** is used for all functional and body text to ensure maximum legibility and a systematic feel.

- **Headlines:** Use tight letter-spacing on larger sizes to maintain a sleek, "locked-in" look.
- **Body Text:** Use Slate-700 (#334155) instead of pure black to maintain a softer, premium reading experience.
- **Labels:** Always use semi-bold weight and slight tracking for clear categorization.

## Layout & Spacing

The layout follows a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The hallmark of this design system is "Generous Breathing Room." 

- **Vertical Rhythm:** Sections are separated by large 120px paddings to emphasize exclusivity and focus.
- **Grid Alignment:** Elements should be aligned to the grid, but decorative background glass elements can bleed off-canvas to create a sense of depth.
- **Desktop:** 1280px max-width container with 32px gutters.
- **Mobile:** Full-width with 20px side margins and vertical stacking for all grid components.

## Elevation & Depth

Hierarchy is achieved through **Ambient Shadows** and **Tonal Layering**. 

1.  **Level 0 (Base):** Flat White or light Slate background.
2.  **Level 1 (Subtle):** Cards with a 1px border in Slate-200 and no shadow.
3.  **Level 2 (Elevated):** Glassmorphic cards with a 70% white fill, 20px blur, and a soft, multi-layered shadow: `0 10px 15px -3px rgba(15, 23, 42, 0.05), 0 4px 6px -4px rgba(15, 23, 42, 0.05)`.
4.  **Level 3 (Interactive):** On hover, elevated elements should lift further using a more pronounced, diffused shadow with a hint of the Primary color in the tint.

Avoid harsh black shadows; all depth should feel like light passing through semi-opaque materials.

## Shapes

The shape language is defined by **Soft Geometric Precision**. 

- **Standard Radius:** 0.5rem (8px) for small components like inputs and tags.
- **Container Radius:** 1.5rem (24px) for cards and sections—this "2xl" look is a signature of the system.
- **Interactive Elements:** Buttons utilize a slightly more aggressive 0.75rem (12px) radius to distinguish them from static containers.

## Components

### Buttons
- **Primary:** Deep Midnight Blue background, white text. No border. On hover, shifts to Electric Blue.
- **Secondary:** Transparent background, Electric Blue border (2px), Electric Blue text.
- **Ghost:** Transparent background, Slate-600 text, subtle background gray fill on hover.

### Cards
- Standard cards use the **Level 2 Elevation** (Glassmorphism). 
- Cards feature a 1.5rem corner radius.
- Imagery within cards should have a subtle 0.5px inner "sheen" border to simulate glass edges.

### Input Fields
- Soft gray fill (Slate-50) with a 1px border (Slate-200).
- Focus state: Border color changes to Electric Blue with a subtle 3px outer glow (Primary Blue at 10% opacity).

### Chips & Badges
- Small, uppercase labels with increased letter spacing.
- Backgrounds are light tints of the accent colors (e.g., Electric Blue at 10% opacity).

### Lists
- Icon-led lists using custom-drawn, thin-stroke (1.5pt) SVG icons in Electric Blue or Gold.
- Generous 16px vertical spacing between list items.

### Special Component: Portfolio Mosaic
- A non-uniform grid for showcasing agency work, using varying card heights and subtle parallax effects on scroll to emphasize "premium digital" motion.