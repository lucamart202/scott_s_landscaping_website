---
name: The Design System
colors:
  surface: '#fcf9f2'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f2'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee7'
  surface-container-high: '#ebe8e1'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#424841'
  inverse-surface: '#31312c'
  inverse-on-surface: '#f3f0ea'
  outline: '#737970'
  outline-variant: '#c2c8bf'
  surface-tint: '#476648'
  primary: '#17331a'
  on-primary: '#ffffff'
  primary-container: '#2d4a2f'
  on-primary-container: '#98b996'
  inverse-primary: '#aecfac'
  secondary: '#8a5019'
  on-secondary: '#ffffff'
  secondary-container: '#fdb071'
  on-secondary-container: '#774109'
  tertiary: '#053511'
  on-tertiary: '#ffffff'
  tertiary-container: '#1f4c25'
  on-tertiary-container: '#8bbc8b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c9ecc6'
  primary-fixed-dim: '#aecfac'
  on-primary-fixed: '#04210a'
  on-primary-fixed-variant: '#304d32'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6d3901'
  tertiary-fixed: '#bcf0ba'
  tertiary-fixed-dim: '#a1d3a0'
  on-tertiary-fixed: '#002107'
  on-tertiary-fixed-variant: '#235029'
  background: '#fcf9f2'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  h1:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  h2:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.3'
  h3:
    fontFamily: Noto Serif
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.4'
  body-md:
    fontFamily: Manrope
    fontSize: 15px
    fontWeight: '400'
    lineHeight: '1.7'
  body-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.6'
  label:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  section-v-padding-sm: 80px
  section-v-padding-lg: 120px
  gutter: 24px
  margin-edge: 40px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is rooted in the concept of "Artisanal Precision." It targets high-end residential and commercial clients in Louisville who value craftsmanship and local heritage. The brand personality is professional yet warm, evoking the feeling of a well-tended estate.

To achieve this, the system utilizes a **Minimalist** style with a focus on high-quality typography and a nature-inspired palette. By avoiding shadows and gradients, the UI maintains a flat, contemporary aesthetic that allows photography of lush landscapes to take center stage. The emotional response should be one of tranquility, trust, and structural integrity.

## Colors

This design system uses a sophisticated, earth-toned palette to reflect the landscaping industry. 

- **Primary Canvas:** Use White (#FFFFFF) as the standard background. For section differentiation, use Mist (#F2F7ED) or Linen (#F8F6F1) to provide subtle visual breaks without introducing high contrast.
- **Action & Hierarchy:** Forest (#2D4A2F) is reserved for primary actions and authoritative headlines. Bark (#A0622A) serves as a warm alternative for secondary calls to action, providing a "soil and wood" counterpoint to the greenery.
- **Accents:** Moss and Sage are used for interactive states and supportive icons. Fern and Sand are utilized for container backgrounds to group related content softly.
- **Text:** Charcoal (#2A2A26) is used for all body copy to ensure readability while appearing softer and more organic than pure black.

## Typography

The typography strategy pairs a traditional serif with a modern, clean sans-serif to bridge the gap between "artisanal" and "professional."

- **Headlines:** Noto Serif (as a high-quality alternative to Playfair) conveys authority and timelessness. Headlines should always use the Forest (#2D4A2F) color.
- **Body:** Manrope provides a contemporary, highly readable experience. The generous 1.7 line-height is critical to maintaining the "spacious" feel requested in the brand brief.
- **Metadata:** All labels, tags, and small utility text must be set in uppercase Manrope with increased letter-spacing to create an architectural, organized look.

## Layout & Spacing

The layout utilizes a **Fixed Grid** system to ensure a premium, editorial feel that doesn't feel overly "stretched" on ultra-wide monitors.

- **Vertical Rhythm:** Sections are separated by significant vertical padding (80px to 120px). This "white space" is intentional; it allows the content to breathe and suggests a premium service where details are not rushed.
- **Content Width:** Main content is capped at 1200px.
- **Grid:** A 12-column grid is used for desktop layouts, with 24px gutters to keep elements distinct and organized.

## Elevation & Depth

This design system employs **Low-Contrast Outlines** and **Tonal Layers** rather than shadows. To maintain the flat, handcrafted aesthetic:

- **Depth through Color:** Use background color shifts (e.g., a Sand #E8DDD0 card on a White #FFFFFF background) to indicate separate components.
- **Borders:** Use thin, 1px borders in Sage (#8FB28A) or Stone (#C49A6C) for form fields and card outlines. This creates structure without the "heaviness" of a drop shadow.
- **No Shadows:** Avoid `box-shadow` properties entirely. The hierarchy is established through spacing, scale, and color blocking.

## Shapes

The shape language is diverse but disciplined, using specific radii to denote the scale of the element:

- **Buttons:** 6px radius for a sharp, professional finish.
- **Cards & Inputs:** 8px radius for a modern, approachable feel.
- **Containers:** Large image blocks or section backgrounds use a 24px radius to soften the overall layout and mimic organic forms found in landscaping.
- **Icons:** Use linear icons with a 2px stroke weight to match the "thin border" philosophy of the header.

## Components

### Buttons
- **Primary:** Forest background, White text. No border.
- **Secondary:** Bark background, White text. No border. 
- **Outline:** Transparent background, Forest 1px border, Forest text.
- *Interaction:* On hover, the Moss color should be used for primary/outline states.

### Cards
- **Style:** Background Sand (#E8DDD0), 8px border radius, no shadow.
- **Padding:** 32px internal padding for a spacious feel.

### Form Fields
- **Style:** White background, 1px Sage border, 8px radius. 
- **Labels:** Uppercase Manrope, 12px, placed above the field.

### Header
- **Style:** Sticky position, White background, 1px Stone border on the bottom. 
- **Logo:** Set in Noto Serif Bold, Forest color.

### Footer
- **Style:** Charcoal background, Linen text for high legibility. 
- **Layout:** 4-column layout for links, contact info, and "Louisville Proud" badge.

### Additional Components
- **Project Gallery:** Large image tiles with 24px rounded corners and a Fern (#D4E6C3) caption bar at the bottom.
- **Service Tags:** Sage background with Forest text, 50% opacity background for a subtle "leafy" effect.