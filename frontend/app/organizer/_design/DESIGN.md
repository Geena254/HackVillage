---
name: Kinetic Trust PWA
colors:
  surface: '#f9f9fd'
  surface-dim: '#d9dade'
  surface-bright: '#f9f9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f7'
  surface-container: '#eeedf2'
  surface-container-high: '#e8e8ec'
  surface-container-highest: '#e2e2e6'
  on-surface: '#1a1c1f'
  on-surface-variant: '#454654'
  inverse-surface: '#2f3034'
  inverse-on-surface: '#f0f0f4'
  outline: '#757685'
  outline-variant: '#c5c5d6'
  surface-tint: '#4051ca'
  primary: '#000d66'
  on-primary: '#ffffff'
  primary-container: '#001a9e'
  on-primary-container: '#8391ff'
  inverse-primary: '#bcc2ff'
  secondary: '#00629d'
  on-secondary: '#ffffff'
  secondary-container: '#00a2fd'
  on-secondary-container: '#003558'
  tertiary: '#1c1e1e'
  on-tertiary: '#ffffff'
  tertiary-container: '#313333'
  on-tertiary-container: '#9a9b9b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dfe0ff'
  primary-fixed-dim: '#bcc2ff'
  on-primary-fixed: '#000c61'
  on-primary-fixed-variant: '#2436b1'
  secondary-fixed: '#cfe5ff'
  secondary-fixed-dim: '#98cbff'
  on-secondary-fixed: '#001d33'
  on-secondary-fixed-variant: '#004a77'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#f9f9fd'
  on-background: '#1a1c1f'
  surface-variant: '#e2e2e6'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  sidebar-width: 280px
  bottom-bar-height: 64px
---

## Brand & Style

The design system is engineered for a Progressive Web App (PWA) environment, emphasizing high-performance, security, and a "native-feel" user experience. The aesthetic is **Corporate / Modern**, characterized by a systematic approach to hierarchy, precision-aligned elements, and a high-trust atmosphere. 

The brand personality is authoritative yet dynamic, leveraging a stark, high-contrast palette to evoke reliability and technical excellence. The UI focuses on utility and speed, ensuring that the interface feels responsive and dependable for professional users.

## Colors

This color palette is strictly derived from the brand's identity, focusing on depth and vibrancy against a sterile white environment.

- **Primary (#001A9E):** Deep Navy. Used for core branding, primary action buttons, and critical UI states that require a sense of permanence and security.
- **Secondary (#00A3FF):** Vibrant Azure. Utilized for interactive elements, focus states, links, and accents to provide a "kinetic" energy to the interface.
- **Tertiary/Surface (#FFFFFF):** Clean White. The primary background color to maintain a high-trust, clinical workspace.
- **Neutral (#121417):** A near-black for high-readability text and structural borders.

## Typography

The typography system utilizes **Inter** exclusively to achieve a modern, tech-focused PWA feel. It is chosen for its exceptional legibility on digital screens and its neutral, systematic character. 

Hierarchy is established through tight scaling and purposeful weight shifts. Headlines use a slightly tighter letter-spacing to feel more cohesive and impactful. Labels are occasionally set in uppercase with increased tracking to differentiate from body text in data-heavy contexts.

## Layout & Spacing

The layout is optimized for PWA usage, prioritizing bottom-weighted interactions on mobile and structural stability on desktop.

- **Mobile (< 768px):** Navigation is moved to a bottom tab bar for "thumb-friendly" access. Margins are fixed at 16px.
- **Desktop (>= 768px):** Navigation transitions to a persistent left sidebar. Content is placed within a fluid grid that maintains a maximum readable width of 1200px.
- **Spacing Rhythm:** A 4px/8px baseline grid is used to maintain strict vertical and horizontal alignment. All component spacing must be a multiple of the base 4px unit.

## Elevation & Depth

This design system uses **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows to maintain a clean, professional aesthetic.

1.  **Level 0 (Surface):** The primary background (#FFFFFF).
2.  **Level 1 (Card/Container):** Uses a subtle 1px border (#E2E8F0) to define areas.
3.  **Interactive Depth:** Elements like primary buttons use a solid fill of #001A9E. Active or pressed states are indicated by a subtle shift to #00A3FF. 
4.  **Shadows:** When necessary for overlays (e.g., Modals), use a very soft, diffused ambient shadow: `0 4px 20px rgba(0, 26, 158, 0.08)`. This tints the shadow with the primary navy to keep it integrated with the brand.

## Shapes

The shape language is **Soft**, utilizing a 0.25rem (4px) base radius. This provides a professional, disciplined appearance that feels modern without becoming too casual or "bubbly."

- **Standard Buttons/Inputs:** 4px radius.
- **Large Cards/Containers:** 8px (rounded-lg) radius.
- **Full Radius:** Only used for small badge-style chips or status indicators.

## Components

- **Buttons:** Primary buttons are #001A9E with white text. Secondary buttons use a #00A3FF outline with navy text. The hover state for primary buttons increases saturation or shifts slightly toward the Azure.
- **Bottom Navigation (Mobile):** Icons are #001A9E when active, accompanied by a small dot indicator. Inactive icons are a medium-gray neutral.
- **Sidebar (Desktop):** Links are high-contrast with a 4px vertical accent bar in Azure (#00A3FF) to denote the active page.
- **Input Fields:** Use a 1px #E2E8F0 border that shifts to a 2px Azure (#00A3FF) border on focus. Labels sit just above the field in `label-sm` typography.
- **Cards:** White backgrounds with a subtle border. No shadows are used for standard dashboard cards; they rely on 16px internal padding for clarity.
- **Chips:** Used for status. Success states use Azure with a light tint background; neutral states use Navy with a light tint background.