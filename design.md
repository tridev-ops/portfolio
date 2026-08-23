---
name: Tridev Portfolio
colors:
  surface: '#1E293B'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#bcc7de'
  on-secondary: '#263143'
  secondary-container: '#3e495d'
  on-secondary-container: '#aeb9d0'
  tertiary: '#c5cce6'
  on-tertiary: '#283044'
  tertiary-container: '#a9b1ca'
  on-tertiary-container: '#3c4459'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#0F172A'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
  text-primary: '#FFFFFF'
  text-secondary: '#94A3B8'
  accent-glow: rgba(56, 189, 248, 0.15)
typography:
  display:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-mobile:
    fontFamily: Geist
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
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
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  section-gap: 8rem
  container-max: 1100px
  gutter: 24px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system embodies a **Modern Minimalist** aesthetic tailored for a high-end developer portfolio. The brand personality is professional, precise, and intellectually curious. It avoids the "noisy" decorations common in creative portfolios to prioritize code-like clarity and structural honesty.

The visual direction leverages a "Developer-First" sophistication, utilizing a monochromatic foundation with a single precision-engineered accent color. The goal is to evoke a sense of reliability and technical mastery through generous whitespace, high-contrast typography, and a "breathable" layout that treats content as the primary interface element.

## Colors
The palette is rooted in a deep, "Night-Sky" dark mode. 

- **Primary (#38BDF8):** An electric, sky-blue used exclusively for interactive highlights, key CTAs, and active states. It represents the "spark" of innovation.
- **Surface Layers:** The background utilizes the darkest shade (#0F172A), while cards and containers use a slightly elevated navy (#1E293B) to create depth without relying on shadows.
- **Typography:** Pure white is reserved for high-level headings to ensure maximum impact, while a muted slate-gray (#94A3B8) is used for body text and metadata to reduce eye strain and establish clear hierarchy.

## Typography
The system uses a triple-font approach to balance character and utility. 

- **Headings:** Geist provides a technical, sharp geometric feel that resonates with modern software engineering. Tight letter spacing is used for large display sizes to create a "compact" high-end look.
- **Body:** Inter is the workhorse, selected for its exceptional legibility at small sizes and its neutral, "system-like" appearance.
- **Data/Tags:** JetBrains Mono (monospaced) is used for skills, tags, and small metadata labels to reinforce the developer-centric identity of the brand.

## Layout & Spacing
This design system employs a **Fixed Centered Grid** for desktop and a **Fluid Single-Column** layout for mobile. 

- **Vertical Rhythm:** Large "Section Gaps" (128px on desktop, 80px on mobile) ensure the user focuses on one narrative beat at a time (e.g., transitioning from "Skills" to "Projects").
- **Grid:** A 12-column grid is used for the "Projects" section, typically spanning 6 columns per card or 12 columns for featured items.
- **Safe Zones:** Use a minimum 24px horizontal margin on mobile to ensure content doesn't hit the screen edges.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Subtle Outlines** rather than heavy drop shadows.

- **Level 0 (Base):** The main page background (#0F172A).
- **Level 1 (Cards):** Surfaces using #1E293B with a 1px solid border of #94A3B8 at 10% opacity. 
- **Active State:** When interacting with a card or button, a "Primary Glow" is applied—a soft, 20px blur using `accent-glow` to make the element feel as if it's backlit by the primary accent color.
- **Glassmorphism:** Navigation headers use a backdrop blur (20px) with a semi-transparent background to maintain context while scrolling.

## Shapes
The shape language is **Soft (Level 1)**. 

- **Standard Elements:** Buttons and input fields use a 0.25rem (4px) radius to maintain a professional, slightly "sharp" edge.
- **Content Containers:** Project cards and Skill tags use a 0.5rem (8px) radius to feel approachable and modern.
- **Pill Elements:** Only used for "Status Indicators" (e.g., "Live", "Coming Soon") to differentiate them from functional buttons.

## Components

- **Buttons:** Primary buttons use a solid #38BDF8 background with #0F172A text. Secondary buttons are "Ghost" style: 1px border of the accent color with no fill, transitioning to a subtle glow on hover.
- **Skill Tags:** Use the monospaced `label-caps` font. Background is `surface` with a subtle primary-colored border (20% opacity). They should be displayed in a wrap-flex layout.
- **Project Cards:** Feature a top-aligned image or code snippet, followed by `headline-md` titles. The entire card is a hit area with a subtle vertical lift on hover (+4px Y-axis).
- **Input Fields:** Minimalist design with only a bottom border (#94A3B8) that transforms into a full 1px primary-colored outline when focused.
- **Navigation:** Top-fixed, minimal links using the `label-caps` style. The "Logo" (TRIDEV) should be bold Geist at 20px, with the first letter optionally tinted in the primary color.