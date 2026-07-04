---
name: Century Ink Design System
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#f3ca50'
  on-tertiary: '#3d2f00'
  tertiary-container: '#d5af37'
  on-tertiary-container: '#564300'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#ffe08b'
  tertiary-fixed-dim: '#eac249'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#584400'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg-mobile:
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
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
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
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style
The design system for this product is rooted in a **Sophisticated Dark Minimalist** aesthetic, tailored for a high-end tattoo studio where the skin is the canvas and the art is the focus. The brand personality balances the raw edge of tattoo culture with the refined precision of a luxury atelier. 

The visual language uses high-contrast elements and generous whitespace (or "darkspace") to ensure that portfolio photography is the undisputed centerpiece. By utilizing a dark-mode-first approach, we evoke a sense of intimacy and focus, mirroring the focused environment of a professional studio session. The emotional response should be one of absolute trust in the artist’s skill and an appreciation for the premium nature of the craft.

## Colors
The palette is centered on a "Midnight and Metallic" theme. 

- **Primary (#D4AF37):** A rich, classic gold used sparingly for calls to action, active states, and brand signatures. It signifies the "Gold Standard" of craftsmanship.
- **Secondary (#1A1A1A):** A slightly lifted charcoal used for surface containers, cards, and section differentiation to provide depth against the pure black.
- **Accent (#C5A028):** A deeper brass used for hover states and subtle gradients to add a tactile, metallic dimension.
- **Base (#121212 & #000000):** Deep charcoal and absolute black are used for the background to create a "void" effect that makes vibrant tattoo photography pop.
- **Typography Colors:** Use `High-Emphasis White (#FFFFFF)` for headlines and `Medium-Emphasis Grey (#A0A0A0)` for body text to maintain hierarchy and reduce eye strain.

## Typography
The typography system uses a pairing of **Montserrat** for impact and **Inter** for utility. 

**Montserrat** is the voice of the brand—bold, geometric, and confident. Use it for all headlines and large display quotes. **Inter** provides a clean, neutral balance for body copy, ensuring that technical information (aftercare instructions, pricing, bios) is effortlessly readable. 

**JetBrains Mono** is introduced as a secondary label font for metadata, such as artist specialties, appointment times, or technical specs. This monospaced touch adds a "technical precision" feel, suggesting the clinical hygiene and exactness required in professional tattooing.

## Layout & Spacing
This design system utilizes a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile. 

The layout philosophy emphasizes "Editorial Breathing Room." Large sections of the portfolio should span the full width or 10/12 columns to maximize the visual weight of the art. 

**Spacing Principles:**
- Use an 8px base grid.
- **Negative Space:** Use generous vertical padding (80px - 120px) between homepage sections to create a premium, gallery-like experience.
- **Alignment:** Headlines should be left-aligned for a modern, architectural feel, while decorative "gold" accents can be used as vertical rules to guide the eye.

## Elevation & Depth
In this dark-themed system, we avoid heavy drop shadows in favor of **Tonal Elevation** and **Inner Glows**.

- **Surfaces:** Depth is created by lightening the background hex. The further "forward" an element is (like a modal or a card), the lighter its background (#121212 base -> #1A1A1A surface -> #242424 overlay).
- **Subtle Glow:** High-priority components like active booking buttons may feature a very soft, low-opacity gold outer glow (`rgba(212, 175, 55, 0.15)`) to simulate a metallic reflection.
- **Dividers:** Use 1px solid lines in #333333 for subtle separation. Avoid high-contrast white borders.

## Shapes
The shape language is **Soft (0.25rem / 4px)**. 

While the brand is modern, sharp 90-degree corners can feel too aggressive and "corporate." A very subtle rounding (4px) on buttons, images, and input fields softens the UI just enough to feel approachable and "human," reflecting the personal, skin-to-skin nature of the service. 

**Image Treatment:** Large portfolio images should maintain a consistent aspect ratio (e.g., 4:5 for portraits) with 4px corner radii to maintain a clean, organized gallery look.

## Components

### Buttons
- **Primary:** Solid Gold (#D4AF37) background with Black (#000000) Montserrat Bold text. Use for "Book Now."
- **Secondary:** Ghost style. 1px Gold border with Gold text. High-contrast hover with a solid Gold fill.
- **Tertiary:** Text-only with a JetBrains Mono label and a 2px Gold underline that expands on hover.

### Image Galleries
- **Masonry Grid:** Used for the main portfolio to accommodate various tattoo shapes (tall back pieces vs. small wrist pieces).
- **Hover State:** On hover, images should slightly scale up (1.05x) and show a subtle gold overlay with the artist's name and category.

### Booking Forms
- **Input Fields:** Dark background (#1A1A1A) with 1px dark grey borders. When focused, the border transitions to Gold. 
- **Labels:** Always use JetBrains Mono for form labels to maintain the "technical/studio" aesthetic.

### Cards
- **Artist Profiles:** Large, high-contrast imagery at the top, followed by a Secondary surface container for the bio. Use the gold accent color for social media icons and "Years of Experience" badges.

### Floating Action
- A persistent "Quick Book" floating button should be present on mobile, styled as a solid Gold circle with a black "Plus" or "Calendar" icon.