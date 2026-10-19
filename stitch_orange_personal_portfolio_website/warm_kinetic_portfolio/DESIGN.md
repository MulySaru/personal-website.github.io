---
name: Warm Kinetic Portfolio
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#5a4136'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#8e7164'
  outline-variant: '#e2bfb0'
  surface-tint: '#a04100'
  primary: '#a04100'
  on-primary: '#ffffff'
  primary-container: '#ff6b00'
  on-primary-container: '#572000'
  inverse-primary: '#ffb693'
  secondary: '#675c55'
  on-secondary: '#ffffff'
  secondary-container: '#ebddd3'
  on-secondary-container: '#6b6159'
  tertiary: '#895026'
  on-tertiary: '#ffffff'
  tertiary-container: '#ce895a'
  on-tertiary-container: '#512500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#ffb693'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#7a3000'
  secondary-fixed: '#eee0d6'
  secondary-fixed-dim: '#d2c4bb'
  on-secondary-fixed: '#211a14'
  on-secondary-fixed-variant: '#4e453e'
  tertiary-fixed: '#ffdcc7'
  tertiary-fixed-dim: '#ffb786'
  on-tertiary-fixed: '#311300'
  on-tertiary-fixed-variant: '#6d3910'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a personal portfolio and professional identity experience that bridges authentic warmth with contemporary digital craft. Designed for ambitious professionals, creatives, and engineers presenting bilingual English and Thai profiles, the aesthetic pivots away from flat, cookie-cutter resumes toward an engaging, high-clarity editorial format.

The visual style blends **Modern Minimalism** with **Warm Tactile Nuance**:
- **Personality:** Optimistic, dynamic, disciplined, approachable, and articulate.
- **Atmosphere:** Sunlit studio energy—clean white backgrounds anchored by vibrant solar orange accents, balanced by rich slate typography and delicate cream backdrops.
- **Core Intent:** Present career history, bilingual competencies, project artifacts, and personal milestones through organized modular cards, tactile status chips, and crisp tabular hierarchies that respect scanning patterns on desktop, tablet, and mobile displays.

## Colors

The color architecture relies on high contrast and warm tonal pacing to structure hierarchy effortlessly across personal bio sections and portfolio grids.

### Roles & Semantic Mapping
- **Primary (`#FF6B00`):** Electric solar orange. Reserved for primary calls to action, brand monograms, active navigation indicators, key metrics, and focus halos.
- **Secondary (`#FFF0E6`):** Soft melon/cream surface wash. Provides soothing background contrast for callouts, tag surfaces, active tab states, and nested section containers.
- **Tertiary (`#FFB380`):** Muted apricot border and auxiliary accent. Serves as interactive hover accents, timeline milestone rings, and delicate divider strokes.
- **Neutral Core (`#1E293B`):** Deep charcoal slate. Establishes WCAG AAA legibility for headlines, body copy, and UI icons against white and cream surfaces, avoiding the harshness of pitch black.
- **Base Canvas:** Crisp pure white (`#FFFFFF`) backed with subtle warm off-white canvas backgrounds (`#FAFAF9`) to prevent glare during sustained review.

## Typography

Typography pairs **Plus Jakarta Sans** for prominent headers with **Inter** for clean body text, data points, and technical metadata. When rendering Thai glyphs, standard platform fallbacks (such as *Prompt* or *Kanit* for titles, and *Sarabun* or *Sukhumvit Set* for body text) seamlessly match the geometry and baseline alignments.

- **Headlines:** Plus Jakarta Sans delivers structural warmth with rounded letter junctions and high x-height, rendering candidate titles and achievements with personality and presence.
- **Body & Meta:** Inter handles detailed career timelines, project notes, contact specs, and bilingual strings with clinical precision and neutral readability.
- **Bilingual Rhythms:** Because Thai script lacks Latin capitalization and requires vertical room for tonal marks and vowels, line heights are generously spaced (minimum 1.5× for body, 1.25× for titles) to prevent mark clipping.

## Layout & Spacing

The layout is built upon an adaptive 12-column fluid grid system that scales to showcase personal profile summaries alongside modular content segments.

- **Desktop (1024px+):** 12-column grid with a 1200px max-width container, 24px (`1.5rem`) gutters, and 32px (`2rem`) page margins. Asymmetrical card structures pair a 4-column sticky profile/contact rail with an 8-column scrolling content stack (experience, education, tool proficiencies, project portfolio).
- **Tablet (768px – 1023px):** 8-column layout with 20px gutters and 24px margins. The profile rail sits as a compact horizontal header above stacked dual-column cards.
- **Mobile (< 768px):** 4-column flow with 16px (`1rem`) gutters and 20px (`1.25rem`) margins. Content reflows into a single clean column with edge-to-edge modular containers.
- **Spacing Rhythm:** Micro elements within component containers follow strict 4px/8px intervals (`space-xs` to `space-xl`) to preserve clean typographic hierarchy without clutter.

