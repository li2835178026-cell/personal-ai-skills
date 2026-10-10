---
name: motion-director
description: Direct code-generated educational motion videos with clear visual attention, narrative continuity, pacing, and factual fidelity. Use before writing Remotion/Three.js/Manim animation code and during preview review.
---

# Motion Director v0.1 — Experimental

## Principle
Motion must help a viewer understand, not merely decorate the screen. A technically elaborate animation is not necessarily good direction.

## Pre-code deliverable: Motion Board
Specify audience, learning objective, core visual motif, 3-second hook, timecoded shots, primary focal point per shot, action motivation, transitions, pauses, information revealed, and scientific/claim-check requirements. Prefer a recurring evolving visual motif over disconnected scenes where appropriate. Do not enforce this as a universal aesthetic.

## Direction checks
- Where should the eye look right now? One primary focal point per beat.
- Why does each element move? State its narrative or explanatory function.
- What carries attention from one shot to the next (shape, position, direction, motion, or meaning)?
- Where are anticipation, acceleration, breathing room, pause, and release?
- What can the viewer explain after the movement ends?
- Avoid random glow, particles, zooms, and transitions as substitutes for storytelling.
- Check readability on mobile and sound-off comprehension where relevant.

## Production workflow
1. Research and fact-check the central claim; flag uncertain science.
2. Draft the Motion Board and obtain direction approval before extensive code.
3. Build only a 15-second proof segment initially; reuse verified components.
4. Render low-cost previews and inspect actual motion, not only still frames.
5. Separate technical bugs (fix automatically) from aesthetic/direction changes (review deliberately).
6. Record iterations, time, quota/cost, and failure causes; avoid full rebuild for minor fixes.
7. Final render only after content and direction review.

## Evaluation rubric
Score each 1–5 with examples: attention guidance, visual continuity, rhythm, explanatory clarity, factual accuracy, mobile legibility. Compare baseline prompt vs director-enhanced prompt using same topic and runtime. Do not claim Opus-equivalent quality without blinded viewing and real rendered evidence.

## Initial test
15-second segment of “为什么你听自己的录音会觉得陌生？” Compare air conduction and body/bone conduction carefully; do not claim recorded sound is an absolute objective voice.
