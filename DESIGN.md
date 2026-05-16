---
name: Asaqua
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#404850'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#707881'
  outline-variant: '#bfc7d1'
  surface-tint: '#006399'
  primary: '#005d90'
  on-primary: '#ffffff'
  primary-container: '#0077b6'
  on-primary-container: '#f3f7ff'
  inverse-primary: '#94ccff'
  secondary: '#5157a6'
  on-secondary: '#ffffff'
  secondary-container: '#a4a9ff'
  on-secondary-container: '#363b89'
  tertiary: '#00626f'
  on-tertiary: '#ffffff'
  tertiary-container: '#227c8a'
  on-tertiary-container: '#e7fbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cde5ff'
  primary-fixed-dim: '#94ccff'
  on-primary-fixed: '#001d32'
  on-primary-fixed-variant: '#004b74'
  secondary-fixed: '#e0e0ff'
  secondary-fixed-dim: '#bfc2ff'
  on-secondary-fixed: '#070a61'
  on-secondary-fixed-variant: '#393e8c'
  tertiary-fixed: '#9feffe'
  tertiary-fixed-dim: '#83d3e1'
  on-tertiary-fixed: '#001f24'
  on-tertiary-fixed-variant: '#004f59'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style

The design system is centered on the concept of "Elemental Purity." It serves a high-end audience that values wellness, sustainability, and sophisticated aesthetics. The visual language evokes the sensation of a cold glass of water on a pristine surface: refreshing, clear, and essential.

The chosen style is a refined blend of **Minimalism** and **Glassmorphism**. By utilizing generous whitespace, the design system allows content to breathe, suggesting the vastness of the ocean. Glassmorphic elements—characterized by subtle background blurs and thin, light-catching strokes—mimic the condensation on a premium glass bottle and the translucency of water itself. The overall emotional response should be one of tranquility, trust, and premium refreshment.

## Colors

The palette is derived from the various states and depths of water. 

- **Primary (Crystal Blue):** A vibrant, mid-tone blue used for interactive elements and brand accents. It represents the clarity of filtered water.
- **Secondary (Deep Ocean):** A rich, dark navy used for primary typography and high-contrast components, grounding the design in luxury and heritage.
- **Tertiary (Arctic Mist):** A very pale, cyan-tinted blue used for large surface areas and background washes to prevent the "starkness" of pure white.
- **Neutral (Crisp White):** Used for the base canvas and as the "highlight" color on glassmorphic layers to create a sense of light reflection.

The default color mode is **light**, ensuring the interface feels airy and sun-drenched.

## Typography

The typography strategy emphasizes clarity and structural elegance. 

**Manrope** is utilized for all headlines. Its geometric yet slightly softened terminals provide a modern, high-end feel that remains approachable. Headlines use tight letter-spacing and substantial weight to create a rhythmic "anchor" for the eyes.

**Inter** is the workhorse for body text and labels. It was chosen for its exceptional readability at smaller scales and its neutral, systematic nature, which allows the brand’s photographic and glassmorphic elements to take center stage. 

Hierarchy is established through extreme scale: very large, bold headlines paired with generous line-heights in the body text to ensure a relaxed, premium reading experience.

## Layout & Spacing

The layout follows a **fluid grid** philosophy with exaggerated outer margins to reinforce the premium, "boutique" feel. 

- **Desktop:** A 12-column grid with a 1280px max-width. Margins are intentionally wide (64px) to create a centered, focused column of content that feels curated.
- **Mobile:** A 4-column grid with 20px margins. 
- **Spacing Rhythm:** Based on an 8px scale. Vertical "stack" spacing is aggressive (80px+ between sections) to ensure no part of the UI feels cluttered.

Elements should often "float" within the grid, using offset alignments to mimic the organic flow of water rather than a rigid, boxy corporate structure.

## Elevation & Depth

Depth is conveyed through **Glassmorphism** and soft environmental lighting rather than traditional drop shadows.

1.  **Backdrop Blurs:** Secondary surfaces (like navigation bars and modal overlays) use a `20px` to `40px` background blur with a 70% opaque white fill.
2.  **Inner Glows:** Instead of outer shadows, cards and containers feature a `1px` solid white border at 40% opacity. This acts as a "specular highlight," simulating the edge of a glass bottle catching the light.
3.  **Ambient Shadows:** Where depth is required for functional hierarchy, use extremely diffused, low-opacity shadows (e.g., Blur: 30px, Opacity: 4%) tinted with the Secondary (Deep Ocean) color to keep the shadows from looking "dirty."

## Shapes

The shape language is "Softly Organic." While water is fluid, the premium nature of the brand requires some structural definition.

A **roundedness level of 2** (0.5rem base) is applied to standard UI components like input fields and small buttons. Larger containers and cards utilize `rounded-xl` (1.5rem) to evoke the smoothed edges of river stones or custom-molded glass. 

Avoid perfectly sharp 0px corners, as they feel too industrial and aggressive for a brand centered on hydration and purity.

## Components

- **Buttons:** Primary buttons are solid Deep Ocean Blue with white text, featuring a slight "shimmer" hover effect. Secondary buttons use the glassmorphic style: a blurred background with a thin white border.
- **Cards:** Components should appear as "floating" glass panes. They feature the `rounded-xl` corner radius, a subtle white inner-border, and a very soft background tint of Arctic Mist.
- **Input Fields:** Minimalist design. Use a simple bottom border (2px) in Crystal Blue when focused, with the background being a very faint version of the tertiary color.
- **Chips & Tags:** Pill-shaped (rounded-full) with a light Crystal Blue fill and Deep Ocean text. These should look like small, smooth pebbles.
- **Progress Indicators:** Use fluid, wave-like animations for loading states or scroll indicators to reinforce the water theme.
- **Lists:** Clean, high-contrast rows separated by 1px "water-line" dividers in a very faint blue-grey.