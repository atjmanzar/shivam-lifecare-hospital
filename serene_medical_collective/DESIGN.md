---
name: Serene Medical Collective
colors:
  surface: '#f7faf9'
  surface-dim: '#d7dbda'
  surface-bright: '#f7faf9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f3'
  surface-container: '#ebeeed'
  surface-container-high: '#e6e9e8'
  surface-container-highest: '#e0e3e2'
  on-surface: '#181c1c'
  on-surface-variant: '#3e4948'
  inverse-surface: '#2d3131'
  inverse-on-surface: '#eef1f0'
  outline: '#6e7978'
  outline-variant: '#bec9c8'
  surface-tint: '#026a69'
  primary: '#006665'
  on-primary: '#ffffff'
  primary-container: '#2a7f7e'
  on-primary-container: '#e8fffe'
  inverse-primary: '#85d4d2'
  secondary: '#8a4e40'
  on-secondary: '#ffffff'
  secondary-container: '#feb19e'
  on-secondary-container: '#794133'
  tertiary: '#416247'
  on-tertiary: '#ffffff'
  tertiary-container: '#597b5e'
  on-tertiary-container: '#eeffec'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a1f0ef'
  primary-fixed-dim: '#85d4d2'
  on-primary-fixed: '#002020'
  on-primary-fixed-variant: '#00504f'
  secondary-fixed: '#ffdad2'
  secondary-fixed-dim: '#ffb4a3'
  on-secondary-fixed: '#370e05'
  on-secondary-fixed-variant: '#6e382b'
  tertiary-fixed: '#c7ecc9'
  tertiary-fixed-dim: '#abd0ae'
  on-tertiary-fixed: '#01210c'
  on-tertiary-fixed-variant: '#2e4e34'
  background: '#f7faf9'
  on-background: '#181c1c'
  surface-variant: '#e0e3e2'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '500'
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
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
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

The design system is built upon the persona of a "Caring Senior Doctor"—authoritative and highly competent, yet approachable and warm. It avoids the sterile, cold aesthetics typical of institutional healthcare in favor of a boutique, high-end hospitality feel that emphasizes fertility and holistic wellness.

The visual style is **Modern Corporate with Tactile Warmth**, utilizing organic shapes and a soft color palette to reduce patient anxiety. It leverages heavy whitespace and soft-focus imagery to evoke a sense of calm and luxury. The emotional response is one of safety, empathy, and professional excellence.

## Colors

This design system utilizes a palette designed to balance medical professionalism with nurturing warmth.

- **Primary Teal (#2A7F7E):** Used for primary actions, navigation, and brand-heavy elements. It communicates competence.
- **Secondary Coral (#F4A896):** Used sparingly for "Life-giving" moments, IVF-related highlights, and soft calls to action.
- **Tertiary Sage (#7EA182):** Used for trust indicators, success states, and secondary supportive accents.
- **Neutral Surface (#FAFAF8):** The background is never pure white, but this warm off-white to maintain a "living room" comfort level.
- **Text Charcoal (#2E2E2E):** Ensures high legibility without the harsh contrast of pure black.

## Typography

The typography strategy prioritizes accessibility for diverse age groups. 

**Sora** is the voice of the brand—used for headings to provide a distinctive, modern, and friendly character. Its geometric roots are softened by humanist details, making it feel premium yet humble.

**Inter** is the workhorse for all functional and body copy. A base size of **18px** is established for primary body content to ensure effortless readability for patients under stress or with visual impairments. Use tighter line heights for headings and generous line heights (1.5x+) for body paragraphs.

## Layout & Spacing

The design system employs a **Fluid-Fixed Hybrid Grid** based on an 8px rhythmic scale. 

- **Desktop:** 12-column grid with a maximum content width of 1280px. Use wide 64px margins to allow the UI to breathe.
- **Mobile:** 4-column grid with 20px margins.
- **Vertical Rhythm:** Use the `lg` (48px) and `xl` (80px) spacing tokens between major sections to prevent the interface from feeling cluttered or "urgent." Healthcare information should be paced slowly for better comprehension.

## Elevation & Depth

This design system uses **Tonal Layering and Ambient Shadows** to create a sense of gentle floating. 

- **Surface Levels:** The base level is the warm off-white. Secondary containers (like cards) sit on top with a pure white fill.
- **Shadows:** Use extremely diffused, low-opacity shadows. The shadow color should not be grey, but a tinted version of the primary teal (e.g., `#2A7F7E` at 8% opacity) to maintain a soft, integrated look.
- **Blur:** High blur radius (20px-40px) with low vertical offset (4px-8px) is preferred to avoid "heavy" or "dirty" UI elements.

## Shapes

The shape language is defined by **Generous Radii**. 

Standard cards and containers use a **20px radius** to eliminate sharp corners, which can subconsciously trigger a sense of danger or clinical coldness. Buttons and interactive chips are **Pill-shaped (Fully Rounded)** to emphasize the "friendly/approachable" brand pillar. Smaller elements like input fields should use a consistent 8px-12px radius.

## Components

### Buttons
- **Primary:** Pill-shaped, Primary Teal background, White text. 16px horizontal and 24px vertical padding.
- **Secondary:** Pill-shaped, Coral background. Used exclusively for "Book Appointment" or "Maternity Services."
- **Ghost:** Primary Teal stroke (1px) with no fill.

### Cards
- **Patient Info/Service Cards:** White background, 20px radius, soft teal-tinted shadow.
- **Padding:** Minimum 32px internal padding to ensure content feels uncrowded.

### Form Fields
- **Inputs:** 12px radius, light grey border (softening to Primary Teal on focus). 
- **Labels:** Inter Semi-bold, 14px, positioned above the field for clarity.

### Feedback & Status
- **Success:** Sage Green.
- **Information:** Primary Teal.
- **Urgent:** Use a deeper coral, avoiding harsh reds where possible to maintain the "calm" atmosphere.

### Specialized Components
- **Doctor Profile Cards:** Focus on the headshot with a circular or soft-square crop, utilizing Sora for the name and Inter for the specialty.
- **Service Chips:** Fully rounded, light tints of Primary Teal or Sage for categorizing hospital departments.