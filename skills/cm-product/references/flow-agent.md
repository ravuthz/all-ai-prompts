# Final Flow AI Agent Prompt Rules

The final prompt must instruct the video-generation agent to treat these as authoritative references:

1. approved commercial script
2. approved character reference image
3. approved product reference image
4. approved location reference image
5. approved complete storyboard image

These form one unified production plan.

## Reference priority

When minor conflicts appear:
- character appearance → character reference wins
- product physical design → product reference wins
- location physical design → location reference wins
- story order/action → storyboard plan + script win

## Required instructions

The final master prompt should explicitly cover:
- project title and duration
- format and target audience
- character lock
- product lock
- location lock
- global visual direction
- shot-by-shot execution
- audio/music/SFX
- dialogue/voiceover
- readable screen text
- multi-part clip continuity
- physical/object continuity
- product-claim guardrails
- quality-control checklist
- final brand objective

## Multi-part continuity

When video is generated in multiple clips, every new clip must be compared against the references and the previous clip.

Preserve:
- face and hair
- clothing/accessories
- body proportions
- product design and product position
- location/environment
- lighting direction
- time progression
- story state
- prop state and hand continuity where practical

The finished commercial should look like one production, not unrelated clips stitched together.

## Animals

If animals appear, keep them visually consistent across shots. Do not assign human speech unless the user explicitly requests a stylized talking-animal concept.
