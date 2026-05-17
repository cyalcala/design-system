# Transcript Methodology Extraction

Date: 2026-05-17

This document captures the reusable methods extracted from the supplied video transcripts. It intentionally preserves methodology, not exact creative identity.

## Source Method 1: Image Reference to Animated Hero to Codex

Core method:

1. Generate a visually distinctive hero reference image.
2. Generate a matching mobile breakpoint early.
3. Remove baked-in buttons from the image.
4. Animate desktop and mobile versions as subtle hero videos.
5. Save assets in the same project folder Codex will use.
6. Give Codex paths to image references and hero videos.
7. Ask Codex to create a design spec from the references.
8. Build the rest of the page to match the hero's world.

Best insight:

The hero is the art-direction seed for the whole site.

Risk:

The result can become a wallpaper site if business logic, copy, and real UI are weak.

System fix:

Separate cinematic assets from real interface elements.

## Source Method 2: Infinite Canvas Variant Lab

Core method:

1. Use a canvas to view multiple design outputs at once.
2. Generate an initial page.
3. Ask for variants with different hero or component strategies.
4. Annotate, edit, and select components visually.
5. Use generated assets such as logos or background images.
6. Bring in external component references for specific sections.
7. Export or run selected designs locally.

Best insight:

Premium design improves through visible comparison, not isolated prompting.

Risk:

Too many variants can dilute the art direction.

System fix:

Variant only high-leverage sections.

## Source Method 3: Open Design

Core method:

1. Use local-first design tooling.
2. Choose an agent and model.
3. Choose or create a design system.
4. Use skills for different output types.
5. Ask context questions before generating.
6. Preview responsive views.
7. Export the design package.

Best insight:

Design systems and skills reduce dependence on raw model taste.

Risk:

The user may need enough design vocabulary to choose a direction.

System fix:

Add premium mode selection and anti-reference prompts before design system choice.

## Source Method 4: Visual Composition System, Not Website Template

Core method:

1. Prompt for a 16:9 website design reference that avoids conventional hero layout.
2. Generate a clean background art plate without UI.
3. Give Codex both the reference and clean background.
4. Ask for visual analysis and implementation.
5. Run a fidelity pass for composition, hierarchy, spacing, typography, and responsiveness.
6. Animate the background.
7. Extract an art bible.
8. Build the rest of the landing page from that art bible.

Best insight:

The key prompt shift is from "website template" to "visual composition system."

Risk:

Without an art bible, later sections drift away from the hero.

System fix:

Make art bible extraction mandatory before page expansion.

## Source Method 5: Impeccable Anti-Slop Workflow

Core method:

1. Use design knowledge references for typography, color, spatial design, responsiveness, interaction, motion, and UX writing.
2. Detect AI slop patterns.
3. Critique and audit the design.
4. Apply targeted fixes: clarify, distill, layout, quiet, harden, polish.
5. Generate multiple lightweight design options.
6. Use tweak panels or adjustable controls for final taste tuning.

Best insight:

Anti-slop is not optional. It is a design QA stage.

Risk:

Over-minimizing can remove personality.

System fix:

Use anti-slop to remove generic patterns while preserving the chosen premium mode.

## Source Method 6: Claude Design Scroll Journey and Deployment Workflow

Core method:

1. Start from existing site or new idea.
2. Generate brand positioning and hero copy.
3. Generate image/video prompts for hero background.
4. Use a short, subtle looping video.
5. Bring assets into a design tool.
6. Sketch rough layout when helpful.
7. Let the tool create high-fidelity prototype and design system.
8. Use comments, drawing, inline edits, and tweak panels.
9. Export project to code.
10. Run locally, push to GitHub, deploy to Vercel.
11. Check mobile before shipping.

Best insight:

Scroll journeys can turn static content into a memorable narrative.

Risk:

Usage limits and long context can cause waste and drift.

System fix:

Use one visual dimension per prompt, export fresh context when needed, and keep a build packet as the source of truth.

## Combined Method

The strongest integrated workflow is:

1. Brand diagnosis
2. Premium mode
3. Anti-reference list
4. Visual composition seed
5. Desktop/mobile asset split
6. Motion plan
7. Art bible / `DESIGN.md`
8. Section storyboard
9. Variant lab for high-value sections
10. Signature moment
11. One-shot build packet
12. Anti-slop and premium QA

