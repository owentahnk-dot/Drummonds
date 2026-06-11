---
name: Heritage Alpine
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#444842'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#747872'
  outline-variant: '#c4c8c0'
  surface-tint: '#536252'
  primary: '#182519'
  on-primary: '#ffffff'
  primary-container: '#2d3b2d'
  on-primary-container: '#95a593'
  inverse-primary: '#bbcbb8'
  secondary: '#954a0c'
  on-secondary: '#ffffff'
  secondary-container: '#fc9c5a'
  on-secondary-container: '#713400'
  tertiary: '#11242c'
  on-tertiary: '#ffffff'
  tertiary-container: '#273a42'
  on-tertiary-container: '#90a4ae'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e7d3'
  primary-fixed-dim: '#bbcbb8'
  on-primary-fixed: '#111f12'
  on-primary-fixed-variant: '#3c4a3c'
  secondary-fixed: '#ffdbc7'
  secondary-fixed-dim: '#ffb688'
  on-secondary-fixed: '#311300'
  on-secondary-fixed-variant: '#733500'
  tertiary-fixed: '#d1e6f0'
  tertiary-fixed-dim: '#b5cad4'
  on-tertiary-fixed: '#0a1e26'
  on-tertiary-fixed-variant: '#374952'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
  forest-deep: '#1A241A'
  amber-glow: '#B35B21'
  slate-mountain: '#323F4B'
  paper-aged: '#F2EFE9'
  wood-dark: '#3E2723'
typography:
  headline-xl:
    fontFamily: Roboto Slab
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Roboto Slab
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Roboto Slab
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Roboto Slab
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
  tagline:
    fontFamily: Roboto Slab
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  headline-lg-mobile:
    fontFamily: Roboto Slab
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
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style

This design system establishes a **Tactile / Modern-Heritage** aesthetic for Drummond's Mountain Shop. It balances the "Since 1993" family-owned legacy with modern usability, prioritizing warmth, reliability, and the rugged spirit of the outdoors.

The visual language avoids clinical precision in favor of a handcrafted feel. Key stylistic elements include:
- **Subtle Grain Textures:** Overlays on backgrounds to mimic the grit of the trail and the feel of natural paper.
- **Organic Dividers:** Replacing harsh lines with woodgrain-inspired rules and typographic glyphs (`✶`).
- **Welcoming Softness:** Using rounded corners and warm tones to create an approachable, community-focused environment rather than a high-performance, aggressive sporting goods store.
- **High Information Density:** Maintaining a "catalog" feel that highlights brand expertise and inventory breadth.

## Colors

The palette is rooted in the natural environment of the White Mountains. 

- **Primary (Forest Green):** Used for primary navigation, headings, and foundational elements to ground the UI in nature.
- **Secondary (Warm Amber):** Reserved for Call-to-Actions, links, and highlighted shop metadata. It provides a warm, sunlit contrast to the deep greens.
- **Tertiary (Slate Gray):** Used for secondary text, metadata, and structural accents.
- **Neutral (Off-White/Bone):** Replaces pure white to reduce eye strain and provide a "field notes" parchment feel.

Backgrounds should utilize `paper-aged` for main surfaces, with `neutral_color_hex` for nested containers to create a subtle layered depth.

## Typography

The typography pairings emphasize sturdiness and legibility.

- **Headlines:** Roboto Slab provides the "rugged shop" aesthetic. It should be used for brand headings, section titles, and major category callouts.
- **Body & Labels:** Open Sans offers a clean, neutral counterpoint that ensures readability across long lists of technical gear and brands.
- **Special Styles:** The "Tagline" style (e.g., *~ Since 1993 ~*) should be used for heritage callouts, utilizing the italic weights of the slab serif to denote history and personal touch.
- **Stylistic Glyphs:** The `✶` character (Six-pointed star) should be used as an inline separator for list items in horizontal layouts, rendered in the secondary amber color.

## Layout & Spacing

The layout follows a **Hybrid Fixed Grid** model, centering content on large screens to mimic the focused feel of a local storefront.

- **Grid Model:** 12-column grid for desktop with 24px gutters.
- **Rhythm:** Spacing follows an 8px base unit. Larger gaps (48px-64px) are encouraged between major sections to allow the "grain" texture and photography to breathe.
- **Reflow:** On mobile, margins shrink to 16px. Lists that are horizontal on desktop (separated by `✶`) reflow into vertical bulleted lists for better thumb-targets.
- **Sidebar:** For utilitarian pages (Store Hours, Rentals), a 3-column left-hand sidebar is used for navigation and persistent shop metadata.

## Elevation & Depth

To maintain a "handcrafted" and tactile feel, this design system avoids heavy drop shadows and high-tech blurs.

- **Tonal Layers:** Depth is achieved through color. Containers use `paper-aged` against the darker `neutral_color_hex` page background.
- **Subtle Texture:** Rather than elevation, use "pressed" effects. Buttons and cards may have a 1px solid border in a slightly darker shade of the background color to give them a die-cut appearance.
- **Low-Contrast Outlines:** Use 1px borders in `slate-mountain` at low opacity (20%) to define sections without breaking the organic flow of the page.
- **Physical Metaphor:** Think of the UI as pieces of gear laid out on a wooden table. Elements should feel flat but material.

## Shapes

The shape language is **Soft and Structural**. 

- **Corners:** A 0.25rem (4px) radius is the standard for cards and inputs. This provides just enough softness to feel friendly while maintaining the "sturdy" brand promise.
- **Buttons:** Primary buttons use a slightly higher roundedness (8px) to distinguish them as interactive, tactile objects.
- **Dividers:** Horizontal rules are never a simple line. Use a repeating `* * * * *` glyph sequence or a faint woodgrain texture pattern to separate major page sections.

## Components

- **Buttons:** Solid `primary-color` backgrounds with `neutral` text. On hover, they shift to `amber-glow`. High-weight slab serif text for button labels.
- **Cards:** Background `paper-aged`, 1px `slate-mountain` border (low opacity). Use for equipment categories (e.g., "Hiking Gear").
- **Inputs:** Square-ish (4px radius) with a thick 2px bottom border in `slate-mountain` to mimic a traditional form.
- **Chips/Badges:** Used for brand names (e.g., "Burton", "Columbia"). Rounded-xl, light `slate-gray` background with dark forest text.
- **Dividers:** Use a custom "Heritage Divider" component consisting of the `~` character or a row of stars to separate the main content from the footer.
- **Product Lists:** Use the `✶` glyph to separate brand names in a running paragraph format to maximize space and maintain the "directory" aesthetic.