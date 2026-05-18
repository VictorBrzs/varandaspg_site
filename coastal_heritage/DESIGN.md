---
name: Coastal Heritage
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
  on-surface-variant: '#45483e'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#76786d'
  outline-variant: '#c6c8ba'
  surface-tint: '#546439'
  primary: '#35431c'
  on-primary: '#ffffff'
  primary-container: '#4c5b31'
  on-primary-container: '#c0d29d'
  inverse-primary: '#bccd99'
  secondary: '#6b5d41'
  on-secondary: '#ffffff'
  secondary-container: '#f1ddba'
  on-secondary-container: '#6f6145'
  tertiary: '#3b4133'
  on-tertiary: '#ffffff'
  tertiary-container: '#525849'
  on-tertiary-container: '#c8cebb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e9b3'
  primary-fixed-dim: '#bccd99'
  on-primary-fixed: '#131f00'
  on-primary-fixed-variant: '#3d4c23'
  secondary-fixed: '#f4e0bd'
  secondary-fixed-dim: '#d7c4a2'
  on-secondary-fixed: '#241a05'
  on-secondary-fixed-variant: '#52452b'
  tertiary-fixed: '#e0e5d2'
  tertiary-fixed-dim: '#c4c9b6'
  on-tertiary-fixed: '#181d12'
  on-tertiary-fixed-variant: '#43493b'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
---

## Brand & Style

This design system is crafted for a premium dining experience that bridges the gap between traditional "Caiçara" roots and international sophistication. The brand personality is **refined, organic, and welcoming**, reflecting the upscale yet relaxed atmosphere of Praia Grande’s coastline.

The visual style is a blend of **Modern Minimalism** and **Tactile Organicism**. It prioritizes high-quality photography and generous whitespace to allow the culinary artistry to stand out. Key brand traits include:
- **Sophistication:** Subtle, high-contrast serif typography and a muted, nature-inspired palette.
- **Warmth:** Use of soft beige backgrounds instead of harsh whites to create a more inviting, high-end feel.
- **Nature-Centric:** Integration of delicate botanical line art and leaf motifs to reference the local environment.
- **Mobile-First Luxury:** A seamless, high-performance interface that maintains its elegance across all touchpoints, especially for guests making reservations on the move.

## Colors

The palette is derived from the coastal landscape—deep forest greens, sandy shores, and dark earth tones.

- **Primary (Olive Green):** Used for primary actions, success states, and brand-identifying motifs. It represents freshness and the local flora.
- **Secondary (Warm Sand):** Used for accents, secondary buttons, and highlighted containers. It adds a touch of warmth and luxury.
- **Neutral (Parchment):** The primary background color. It is softer than pure white, reducing eye strain and providing a premium "menu" feel.
- **Surface (Deep Charcoal):** Reserved for footers, dark-mode sections, or high-contrast typography to ensure legibility and a grounded feel.

Maintain a high contrast ratio for all text elements against the parchment background to ensure accessibility.

## Typography

The typography strategy pairs a timeless serif with a modern, highly legible sans-serif.

- **Headlines:** Uses *Playfair Display*. This font conveys authority and elegance. Large display sizes should use tighter letter spacing for a modern editorial look.
- **Body Text:** Uses *Be Vietnam Pro*. It provides a clean, contemporary contrast to the serif headlines and ensures high readability for menu descriptions and long-form content.
- **Labels:** Small caps and increased letter spacing are used for navigational elements and overlines to create a hierarchy that feels organized and professional.

## Layout & Spacing

The design system utilizes a **Fluid 12-Column Grid** for desktop and a **Single-Column Stack** for mobile devices.

- **Rhythm:** An 8px base unit drives all spacing decisions. 
- **Breathing Room:** Sections are separated by significant vertical padding to emphasize the premium nature of the brand.
- **Mobile Adjustments:** Margins shift from 80px on desktop to 20px on mobile to maximize content real estate while maintaining a clear frame.
- **Containment:** For readability, text-heavy blocks (like restaurant history or "Caiçara" stories) should be constrained to a max-width of 800px regardless of screen size.

## Elevation & Depth

To maintain a sophisticated and tactile feel, this design system avoids heavy drop shadows in favor of **Tonal Layers** and **Subtle Micro-shadows**.

- **Surface Tiers:** Use slight color variations (e.g., parchment to a slightly darker sand) to indicate different content areas.
- **Floating Elements:** Cards and menus use a very soft, diffused shadow (`0px 4px 20px rgba(0,0,0,0.05)`) to appear as if they are resting lightly on the surface.
- **Interactive States:** Buttons should feel "pressed" rather than "lifted" when interacted with, reinforcing a physical, tactile connection.

## Shapes

The shape language is **Soft (Level 1)**. This provides a gentle, human touch without appearing overly "bubbly" or informal.

- **Standard Elements:** Buttons and input fields use a `4px` (0.25rem) radius.
- **Cards and Imagery:** Large image containers and feature cards use a `8px` (0.5rem) radius to feel more contemporary.
- **Decorative Elements:** Botanical icons and leaf motifs should feature organic, flowing lines to contrast against the structured grid of the layout.

## Components

### Buttons
- **Primary:** Solid Olive Green background with parchment text. High-contrast and bold.
- **Secondary:** Outlined in Sand or Olive, with a slight hover fill.
- **Text Buttons:** Used for "View More" links, accompanied by a small leaf icon or arrow.

### Cards (Menu & Features)
- Cards use a clean layout with image-top alignment. Typography inside cards should be centered for a formal "menu card" aesthetic. 
- Images should have a subtle zoom effect on hover.

### Inputs
- Form fields (Reservation system) use a clean bottom-border style or very light parchment fill to maintain an airy feel. Labels are always placed above the field in `label-md` style.

### Navigation
- A centered logo for desktop, with a simplified "Hamburger" menu for mobile. 
- The "Book a Table" call-to-action is always present as a primary button in the header.

### Botanical Icons
- Use custom line-art icons of local leaves (Guaiamu, seaweed, or native forest leaves) to serve as section dividers or bullet points.