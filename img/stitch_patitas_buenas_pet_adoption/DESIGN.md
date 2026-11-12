---
name: Warm Shelter Modern
colors:
  surface: '#f3faff'
  surface-dim: '#bedfef'
  surface-bright: '#f3faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#e6f6ff'
  surface-container: '#d8f2ff'
  surface-container-high: '#ccedfe'
  surface-container-highest: '#c6e8f8'
  on-surface: '#001f29'
  on-surface-variant: '#55423e'
  inverse-surface: '#123441'
  inverse-on-surface: '#dff4ff'
  outline: '#88726d'
  outline-variant: '#dbc1ba'
  surface-tint: '#9a442d'
  primary: '#9a442d'
  on-primary: '#ffffff'
  primary-container: '#e07a5f'
  on-primary-container: '#5b1604'
  inverse-primary: '#ffb4a1'
  secondary: '#386753'
  on-secondary: '#ffffff'
  secondary-container: '#b8ebd1'
  on-secondary-container: '#3d6c57'
  tertiary: '#8e4e14'
  on-tertiary: '#ffffff'
  tertiary-container: '#d18547'
  on-tertiary-container: '#4c2500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd2'
  primary-fixed-dim: '#ffb4a1'
  on-primary-fixed: '#3c0800'
  on-primary-fixed-variant: '#7c2e19'
  secondary-fixed: '#bbeed4'
  secondary-fixed-dim: '#9fd1b8'
  on-secondary-fixed: '#002115'
  on-secondary-fixed-variant: '#1f4f3c'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#ffb780'
  on-tertiary-fixed: '#2f1400'
  on-tertiary-fixed-variant: '#6f3800'
  background: '#f3faff'
  on-background: '#001f29'
  surface-variant: '#c6e8f8'
typography:
  display-hero:
    fontFamily: Outfit
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Outfit
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Outfit
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses compassionate guardianship, approachable warmth, and optimistic modern care. Built for animal adoption and community shelter initiatives, the UI balances emotional reassurance with functional clarity.

The visual direction blends **Warm Organic Modernism** with soft tactile accents:
- Generous, organic whitespace that removes anxiety and fosters calm browsing.
- Softly contoured surfaces and welcoming curves that evoke warmth, petting, and comfort.
- High-contrast, highly legible typographic pairings that pair friendly character with institutional trustworthiness.
- Emotional transparency: animal stories, urgent needs, and adoption readiness stages are prioritized with clean information architecture.

## Colors

The color palette translates the warmth of clay, sunlit fur, and lush recovery gardens into an accessible UI hierarchy:

- **Primary (`#E07A5F` - Terracotta):** Used for primary conversion actions (e.g., "Adoptar", "Donar ahora"), critical active states, and emotional focal points.
- **Secondary (`#81B29A` - Leaf Sage):** Represents healing, safety, veterinary clearance, and success milestones (e.g., "Adoptado", health confirmation chips).
- **Tertiary (`#F4A261` - Soft Amber):** Accent color for intermediate awareness, warm badges, foster care alerts, and playful hover feedback.
- **Neutral (`#264653` - Deep Charcoal Slate):** Grounds the interface with dark, legible typography and high-contrast anchors. Never use pure black (`#000000`).
- **Canvas & Surfaces:**
  - Background Canvas: Warm Cream (`#FDFBF7`)
  - Elevated Container / Cards: Pure Warm White (`#FFFFFF`) with subtle tinted borders (`#F4F1DE`)
  - Subdued / Muted Backgrounds: Muted Sand (`#F4F1DE`)

### Status Indicators
- **Urgente (Urgent Foster / Medical):** Deep Coral/Crimson tint overlay with `#E07A5F` border.
- **En Espera (Pending match / Under review):** Warm Amber background `#F4A261` with `#264653` text.
- **Adoptado (Successfully adopted):** Soft Sage `#81B29A` with pure white or deep slate typography.

## Typography

The type system blends friendly, geometric charisma in headings with crisp structural legibility for dense profile details:

- **Headlines (Outfit):** Provides a welcoming, human, and modern geometry. Curved strokes feel gentle and non-corporate, projecting optimism across adoption appeals and pet stories.
- **Body & Labels (Plus Jakarta Sans):** Highly legible humanist sans-serif with open apertures and clean numerals, ensuring clear readability for age, health history, and adoption procedures.

Rules:
- Never set long editorial or narrative paragraphs in `Outfit`.
- Pet attribute callouts (e.g., "Macho • 2 años • Vacunado") must use `body-sm` or `label-lg` with sufficient tracking to preserve quick scanning.

## Layout & Spacing

