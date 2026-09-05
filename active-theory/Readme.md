# 🌌 Active Theory — Cosmic Void Website

> An immersive, cinematic studio website concept inspired by the visual language of Active Theory, combining experimental WebGL, minimal ghost UI, atmospheric motion, and interactive storytelling.

## 🔗 Live Demo

🚀 **[View Live Website](YOUR_LIVE_DEMO_URL_HERE)**

---

## ✦ Project Overview

The **Active Theory Cosmic Void Website** is a cinematic interactive website concept created in strict accordance with the **Active Theory — Style Reference** and approved implementation plan.

The experience combines:

- Immersive WebGL visuals
- Three.js-powered cosmic environments
- Minimal ghost UI
- Interactive case studies
- Procedural ambient audio
- Atmospheric particle systems
- Responsive interactive controls
- Experimental digital-art direction

The goal was to create a website that feels less like a traditional landing page and more like an **interactive digital environment**.

---

# 🎨 Design System

The interface follows a strict visual system defined by the project design reference.

### Color Palette

| Token | Color |
|---|---|
| Void Black | `#000000` |
| Ghost White | `#ffffff` |
| Ash Border | `#4d4d4d` |
| Smoke | `#808080` |
| Fog | `#999999` |
| Pale Mist | `#c6c6c6` |
| Dusk Violet | `#343755` |

### Visual Principles

- Zero traditional drop shadows
- Translucent UI layers
- `backdrop-filter: blur(4px)`
- Minimal borders
- High-contrast black-and-white interface
- Controlled use of violet and chromatic color
- Experimental atmospheric visuals

### Border Radius

The interface uses a deliberately restricted radius system:

- `5px` — Inputs and ghost buttons
- `12px` — Cards and banners
- `500px` — Pills and tags

---

# 🔤 Typography

The typography system uses three distinct styles.

### Geometric Sans

Used for:

- Navigation
- Buttons
- UI chrome
- Micro-telemetry
- Interface labels

Primary reference:

**Space Grotesk**, matching the geometric character of `nbarchitekt`.

### Classical Serif

Used for:

- Body copy
- Narrative content
- Descriptions
- Case-study storytelling

Reference:

**Times / Times New Roman**

Base size:

`16px`

Line height:

`1.88`

### Utilitarian Sans

Used for:

- Legal information
- Compliance text
- Micro-copy

Reference:

**Arial**

Size:

`13px`

---

# 🌌 WebGL Cosmic Experience

The core visual experience is powered by **Three.js WebGL**.

### Circular Wireframe Portal

A torus-based circular portal creates the primary visual centerpiece.

Features include:

- Dynamic cyan-to-magenta gradient rim
- Dashed outer orbit ring
- Rotating geometry
- Atmospheric glow

### Geometric Mark Core

The center of the portal contains rotating geometric wireframes:

- Octahedron
- Icosahedron
- Multi-axis rotation
- Counter-rotating geometry
- Subtle rhythmic breathing animation

### Particle Fountain

The portal generates a gravitational particle field containing approximately:

**1,600 particles**

Particle colors include:

- Green
- Gold
- Cyan
- White

The particles cascade downward from the portal aperture in a gravitational-style animation.

### Aurora Bleed

A deep atmospheric radial wash emerges from the upper-left area of the scene.

The animation uses a slow:

**9-second breathing cycle**

to create an ambient, constantly evolving environment.

### Gravitational Mouse Interaction

The cosmic scene responds to cursor movement.

Mouse interaction influences:

- Portal tilt
- Particle-field direction
- Celestial positioning
- Overall scene movement

---

# 👻 Interactive Ghost UI

The interface uses a minimal **Ghost UI** system to keep the experience immersive without visually competing with the WebGL environment.

## Navigation

The top-right navigation contains:

- Ghost navigation buttons
- 2px hairline borders
- Uppercase geometric typography
- Spatial divider dots
- Audio control

### Audio Toggle

The audio control activates a procedural cosmic ambient synthesizer created using the:

**Web Audio API**

---

# 🎯 Hero Experience

The hero overlay provides minimal interface information around the central cosmic scene.

It includes:

- Brand telemetry
- Coordinate indicators
- Atmospheric micro-copy
- Primary CTA
- Interactive visual centerpiece

The primary CTA uses:

**Dusk Violet — `#343755`**

with a pill-style interface.

---

# 📂 Case Study Archive

The **Work Drawer** provides access to the project's case-study archive.

The drawer features:

- Translucent interface layers
- Ghost Cards
- 1px Ash Borders
- 12px corner radius
- 28px internal card padding
- Pill-shaped tags
- Hairline link indicators

### Typography

Case-study titles:

**14px bold geometric sans**

Descriptions:

**16px Times serif**

Line height:

**1.88**

---

# 🔍 Interactive Deep-Dive

The **Project Modal** provides a detailed case-study experience.

The modal includes:

- Architecture philosophy
- Project information
- Telemetry metrics
- Engine specifications
- Detailed project content

This allows users to explore the project without leaving the main experience.

---

# 🍪 Cookie Experience

A translucent cookie banner is included as part of the interface system.

The banner uses:

- `rgba(0,0,0,0.5)`
- `backdrop-filter: blur(4px)`
- 12px radius
- 16px top padding
- 28px horizontal padding
- 32px bottom padding

Typography combines:

- Times serif for primary copy
- Arial for compliance micro-copy

The acknowledgement control uses the project's Dusk Violet accent.

---

# 📡 Studio & Contact Experience

The project also includes two immersive information experiences.

### Studio Manifesto

The **About Modal** presents the studio's core philosophy and manifesto.

### Transmission Deck

The **Contact Modal** provides an interactive communication experience designed around the project's encrypted-transmission aesthetic.

---

# 🧩 Project Structure

```text
active-theory/
│
├── src/
│   ├── components/
│   │   ├── WebGLCanvas.tsx
│   │   ├── Navigation.tsx
│   │   ├── HeroOverlay.tsx
│   │   ├── WorkDrawer.tsx
│   │   ├── ProjectModal.tsx
│   │   ├── CookieBanner.tsx
│   │   ├── AboutModal.tsx
│   │   └── ContactModal.tsx
│   │
│   └── index.css
│
├── dist/
│
├── design.md
├── index.html
├── index.standalone.html
├── package.json
├── package-lock.json
├── tsconfig.json
└── vite.config.ts
