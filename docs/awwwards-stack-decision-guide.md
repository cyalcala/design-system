# Awwwards Stack Decision Guide

Date: 2026-05-21

## Purpose

Choose the right implementation stack for premium motion sites.

Do not pick tools because they look impressive. Pick the smallest stack that can execute the motion concept well.

## Default Stack

### React + GSAP + Tailwind

Best for:

- Cinematic landing pages
- Scroll-triggered storytelling
- Product launches
- One-page premium sites

Why:

- GSAP is mature for timeline choreography.
- Tailwind is fast for layout iteration.
- React componentizes complex sections.

Risks:

- Too much animation can hurt performance.
- GSAP code can become tangled without disciplined timelines.

## Modern GSAP Stack

### React 19 + Tailwind v4 + GSAP

Best for:

- Current tutorial/source alignment
- Modern front-end experiments
- Teams comfortable with newest React/Tailwind changes

Use when:

- The project can tolerate current-stack changes.
- You verify package docs before implementation.

## Next.js + GSAP

Best for:

- Production landing pages
- SEO-sensitive projects
- Multi-page marketing sites
- Vercel deployment

Watch for:

- Client-only animation boundaries
- hydration issues
- route transitions
- bundle weight

## Next.js + Framer Motion

Best for:

- UI transitions
- page transitions
- component-level animation
- editorial motion

Less ideal for:

- highly choreographed scroll timelines
- complex pinned sequences
- scroll-linked video

## Framer Motion + Canvas

Best for:

- Furrow-style creative rebuilds
- tactile interactive effects
- canvas-supported artistry

Risk:

- More custom engineering.
- Fewer reusable marketing-site patterns.

## Three.js / React Three Fiber

Best for:

- 3D hero scenes
- immersive portfolios
- product objects
- interactive worlds

Use only when 3D is the concept, not decoration.

Requirements:

- loading state
- static fallback
- mobile performance plan
- canvas pixel verification

## Smooth Scroll Choices

### Native Scroll

Use for:

- most client sites
- accessibility-sensitive sites
- content-heavy pages

### Lenis

Use for:

- lightweight premium smooth scroll
- modern creative sites
- better scroll feel without a huge abstraction

### GSAP ScrollSmoother

Use for:

- GSAP-heavy sites
- integrated scroll animation systems

Check licensing and plugin requirements before production use.

### Locomotive Scroll

Use for:

- studying older Awwwards-style builds
- inertia scroll references

Be careful:

- It can complicate accessibility and modern framework behavior.
- Do not default to it for new production work.

## Plain HTML/CSS/JS

Best for:

- learning fundamentals
- small static prototypes
- simple portfolio experiments

Why:

- Removes framework noise.
- Makes animation mechanics visible.

## Decision Table

| Goal | Recommended stack |
|---|---|
| One-page cinematic landing page | React + GSAP + Tailwind |
| SEO-heavy production site | Next.js + GSAP or Framer Motion |
| Component UI transitions | Framer Motion |
| Scroll storytelling | GSAP ScrollTrigger |
| Real 3D depth | Three.js / React Three Fiber |
| Lightweight premium scroll feel | Lenis |
| Fundamentals learning | HTML/CSS/JS + GSAP |

## Stack Discipline

- Choose the stack after choosing the motion concept.
- Verify official docs before coding.
- Avoid using multiple animation libraries unless each has a clear job.
- Plan mobile and reduced-motion behavior before implementation.