The layout is built around an airy, fluid 12-column grid on desktop and tablet, collapsing to a 4-column responsive grid on mobile:

- **Desktop (1024px+):** 12 columns, 1.5rem gutter, 3rem canvas margin, max content containment at 1280px.
- **Tablet (768px - 1023px):** 8 columns, 1.25rem gutter, 2rem canvas margin.
- **Mobile (<768px):** 4 columns, 1rem gutter, 1.25rem canvas margin.

### Rhythm & Vertical Cadence
- Use `space-xs` and `space-sm` for inline metadata clusters, badge paddings, and tag lists.
- Use `space-md` for card body padding and input fields.
- Use `space-lg` and `space-xl` for section separation, card group gaps, and storytelling transitions.

## Elevation & Depth

Visual hierarchy uses **tonal layer nesting** combined with soft, warm-tinted ambient drop shadows to produce an inviting, tangible feel:

- **Base Canvas:** Flat `#FDFBF7`.
- **Level 1 (Cards, Filter bars):** `#FFFFFF` surface resting on the canvas, bounded by a 1px solid border in `#F4F1DE`, paired with an ultra-soft tinted shadow: `0 4px 20px -2px rgba(38, 70, 83, 0.05)`.
- **Level 2 (Hovered cards, Dropdowns):** Subtle vertical lift `translateY(-3px)` with deepened diffusion: `0 12px 28px -4px rgba(38, 70, 83, 0.09)`.
- **Level 3 (Modals, Adoption inquiry sheets):** `#FFFFFF` surface layered above a dimmed backdrop (`rgba(38, 70, 83, 0.45)` with 4px backdrop blur), supported by `0 24px 48px -8px rgba(38, 70, 83, 0.16)`.
- **No Stark Borders:** Avoid harsh black or cold gray borders; all borders use natural sandstone tones (`#F4F1DE` or `#E07A5F` at 20% opacity).

## Shapes

The shape system conveys kindness, safety, and gentleness:

- **Standard Containers & Cards:** `rounded-lg` (1rem / 16px) or `rounded-xl` (1.5rem / 24px) for prominent pet preview cards and hero banners.
- **Interactive Controls (Buttons, Inputs):** 0.75rem to 1rem corner radius to create an inviting, soft touch-target.
- **Badges, Status Tags, Pill Filters:** Strictly pill-shaped (`rounded-full` / 9999px) to contrast against rectangular content cards and denote status states intuitively.
- **Pet Image Frames:** Always clip pet photography with matching surface border radiuses (`rounded-xl` / 1.5rem) to maintain softness throughout the feed.

## Components

### Buttons
- **Primary Action ("Adoptar", "Donar"):** Filled with `#E07A5F`, text in `#FFFFFF`, `rounded-full` or 0.75rem border radius. Hover introduces `#D0674B` with a subtle elevation lift.
- **Secondary Action ("Saber más", "Ver requisitos"):** Outlined with 1.5px solid `#81B29A`, text in `#264653`, background transparent. Hover fills with `#81B29A` at 12% tint.
- **Tertiary / Ghost:** Text `#264653`, no border, underlines on hover.

### Status Chips & Badges
- Displayed as compact, fully rounded pills (`rounded-full`) with `label-sm` bold text:
  - **Adoptado:** Background `#81B29A` with `#FFFFFF` text. Optional soft check icon.
  - **En espera:** Background `#F4A261` with `#264653` text.
  - **Urgente:** Background `#E07A5F` with `#FFFFFF` text and subtle pulsing dot indicator.

### Pet Profile Cards
- Composed of an upper image container (16:11 aspect ratio, `rounded-xl` overflow hidden) with the status badge pinned floating to top-left (`space-sm` offset).
- Favorite/Bookmark icon pinned to top-right on a frosted circular surface (`rgba(253, 251, 247, 0.85)`).
- Card body includes pet name (`headline-sm`), demographic tags (breed, sex, age) rendered as soft grey/green muted tags, and a prominent bottom action strip.

### Form Inputs & Filters
- Text inputs and search bars sit on `#FFFFFF` with 1.5px borders in `#F4F1DE`.
- Focus state: Border transitions to `#E07A5F` with a soft outer ring `0 0 0 3px rgba(224, 122, 95, 0.2)`.
- Filter chips for category browsing (Perros, Gatos, Cachorros, Adultos mayores): Pill-shaped `#F4F1DE` chips that shift to solid `#264653` with `#FFFFFF` typography when selected.

### Checkboxes & Radio Buttons
- Custom circular radios and rounded checkboxes (0.35rem radius).
- Checked state: Filled with `#81B29A` displaying crisp white vector marks.