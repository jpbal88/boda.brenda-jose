---
name: Crimson & Gold Editorial
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#544343'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#867273'
  outline-variant: '#d9c1c1'
  surface-tint: '#93474d'
  primary: '#2a0006'
  on-primary: '#ffffff'
  primary-container: '#4a0e17'
  on-primary-container: '#ca7379'
  inverse-primary: '#ffb3b6'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#260308'
  on-tertiary: '#ffffff'
  tertiary-container: '#42161c'
  on-tertiary-container: '#bb7a7f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdada'
  primary-fixed-dim: '#ffb3b6'
  on-primary-fixed: '#3d040e'
  on-primary-fixed-variant: '#763037'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdadb'
  tertiary-fixed-dim: '#fcb3b9'
  on-tertiary-fixed: '#360d13'
  on-tertiary-fixed-variant: '#6b373c'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-hero:
    fontFamily: Great Vibes
    fontSize: 84px
    fontWeight: '400'
    lineHeight: 90px
  display-hero-mobile:
    fontFamily: Great Vibes
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 60px
  heading-uppercase:
    fontFamily: Cinzel
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.2em
  section-title:
    fontFamily: Cormorant Garamond
    fontSize: 42px
    fontWeight: '300'
    lineHeight: 48px
  body-large:
    fontFamily: Cormorant Garamond
    fontSize: 22px
    fontWeight: '400'
    lineHeight: 32px
  body-main:
    fontFamily: Cormorant Garamond
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  label-caps:
    fontFamily: Cinzel
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.15em
  button-text:
    fontFamily: Cinzel
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1100px
  section-padding-y: 120px
  mobile-margin: 24px
  gutter: 32px
  ornament-gap: 16px
---

## Brand & Style

The design system is centered on **Editorial Luxury** and **Vintage-Chic** aesthetics. It evokes a sense of timeless romance, exclusivity, and high-end sophistication. The target audience expects a premium, curated experience that mirrors a physical, high-grammage paper invitation.

The visual narrative relies on high-contrast storytelling: deep, immersive dark sections juxtaposed with airy, light editorial layouts. Key stylistic markers include:
- **Fine Hairline Borders:** 0.5pt to 1pt strokes in gold to frame content.
- **Ornamental Accents:** Subtle gold flourishes in corners and as section dividers.
- **Generous Whitespace:** Intentional breathing room to elevate the perceived value of the content.
- **Cinematic Transitions:** Vertical scrolling that feels like turning the pages of a high-fashion magazine.

## Colors

The palette is a regal combination of deep reds, metallics, and warm neutrals. 

- **Primary & Tertiary (Ruby/Burgundy):** Used for immersive hero sections, footers, and primary call-to-action backgrounds. The gradient between `#4A0E17` and `#2B050B` provides a velvet-like depth.
- **Secondary (Champagne Gold):** Reserved for accents, ornamental flourishes, and high-priority headings. When used for text on dark backgrounds, it should evoke a foil-stamped effect.
- **Neutral (Warm Cream):** The foundation for all body content and information-heavy sections. It provides a softer, more heritage feel than a stark white.
- **Functional States:** Success and information states should utilize muted versions of the gold palette to maintain the luxury aesthetic.

## Typography

This system uses a tri-font hierarchy to establish a vintage editorial rhythm:
1.  **Great Vibes (Script):** Used exclusively for names, quotes, and artistic expressions. It should never be used for functional UI or long-form text.
2.  **Cinzel (Serif Caps):** Used for labels, subheadings, and navigation elements. The heavy letter-spacing is essential to achieving a "high-fashion" look.
3.  **Cormorant Garamond (Body):** A classic, legible serif for all information. The italic weight is frequently used for quotes or secondary descriptions to add a literary touch.

Avoid using bold weights for body text; instead, use the Medium weight of Cormorant Garamond or a color shift to Gold for emphasis.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop to maintain the "invitation card" feel, while transitioning to a fluid single-column for mobile.

- **Desktop:** 12-column grid centered within a 1100px container. Large vertical gaps (120px+) between sections are mandatory to preserve the luxury feel.
- **Mobile:** Margins are increased to 24px to ensure the delicate hairline borders have enough visual clearance from the edge of the screen.
- **Rhythm:** Spacing is used to group content into "cards" or "vignettes." Each section (RSVP, Location, Gift Registry) should be treated as a distinct visual composition rather than a continuous flow of data.

## Elevation & Depth

To maintain a flat, heritage-print aesthetic, this design system avoids standard shadows. Depth is instead conveyed through:

- **Tonal Layering:** Using the Cream (`#FDFBF7`) on top of Burgundy backgrounds to create a clear "card on table" hierarchy.
- **Fine-Line Borders:** Using gold hairline strokes (0.5px - 1px) to define boundaries.
- **Opacity Layers:** Subtle 5% black overlays on images to ensure gold text remains legible.
- **Skeuomorphic Accents:** The only exception to the flat rule is the "Gold Foil" effect, which uses gradients and high-specular highlights to mimic metallic printing rather than digital elevation.

## Shapes

The shape language is primarily **Sharp** and architectural. 
- **Standard UI:** 0px to 4px (Soft) roundedness is used for buttons and cards to keep the look crisp and formal.
- **Imagery:** Large photos can use a slightly higher roundedness (up to 12px) or a pill-shape if they are being used as decorative vignettes.
- **Decorative Elements:** Diamonds and thin gold lines are the primary geometric motifs.

## Components

### Buttons
Primary buttons use a solid Gold (`#D4AF37`) or Burgundy background with uppercase Cinzel text. Secondary buttons use a "Ghost" style with a 1px gold border and no fill. All buttons feature a subtle 1px inset gold border to mimic embossed printing.

### Cards
Cards do not use shadows. They are defined by a 1px gold border and a slightly different background shade (e.g., a lighter cream than the page background). Corner flourishes should be applied to primary container cards.

### Input Fields
Inputs are minimalist: a single 1px bottom border in gold or dark burgundy. Labels are always floating or placed above in uppercase Cinzel.

### Chips & Tags
Used for "Dress Code" or "Dietary Options." These should be simple uppercase text with wide letter-spacing, framed by a delicate gold diamond or thin line.

### Ornamental Dividers
Replace standard horizontal rules with a gold diamond motif or a thin line that tapers at both ends. This reinforces the "wedding stationery" theme.