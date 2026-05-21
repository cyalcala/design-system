# Awwwards Pattern Cards

Date: 2026-05-21

## Purpose

Pattern cards turn Awwwards-style motion into reusable building blocks.

Each card answers:

- What is this effect?
- When should it be used?
- What input does it need?
- What stack fits?
- What can go wrong?
- How should it degrade on mobile?

## Card 1: Cinematic Hero Video Loop

Use when:

- The brand needs instant atmosphere.
- The product or service benefits from mood.

Needs:

- short loop
- poster image
- text-safe area
- mobile crop

Stack:

- HTML video + CSS
- GSAP only for overlays/reveals

Avoid:

- long videos
- fake UI inside the video
- unreadable text

Fallback:

- poster image
- reduced-motion static background

## Card 2: Scroll-Pinned Product Reveal

Use when:

- explaining a mechanism
- showing transformation
- guiding through features

Needs:

- 3 to 5 steps
- clear copy hierarchy
- visual state per step

Stack:

- GSAP ScrollTrigger

Avoid:

- more than one long pinned sequence
- trapping user scroll

Fallback:

- stacked cards on mobile

## Card 3: Clip-Path Portal Reveal

Use when:

- moving from mood to offer
- creating a dramatic section transition

Needs:

- strong geometric or organic shape language
- high-contrast scene change

Stack:

- GSAP + CSS clip-path

Avoid:

- overuse
- tiny mobile masks

Fallback:

- simple fade/slide reveal

## Card 4: Living Interface / Dashboard

Use when:

- selling SaaS
- showing technical sophistication
- making data feel alive

Needs:

- realistic UI content
- data/state logic
- readable labels

Stack:

- React
- GSAP or Framer Motion

Avoid:

- fake dashboard nonsense
- random blinking numbers

Fallback:

- static dashboard screenshot with subtle highlights

## Card 5: Text Reveal Sequence

Use when:

- copy is short and strong
- hierarchy matters
- opening needs rhythm

Needs:

- edited copy
- line breaks
- mask container

Stack:

- GSAP SplitText or custom line wrappers
- CSS masks

Avoid:

- long paragraphs
- delaying key information too much

Fallback:

- immediate visible text

## Card 6: 3D Hover Case Cards

Use when:

- showcasing work
- making cards feel tactile
- portfolio/agency site

Needs:

- strong images
- short labels
- pointer tracking

Stack:

- CSS transforms
- GSAP quickTo

Avoid:

- hover-only information
- heavy shadows everywhere

Fallback:

- static cards on touch devices

## Card 7: Scroll-Linked Video Journey

Use when:

- the whole page is a journey
- product transformation is visual
- narrative is stronger than static sections

Needs:

- optimized video frames
- poster
- mobile fallback
- reduced-motion fallback

Stack:

- GSAP ScrollTrigger
- canvas/video frame mapping

Avoid:

- huge uncompressed assets
- making all content dependent on scroll frame

Fallback:

- segmented still images

