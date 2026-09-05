# Active Theory — Style Reference
> cosmic void with a single luminous portal — deep-space command deck where chrome whispers and the rendered world shouts

**Theme:** dark

Active Theory operates as a cosmic void stage where the immersive experience is the design and the UI chrome barely exists. The canvas is near-total black (#000000) with UI elements floating as whispered ghost containers — translucent surfaces, hairline borders, and pill-shaped controls that recede into the dark. Typography splits between an architectural geometric sans (nbarchitekt) for navigation and CTAs, and a deliberate editorial serif (Times) for body, creating an unexpected contrast that signals craft over convention. Color is rationed to a single muted violet accent (#343755) and pure white text — the page itself stays monochromatic so the rendered WebGL world carries all chromatic weight. Every UI decision prioritizes invisible-feeling chrome so the 3D scene reads as untethered floating in deep space.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Void Black | `#000000` | `--color-void-black` | Page canvas, immersive background, card surfaces when stacked on dark — the absence of surface, not a color |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text, icon strokes, high-contrast labels — used at full opacity against pure black |
| Ash Border | `#4d4d4d` | `--color-ash-border` | Card borders, divider hairlines — barely-there separator that defines edges without adding visual weight |
| Smoke | `#808080` | `--color-smoke` | Muted borders on ghost buttons, secondary chrome — recedes behind active controls |
| Fog | `#999999` | `--color-fog` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |
| Pale Mist | `#c6c6c6` | `--color-pale-mist` | Tertiary text, link default state, low-priority metadata — sits between white and gray for gentle hierarchy |
| Dusk Violet | `#343755` | `--color-dusk-violet` | Primary action fill — filled pill buttons, the only chromatic accent in the system; muted indigo reads as electric against void black without competing with the rendered scene |

## Tokens — Typography

### nbarchitekt — Navigation, button labels, micro-labels, and link text · `--font-nbarchitekt`
- **Substitute:** Space Grotesk, Inter, or any clean geometric sans with similar x-height proportions
- **Weights:** 400, 700
- **Sizes:** 10px, 12px, 14px
- **Line height:** 1.20, 1.50, 3.00
- **Letter spacing:** normal

### Times — Body copy, card descriptions, inline links · `--font-times`
- **Substitute:** Times New Roman, Georgia, or any editorial serif
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20, 1.88

### Arial — Cookie consent micro-copy · `--font-arial`
- **Substitute:** Any system sans
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20

### Type Scale
| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body-sm | 12px | 1.5 | — | `--text-body-sm` |
| body | 14px | 1.5 | — | `--text-body` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale
| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 28 | 28px | `--spacing-28` |

### Border Radius
| Element | Value |
|---------|-------|
| tags | 500px |
| cards | 12px |
| inputs | 5px |
| buttons-pill | 500px |
| buttons-ghost | 5px |

### Layout
- **Section gap:** 48px
- **Card padding:** 28px
- **Element gap:** 6px

## Surfaces
| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Void Canvas | `#000000` | Immersive WebGL background, the base layer for all rendered scenes |
| 1 | Translucent Overlay | `#00000080` | Cookie banner, modal scrims, tooltip panels |
| 2 | Dusk Violet Surface | `#343755` | Filled pill CTA, selected state surfaces |
| 3 | Frosted Glass | `#ffffff1a` | Ghost button fills |
