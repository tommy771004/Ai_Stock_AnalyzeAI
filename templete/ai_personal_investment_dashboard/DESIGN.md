---
name: AI Personal Investment Dashboard
colors:
  surface: '#10131c'
  surface-dim: '#10131c'
  surface-bright: '#363943'
  surface-container-lowest: '#0b0e16'
  surface-container-low: '#191b24'
  surface-container: '#1d1f28'
  surface-container-high: '#272a33'
  surface-container-highest: '#32343e'
  on-surface: '#e1e2ee'
  on-surface-variant: '#c2c6d8'
  inverse-surface: '#e1e2ee'
  inverse-on-surface: '#2e303a'
  outline: '#8c90a1'
  outline-variant: '#424656'
  surface-tint: '#b3c5ff'
  primary: '#b3c5ff'
  on-primary: '#002b75'
  primary-container: '#0066ff'
  on-primary-container: '#f8f7ff'
  inverse-primary: '#0054d6'
  secondary: '#d1bcff'
  on-secondary: '#3c0090'
  secondary-container: '#7000ff'
  on-secondary-container: '#ddcdff'
  tertiary: '#ffb59d'
  on-tertiary: '#5d1900'
  tertiary-container: '#cc4204'
  on-tertiary-container: '#fff6f4'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#003fa4'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d1bcff'
  on-secondary-fixed: '#23005b'
  on-secondary-fixed-variant: '#5700c9'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59d'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#832600'
  background: '#10131c'
  on-background: '#e1e2ee'
  surface-variant: '#32343e'
typography:
  h1:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  mono-data:
    fontFamily: monospace
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 24px
  margin_desktop: 40px
  margin_mobile: 16px
---

## Brand & Style
The design system is engineered to project **Reliability, Intelligence, and Precision**. It targets sophisticated retail investors who require a high-density, high-performance interface for managing complex financial data through an AI-augmented lens. 

The aesthetic leverages **Modern Corporate Minimalism** with subtle **Glassmorphic** influences to denote the "weightless" nature of digital assets. The interface prioritizes clarity over decoration, using structured whitespace and a rigorous grid to instill a sense of calm in high-stakes environments. AI-driven insights are treated as "elevated" layers, visually distinct from raw data to indicate their predictive nature.

## Colors
This design system utilizes a high-contrast dark-mode default palette to reduce eye strain during prolonged market monitoring. 

*   **Primary Accent:** An "Electric Cobalt" (#0066FF) is used for primary actions and navigational highlights.
*   **Success/Profit:** A "Cool Mint" (#00C087) is chosen for its high visibility against dark backgrounds. It is shifted toward blue to assist those with Protanopia (red-blindness).
*   **Error/Loss:** A "Vibrant Coral" (#FF4D4D) is used for losses, providing a sharp contrast to the success color.
*   **Accessibility (Double-Encoding):** Color alone must never be used to convey status. Every profit value must be accompanied by an upward arrow icon (↑), and every loss by a downward arrow icon (↓). In high-contrast modes, borders are added to status indicators to ensure structural visibility regardless of hue.

## Typography
The system uses **Inter** for English text to ensure maximum legibility in data-heavy tables and **Noto Sans TC** for Chinese characters to maintain a clean, sans-serif rhythm across languages.

*   **Data Numerics:** Use tabular lining figures (monospaced numbers) for financial tables to ensure that decimal points and digits align vertically, facilitating quick scanning of gains and losses.
*   **Hierarchical Scaling:** Use the `label-caps` style for table headers and section overline text to create a clear structural distinction from interactive body text.

## Layout & Spacing
The layout follows a strict **8pt Grid system**. All margins, paddings, and component heights must be multiples of 8px (or 4px for micro-adjustments).

*   **Desktop:** A 12-column fluid grid. The sidebar is fixed at 280px, while the main dashboard area expands. 
*   **Mobile:** A single-column layout with 16px side margins. 
*   **Rhythm:** Vertical spacing between cards should be 24px (lg) on desktop and 16px (md) on mobile to maintain density without overcrowding.

## Elevation & Depth
Depth is created through **Tonal Layering** rather than heavy shadows to maintain a sleek, digital-first appearance.

*   **Level 0 (Base):** The darkest neutral (#0B0E14), used for the application background.
*   **Level 1 (Surface):** The primary container color (#161B22). Cards sit on this level.
*   **Level 2 (Active/Hover):** A lighter tint or a subtle 1px inner border to indicate interactivity.
*   **AI Insights Layer:** Elements generated by AI use a subtle **backrop blur (8px)** and a faint primary-colored glow (shadow: `0 4px 20px rgba(0, 102, 255, 0.15)`) to signify they are "projected" intelligence layers above the standard data.

## Shapes
The design system adopts **Soft** roundedness (4px - 8px) to balance professional rigor with modern approachability.

*   **Small Elements (Buttons, Inputs):** 4px radius (rounded-sm) for a sharp, precise feel.
*   **Medium Elements (Cards, Modals):** 8px radius (rounded-lg) for structural containers.
*   **Large Elements (Feature Banners):** 12px radius (rounded-xl).
*   **Charts:** Line graphs should use a smoothing tension of 0.4 to avoid jagged edges, maintaining the "sophisticated" brand feel.

## Components
*   **Buttons:** Primary buttons use solid Cobalt (#0066FF) with white text. Ghost buttons use a 1px border of the neutral-gray.
*   **Cards:** Every card must have a 1px border (#30363D) to define boundaries in dark mode. Header areas in cards are separated by a subtle horizontal rule.
*   **Input Fields:** Default state has a dark background with a 1px border. Focus state triggers a Cobalt border and a 2px outer glow.
*   **Financial Chips:** Used for tickers (e.g., $AAPL). They utilize the success/error colors for the background at 10% opacity with 100% opacity text for high readability.
*   **Navigation:**
    *   **Desktop Sidebar:** Fixed left. Icons are paired with text labels. Active states use a "vertical pill" indicator on the left edge.
    *   **Desktop Top Navbar:** Reserved for global search, AI assistant toggle, and profile settings.
    *   **Mobile Bottom Bar:** 4-5 high-priority icons (Home, Portfolio, AI Insights, Markets). Active icons use the primary Cobalt color.
    *   **Mobile Hamburger:** Secondary links (Settings, Tax Documents, Help) are tucked into a top-right drawer.