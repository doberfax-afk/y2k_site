---
name: Y2K Party Magazine
colors:
  surface: '#fbf8fc'
  surface-dim: '#dcd9dd'
  surface-bright: '#fbf8fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f2f7'
  surface-container: '#f0edf1'
  surface-container-high: '#eae7eb'
  surface-container-highest: '#e4e1e6'
  on-surface: '#1b1b1e'
  on-surface-variant: '#594046'
  inverse-surface: '#303033'
  inverse-on-surface: '#f3f0f4'
  outline: '#8d6f76'
  outline-variant: '#e0bec5'
  surface-tint: '#b9045e'
  primary: '#b9045e'
  on-primary: '#ffffff'
  primary-container: '#ff4b91'
  on-primary-container: '#5a002a'
  inverse-primary: '#ffb1c6'
  secondary: '#6b38d4'
  on-secondary: '#ffffff'
  secondary-container: '#8455ef'
  on-secondary-container: '#fffbff'
  tertiary: '#00668a'
  on-tertiary: '#ffffff'
  tertiary-container: '#009cd2'
  on-tertiary-container: '#002e41'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e1'
  primary-fixed-dim: '#ffb1c6'
  on-primary-fixed: '#3f001b'
  on-primary-fixed-variant: '#8e0046'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#fbf8fc'
  on-background: '#1b1b1e'
  surface-variant: '#e4e1e6'
typography:
  display-xl:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 68px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '500'
    lineHeight: 22px
  label-bold:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.06em
  caption-hand:
    fontFamily: Caveat
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit-xs: 4px
  unit-sm: 8px
  unit-md: 16px
  unit-lg: 24px
  unit-xl: 32px
  unit-2xl: 48px
  unit-3xl: 64px
  gutter: 20px
  container-max: 1200px
---

## Brand & Style

This design system channels an unapologetic blend of late-90s/early-2000s teen magazine culture, Neo-Brutalism, and vibrant pop optimism. Tailored specifically for an interactive 21st birthday celebration, the visual tone is exuberant, tactile, nostalgic, and hyper-social. It balances the editorial layout structure of print magazines (issue numbers, glossy pull quotes, cutout collages, barcode badges) with modern interactive web affordances (tactile 3D press states, sticker peeling motions, floating glitter particles).

The overall design movement is **Neo-Brutalist Y2K Pop**: unapologetic 2px–3px jet-black borders, solid offset drop-shadows with zero blur radius, sticker-bomb layering, playful asymmetric rotations (-2° to +3°), washi-tape clips, and vibrant electric gradients layered over subtle halftone and dot-grid creamy surfaces.

## Colors

The color palette pairs nostalgic pastel paper tones with intense electric neo-pop primaries and heavy comic ink borders.

### Palette Application
- **Canvas Base**: `#FAF5FF` (Soft Lavender Tint) transitioning subtly into `#FFF1F7` (Cream Blush) using fine dot-grid textures (`radial-gradient(#E2D9F3 1px, transparent 1px)` at 16px grid intervals).
- **Primary (Bubblegum Pink - `#FF4B91`, `#FF70A6`)**: Used for main calls to action, festive badges, heart icons, hero borders, and active tabs.
- **Secondary (Electric Lilac - `#8B5CF6`, `#9D4EDD`)**: Drives interactive elements, cassette housings, player wrappers, and editorial headlines.
- **Tertiary (Sky & Ice Blue - `#38BDF8`, `#70D6FF`)**: Applied to cool counterpoints, comment bubbles, secondary badges, and retro media controls.
- **Accent Highlight (Acid Cyber Lime & Cyber Yellow - `#CCFF00`, `#FFE600`)**: Reserved for limited "VIP", "21!", "HOT!", starburst tags, and washi-tape details.
- **Structure & Ink (Jet Black - `#18181B`)**: Applied as structural ink lines (2px–3px), solid unblurred drop shadows, and high-impact headlines.

## Typography

Typography acts as the editorial spine of the magazine aesthetic, blending brutalist display geometry with ultra-clean interface type and spontaneous handwriting:

- **Display & Headings (Syne)**: Extra-bold weights (700/800) with tight tracking convey high-fashion editorial prestige turned pop. Uppercase treatments paired with slight rotations (`transform: rotate(-1.5deg)`) emphasize magazine cover callouts.
- **Body & Interface (Plus Jakarta Sans)**: Ensures maximum legibility across wishes, guest notes, and interactive guides against vibrant backgrounds.
- **Technical Badges & Meta (Space Grotesk)**: Monospaced/geometric character for date stamps, cassette track indicators, barcode subtitles, and metadata stamps.
- **Handwritten Personal Accents (Caveat)**: Injected strictly for personal captions, sticky notes, photo margins, polaroid signatures, and birthday greetings to preserve human intimacy.

