# Stack Decisions

Pick the smallest stack that can execute the motion concept.

## Common Choices

| Goal | Recommended stack |
|---|---|
| One-page cinematic landing page | React + GSAP + Tailwind |
| SEO-heavy production site | Next.js + GSAP or Framer Motion |
| Component UI transitions | Framer Motion |
| Scroll storytelling | GSAP ScrollTrigger |
| Real 3D depth | Three.js / React Three Fiber |
| Lightweight smooth scroll | Lenis |
| Fundamentals learning | HTML/CSS/JS + GSAP |

## Rules

- Choose stack after choosing motion concept.
- Verify official docs before writing framework-specific code.
- Avoid multiple animation libraries unless each has a clear job.
- Plan mobile and reduced-motion fallbacks before implementation.

