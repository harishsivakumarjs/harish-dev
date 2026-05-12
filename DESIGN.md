---
name: Developer Portfolio
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1b1c'
  on-surface-variant: '#3f4944'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#6f7a74'
  outline-variant: '#bec9c3'
  surface-tint: '#086b53'
  primary: '#005440'
  on-primary: '#ffffff'
  primary-container: '#0f6e56'
  on-primary-container: '#9aedcf'
  inverse-primary: '#84d6b9'
  secondary: '#5f5f59'
  on-secondary: '#ffffff'
  secondary-container: '#e1e0d9'
  on-secondary-container: '#63635d'
  tertiary: '#484a4a'
  on-tertiary: '#ffffff'
  tertiary-container: '#606161'
  on-tertiary-container: '#dcdddd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a0f3d4'
  primary-fixed-dim: '#84d6b9'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#00513e'
  secondary-fixed: '#e4e2dc'
  secondary-fixed-dim: '#c8c6c0'
  on-secondary-fixed: '#1b1c18'
  on-secondary-fixed-variant: '#474742'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf9f8'
  on-background: '#1b1b1c'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  headline-xl-mobile:
    fontFamily: Outfit
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 120px
---

## Brand & Style
This design system is built for a professional freelance developer who balances technical rigour with personal approachability. The aesthetic moves away from the cold, sterile "dark mode" often found in developer sites, opting instead for a "Warm Tech" approach. It utilizes an off-white foundation to feel more like high-end editorial paper, establishing immediate trust and clarity.

The style is **Corporate / Modern** but softened through the use of organic "warm" neutrals and rounded geometry. It emphasizes structure and precision—reflecting the quality of the code—while remaining welcoming to potential clients through generous whitespace and subtle tactile depth.

## Colors
The palette is rooted in a "warm-minimalist" philosophy. 
- **Primary (Deep Teal):** Used for call-to-actions, active navigation states, and highlighting key technical skills. It provides a sophisticated alternative to standard "tech blue."
- **Backgrounds:** The primary surface is #F9F8F5 (Warm Off-White). The #F1EFE8 (Light Section Bg) is reserved for alternating content sections or background containers to create subtle visual hierarchy without harsh lines.
- **Text:** #1E1E1E (Dark Charcoal) is used instead of pure black to maintain the warmth of the palette and improve long-form reading comfort.
- **Borders:** #E2E0D8 is the essential structural element, used for thin, crisp dividers that define the "structured" tone of the brand.

## Typography
The typography strategy pairings high-energy geometric headings with understated, functional body text.

**Outfit** is used for headlines to provide a modern, tech-forward "clean" look. Its geometric nature feels precise and engineered. **DM Sans** is chosen for body text and labels due to its exceptional legibility and low-contrast profile, which keeps the portfolio feeling "approachable" rather than overly aggressive.

For technical blocks or code snippets, use a monospaced font like JetBrains Mono (if available) or a system monospace at 14px to reinforce the developer identity.

## Layout & Spacing
The layout utilizes a **Fixed Grid** system centered on a 1200px max-width container. 

A 12-column grid is standard for desktop, collapsing to a single column on mobile. To maintain the "structured" tone, use consistent 24px gutters between all grid items. Vertical rhythm is driven by an 8px base unit. 

Large section gaps (120px+) are encouraged to provide the "Minimalist" breathing room that distinguishes a premium portfolio from a standard resume. On mobile, reduce side margins to 20px and section gaps to 64px to maintain momentum.

## Elevation & Depth
This design system avoids heavy shadows, instead using **Low-contrast outlines** combined with **Ambient shadows** to create a subtle "lift."

- **Cards:** Use a 1px solid border (#E2E0D8) and a very soft, diffused shadow (Offset: 0px 4px, Blur: 12px, Color: rgba(30, 30, 30, 0.05)).
- **Interactions:** On hover, cards should slightly increase their shadow spread and move -2px on the Y-axis to provide a tactile "float" feel.
- **Layers:** Use the White (#FFFFFF) surface for interactive cards or modals, while the Off-White (#F9F8F5) remains the base floor. This creates a natural hierarchy where the most important content feels closer to the user.

## Shapes
The shape language is consistently **Rounded**, using a 12px (0.75rem) radius for most UI elements. This specific radius is large enough to feel friendly and approachable but sharp enough to maintain a "professional tech" alignment.

- **Standard Elements (Buttons, Inputs):** 12px radius.
- **Large Containers (Cards, Images):** 16px (rounded-lg) for a softer outer silhouette.
- **Tags/Chips:** Fully pill-shaped (rounded-full) to distinguish them from actionable buttons.

## Components
- **Buttons:** Primary buttons use the Deep Teal (#0F6E56) background with White text. Secondary buttons use a White background with the #E2E0D8 border and Charcoal text. Use a height of 48px for standard actions.
- **Project Cards:** Should feature a White background, a 12px corner radius, and a subtle border. Place the project image at the top with a bottom-border separating it from the content.
- **Inputs:** Use the #F1EFE8 (Light section bg) as the fill for input fields to create a "sunken" feel, turning White on focus with a 2px Deep Teal border.
- **Tech Chips:** Small, pill-shaped indicators using #F1EFE8 background and Charcoal text. They should not be vibrant; their purpose is to provide scannable metadata without distracting from the primary CTA.
- **Code Blocks:** For a developer portfolio, style code snippets with a dark background (#1E1E1E) even in this light-mode design, to create a "technical window" effect.