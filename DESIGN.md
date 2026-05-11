---
name: Velocity Finance
colors:
  surface: '#0c141b'
  surface-dim: '#0c141b'
  surface-bright: '#313a42'
  surface-container-lowest: '#070f15'
  surface-container-low: '#141d23'
  surface-container: '#182127'
  surface-container-high: '#222b32'
  surface-container-highest: '#2d363d'
  on-surface: '#dbe3ed'
  on-surface-variant: '#c6c5cf'
  inverse-surface: '#dbe3ed'
  inverse-on-surface: '#293139'
  outline: '#909099'
  outline-variant: '#46464e'
  surface-tint: '#bcc4f1'
  primary: '#bcc4f1'
  on-primary: '#262e52'
  primary-container: '#0b1437'
  on-primary-container: '#767ea7'
  inverse-primary: '#545c83'
  secondary: '#5edac2'
  on-secondary: '#00382f'
  secondary-container: '#03a38d'
  on-secondary-container: '#003028'
  tertiary: '#bbc4f4'
  on-tertiary: '#242e55'
  tertiary-container: '#09143a'
  on-tertiary-container: '#757faa'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#bcc4f1'
  on-primary-fixed: '#10193c'
  on-primary-fixed-variant: '#3d456a'
  secondary-fixed: '#7df7de'
  secondary-fixed-dim: '#5edac2'
  on-secondary-fixed: '#00201b'
  on-secondary-fixed-variant: '#005045'
  tertiary-fixed: '#dde1ff'
  tertiary-fixed-dim: '#bbc4f4'
  on-tertiary-fixed: '#0e193e'
  on-tertiary-fixed-variant: '#3b456c'
  background: '#0c141b'
  on-background: '#dbe3ed'
  surface-variant: '#2d363d'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
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
  margin: 40px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style
The brand "Start" positions itself at the intersection of institutional stability and the kinetic energy of "finanza alternativa" (alternative finance). The design system targets a sophisticated demographic of investors and tech-forward entrepreneurs who value clarity, speed, and precision. 

The visual style is **Corporate Modern with Glassmorphism accents**. It utilizes high-contrast surfaces to evoke a premium feel, while the "Play" motif from the logo is translated into dynamic UI elements that imply forward motion. Expect expansive whitespace, hyper-sharp typography, and layered depth that feels like a digital trading floor of the future. The hero sections must feature subtle, mathematical particles or low-opacity geometric wireframes to reinforce the "tech" side of the financial equation.

## Colors
The palette is anchored in **Night Blue (#0B1437)**, providing a deep, authoritative foundation that replaces standard black. This is contrasted with **Teal Green (#3DBFA8)**, used strategically for "action" states, success indicators, and growth metrics, mirroring the logo's core element.

**Dark Grey-Blue (#1B254B)** serves as the "Surface" color, creating subtle separation from the primary background. Text primarily uses **White** for high-impact headlines and **Cool Grey (#AEB7C0)** for secondary body copy to maintain a comfortable reading hierarchy in a dark-mode environment.

## Typography
This design system utilizes **Inter** for its systematic, tech-centric feel. Headlines are intentionally heavy (Bold to Extra-Bold) with tight letter-spacing to evoke a sense of "growth" and "movement," similar to financial ticker displays.

To maintain a high-end editorial feel, use **Display XL** for hero statements, ensuring the contrast between the Night Blue background and White text is crisp. Labels and small data points should use the **Label-Bold** style with increased tracking (letter spacing) to ensure legibility on dark surfaces.

## Layout & Spacing
The layout follows a **12-column fixed grid** for desktop, centered within a maximum width of 1280px to maintain control over line lengths and visual density. The rhythm is based on an **8px base unit**.

Sections should feel airy and expansive—use **stack-lg** (64px) for vertical padding between major content blocks. Information density in dashboards should be "Comfortable" rather than "Compact," allowing financial data room to breathe through generous gutters (24px).

## Elevation & Depth
Depth is created through **Tonal Layering** and **Glassmorphism**. Rather than traditional heavy shadows, this design system uses:
1. **Base Layer:** Night Blue (#0B1437).
2. **Elevated Cards:** Tertiary Blue (#1B254B) with a subtle 1px border of 10% White.
3. **Overlays:** Glassmorphic panels with a 20px backdrop blur and 5% white fill, creating a "frosted" effect that feels technical and premium.
4. **Soft Glows:** Occasionally, a faint Teal (#3DBFA8) outer glow (blur: 40px, opacity: 15%) is used behind primary call-to-action cards to signify innovation and "energy."

## Shapes
The shape language balances "corporate" and "dynamic." UI elements utilize **Rounded** settings (8px/0.5rem) to soften the technical edge of the dark theme. 

The triangle "Play" icon from the logo is a recurring motif—use it as a directional indicator in buttons or as a decorative element in background geometries. Containers and cards should never be sharp, but they should also avoid the "bubble" look of pill-shapes, maintaining a professional architectural structure.

## Components
- **Buttons:** Primary buttons are solid Teal Green (#3DBFA8) with White text, using the "Play" triangle as a trailing icon. Secondary buttons use the Night Blue background with a 1px Teal border.
- **Input Fields:** Dark backgrounds (#0B1437) with a subtle bottom border or 1px ghost border (#1B254B). Focus state shifts the border to Teal.
- **Cards:** Use the Tonal Layering approach. Cards should have no shadow but a distinct 1px border that is slightly lighter than the card background itself to define the edges.
- **Chips/Badges:** Small, high-contrast pills. For "Growth" metrics, use Teal text on a 10% Teal background opacity.
- **Data Visualizations:** Charts should use Teal Green for primary data lines, with a gradient fill fading into the Night Blue background. Grid lines in charts must be very low-contrast (5% White).
- **Progress Indicators:** Linear, thin bars using the Teal Green accent.