## Layout & Spacing

The layout follows a 12-column dynamic editorial grid layered with floating z-index sticker zones.

- **Grid Framework**: 12 columns desktop (1200px max width with 20px gutters and 24px margins), 6 columns tablet, and 4 columns mobile.
- **Editorial Layering**: Content modules break strict vertical alignment using intentional asymmetric offsets (`translate-y-2`, `translate-x-1`) and overlapping badges to mirror physical collages and magazine paste-ups.
- **Breakpoints**:
  - `Mobile`: `< 640px` (single-column cards, full-width polaroids, persistent floating bottom audio player bar).
  - `Tablet`: `641px - 1024px` (2-column staggered layout, interactive sticker drawers).
  - `Desktop`: `> 1025px` (full 12-column editorial spread with draggable stickers, dual-column guestbook, and standalone centerfold feature).

## Elevation & Depth

Rather than realistic soft Gaussian blurs, depth is communicated through hard-edged **tactile Neo-Brutalist extrusion**:

- **Hard-Offset Shadows**:
  - `Default Layer`: `3px 3px 0px #18181B` with a `2.5px solid #18181B` border.
  - `Elevated / Hero Layer`: `6px 6px 0px #18181B` with a `3px solid #18181B` border.
  - `Floating Sticker / Badge`: `4px 4px 0px rgba(24, 24, 27, 0.9)` with a `1.5px solid #18181B`.
- **Interactive Tactile Press**:
  - Upon active/hover states, elements translate diagonally (`transform: translate(2px, 2px)`) while reducing shadow size proportionally (`1px 1px 0px #18181B`), creating an authentic mechanical "click down" sensation.
- **Gloss & Holo Overlays**:
  - Holographic badges utilize an angled linear gradient (`linear-gradient(135deg, rgba(255,255,255,0.6) 0%, rgba(204,255,0,0.3) 25%, rgba(56,189,248,0.3) 50%, rgba(255,75,145,0.4) 75%, rgba(255,255,255,0.6) 100%)`) with `mix-blend-mode: overlay`.

## Shapes

Shapes utilize a deliberate hybrid of crisp rectangular photo stock and soft pill containers:

- **Border Radius**: Base elements use `0.5rem` (8px), outer cards and cassette decks use `1rem` (16px), and interactive action pills use full radius (`9999px`).
- **Washi Tape Strips**: Semi-transparent rectangular banners (`rgba(255, 230, 0, 0.85)` or `#FF70A6`) with jagged CSS `clip-path` ends pasted diagonally across Polaroid corners.
- **Starburst Tags**: 8-point and 12-point polygon clipped stickers (`clip-path: polygon(...)`) for "HOT", "21", and "EXCLUSIVE" tags.

## Components

### Buttons
- **Primary Action**: Bold Bubblegum Pink (`#FF4B91`) background, white Syne bold text, 2.5px solid `#18181B` border, and `4px 4px 0px #18181B` hard shadow. On `:hover`, shifts color to `#FF70A6`. On `:active`, translates `translate(2px, 2px)` with shadow reduced to `2px 2px 0px #18181B`.
- **Secondary / Ghost**: White or `#FAF5FF` base with lilac text (`#8B5CF6`), 2px solid `#18181B` border, and `3px 3px 0px #8B5CF6`.

### Polaroid Cards (Photo & Message Stream)
- White solid substrate (`#FFFFFF`) with 12px top/side padding and 36px bottom signature area.
- Framed with 2px solid `#18181B`, rotated between `-2.5deg` and `+2deg` randomly.
- Upper corner features a semi-translucent washi tape accent (`#FFE600` at 85% opacity, `transform: rotate(-12deg)`).
- Bottom margin reserved for personal notes in Caveat handwriting font.

### Interactive Y2K Cassette Player
- Body composed of Electric Lilac (`#8B5CF6`) and Sky Blue (`#38BDF8`) dual-molded plastic styling.
- Twin cassette spools styled as rotating SVG wheels with black circular teeth and clear window gradient cutout.
- Track info rendered in Space Grotesk in a bold contrast box. Mechanical buttons ("PLAY", "REWIND", "PARTY MIX") styled as extruded 3D push tabs.

### Sparkle & Holographic Badges
- Pill-shaped or starburst-clipped badges with neon yellow/lime (`#CCFF00`) fill, jet-black uppercase text, and an animated four-point star icon (`✦`) on the trailing edge.

### Inputs & Guestbook Forms
- Cream/white input fields bordered with 2px `#18181B`, hard shadow `3px 3px 0px #18181B`.
- Focus state expands shadow to `4px 4px 0px #FF4B91` with zero outline blur.
- Placeholder text styled in playful muted ink (`#71717A`).