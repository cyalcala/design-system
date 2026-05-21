# Awwwards Motion Pattern Taxonomy

Date: 2026-05-21

## Purpose

This taxonomy converts Awwwards-style references into reusable motion patterns.

The goal is to build original premium websites, not clones.

## Core Pattern Families

### 1. Scroll-Choreographed Storytelling

The page behaves like a directed sequence rather than a static document.

Use for:

- Product launches
- Founder stories
- Premium brand narratives
- Transformation journeys

Common techniques:

- ScrollTrigger timelines
- Pinned scenes
- Staggered reveals
- Scroll-linked progress
- Section-to-section continuity

Avoid when:

- Users need fast task completion
- Content is compliance-heavy
- Mobile performance is weak

### 2. Clip-Path and Mask Transitions

Shapes reveal or hide content in a cinematic way.

Use for:

- Hero transitions
- Scene changes
- Image-to-content reveals
- Brand portals/vaults/doorway metaphors

Risks:

- Can feel gimmicky
- Can hurt accessibility if content timing is unclear
- Needs mobile simplification

### 3. Cinematic Video Storytelling

Video becomes part of the interface rhythm.

Use for:

- High-end products
- Games/entertainment
- Agencies
- Fashion, wellness, creative brands

Rules:

- Provide poster image.
- Compress aggressively.
- Keep real UI as HTML.
- Provide reduced-motion fallback.
- Do not make video the only way to understand content.

### 4. Smooth Scroll and Inertia

Scroll has a premium physical feel.

Tools:

- GSAP ScrollSmoother
- Lenis
- Locomotive Scroll

Use carefully. Smooth scroll can make a site feel expensive, but it can also harm usability if it fights normal browser behavior.

### 5. Pinned Sections

The viewport holds while content changes around it.

Use for:

- Product walkthroughs
- Feature explanations
- Step-by-step transformations
- Scroll-controlled galleries

Avoid overuse. One or two strong pinned sequences usually beats five.

### 6. Parallax Layering

Foreground, midground, and background move at different speeds.

Use for:

- Cinematic depth
- Editorial hero sections
- Landscape/product atmosphere

Risk:

- Overdone parallax feels dated.
- Use subtle depth, not amusement-park motion.

### 7. Text Reveals

Text enters with timing and emphasis.

Patterns:

- Line reveal
- Word reveal
- Character reveal
- Masked upward reveal
- Blur-to-clear
- Scramble/terminal reveal

Rule:

Copy must be worth revealing. Never animate vague filler.

### 8. 3D Hover and Tilt

Cards, images, or panels respond to pointer movement.

Use for:

- Portfolios
- Case studies
- Product cards
- Feature panels

Fallback:

- Disable complex pointer motion on touch.
- Keep content readable without hover.

### 9. Page Transitions

Routes or sections transition as a continuous experience.

Use for:

- Multi-page portfolios
- Case studies
- Agency sites
- Product ecosystems

Risk:

- Can hide slow navigation.
- Needs focus management and accessibility care.

### 10. 3D / WebGL Scenes

Three.js or canvas creates immersive depth.

Use for:

- Creative portfolios
- Product showpieces
- Technical demos
- Worlds, islands, objects, portals

Rules:

- Have a static fallback.
- Keep loading state polished.
- Test canvas is nonblank.
- Avoid 3D when 2D would sell better.

### 11. Bento Motion Layouts

Dense visual modules animate as a system.

Use for:

- SaaS feature overviews
- dashboards
- AI/product pages
- social proof clusters

Risk:

- Can become generic quickly.
- Needs content specificity.

### 12. Scroll-Linked Video

Video frames are mapped to scroll progress.

Use for:

- Product transformation
- process reveal
- narrative journey
- premium hero moments

Risks:

- Heavy assets
- mobile complexity
- poor reduced-motion experience if not planned

## Motion Selection Rule

Pick one signature motion family and one or two support families.

Examples:

- Signature: scroll-linked video. Support: text reveals, subtle parallax.
- Signature: 3D scene. Support: simple fades, light hover.
- Signature: pinned product walkthrough. Support: bento micro-motion.

Avoid combining every Awwwards pattern in one site.