## Elevation & Depth

Visual hierarchy is maintained through subtle tonal layering and soft ambient drop shadows rather than heavy structural borders.

- **Flat Canvas:** Background canvas sits at neutral `#FAFAF9`, providing subtle contrast against foreground cards.
- **Layer 1 (Card Baseline):** Pure white (`#FFFFFF`) surfaces elevated with an ambient, sun-warmed shadow: `box-shadow: 0 4px 20px -2px rgba(30, 41, 59, 0.05), 0 2px 6px -1px rgba(255, 107, 0, 0.04)`. A gentle 1px border (`#F1F5F9`) delivers crisp boundary definition.
- **Layer 2 (Interactive Floating / Hover):** Cards and active callouts elevate slightly on hover (`translateY(-2px)`) with expanded orange-tinted diffusion: `box-shadow: 0 12px 28px -4px rgba(255, 107, 0, 0.12), 0 4px 12px -2px rgba(30, 41, 59, 0.04)`.
- **Layer 3 (Modals & Sticky Bars):** Floating bottom action bars or zoom modals use subtle backdrop filtration (`backdrop-filter: blur(12px)`) combined with `rgba(255, 255, 255, 0.85)` surface transparency and deep grounding shadows (`rgba(30, 41, 59, 0.15)`).

## Shapes

The design adopts a modern rounded visual geometry (Level 2: `roundedness: 2`), introducing friendly curvature that balances technical rigor with approachability:

- **Standard Containers & Cards:** `0.5rem` (8px) base radius, stepping up to `1rem` (16px, `rounded-lg`) for major portfolio cards, contact sections, and avatar frames.
- **Pills & Badges:** Full pill geometry (`rounded-full` / `9999px`) reserved strictly for status chips, skill tags, language proficiency indicators, and primary action buttons.
- **Avatar Container:** Rounded square (`1.5rem` / 24px radius) or circular frame bounded by a 3px solid white rim and a subtle orange accent ring.

## Components

### Buttons
- **Primary:** Filled vibrant orange (`#FF6B00`) with crisp white label (`label-lg`), pill-shaped (`rounded-full`), padded `0.75rem 1.75rem`. Hover shifts to `#E65100` with subtle elevation. Focus ring produces a 3px translucent orange aura (`rgba(255, 107, 0, 0.25)`).
- **Secondary / Ghost:** Soft cream background (`#FFF0E6`) with vibrant orange text (`#FF6B00`) and no border; hover activates a 1px border stroke in `#FFB380`.
- **Icon Buttons:** Pill-circular (`40px × 40px`) for social channels (LinkedIn, GitHub, Email, Phone), using light neutral fill (`#F8FAFC`) with `#1E293B` icons, transitioning to orange surfaces on hover.

### Badges & Skill Chips
- **Pill Badges:** Capsule form (`rounded-full`), `0.25rem 0.75rem` padding. Light `#FFF0E6` background with bold `#FF6B00` text in `label-sm`. Used for key software tags (Canva, Excel, SAP), hobbies, and work status.
- **Language Proficiency Indicator:** A structured horizontal bar pairing the language label (e.g., "TH", "EN") with 5 connected circular indicator dots (filled orange for fluency, soft gray `#E2E8F0` for remaining levels).

### Profile Cards & Section Containers
- **Card Surface:** Crisp white background (`#FFFFFF`), `1rem` corner radius, 1px border in `#F1F5F9`, internal padding `1.5rem` (desktop) or `1.25rem` (mobile).
- **Section Headers:** Clean, unbordered section titles featuring an inline mini-pill or left accent bar in `#FF6B00`, followed by `headline-sm` in dark slate.

### Timeline & Experience Lists
- **Item Rhythm:** Vertical line in muted warm cream (`#FFE4D6`) with a 10px solid orange bullet marking positions and degrees. 
- **Metadata Layout:** Date span rendered in `label-md` uppercase slate muted (`#64748B`), role title in `headline-sm`, and organization/university in `body-md` bold.

### Form Inputs & Contact Items
- **Text Inputs:** Soft rounded rectangular fields (`rounded-md`), border in `#E2E8F0`, light background `#FFFFFF`. Active focus border snaps to `#FF6B00` with zero layout shift.
- **Contact Rows:** Flex container featuring a soft orange circular icon bubble (`36px`), followed by bold metadata labels (`label-md`) and selectable high-contrast values.