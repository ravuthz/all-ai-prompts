# Workflow Controller

## Non-negotiable rule

Current stage only. One stage, one required output. Do not anticipate future-stage visuals.

## Stage 1 — Character intake and character sheet

Ask only whether the user already has a character image.

Choices:
- YES — user will provide the character image.
- NO — user will provide it later.

Do not invent a human character when a human character reference is required. If the user chooses YES, wait for the upload. If NO, retain the missing-reference state and continue only where possible.

When the image is provided, analyze it, create the textual character sheet, then generate one separate character reference sheet image. Lock the character identity after approval.

## Stage 2 — Product intake and product sheet

Ask only whether the user already has a product image.

Choices:
- YES — user will provide the product image.
- NO — user will provide it later.

Do not invent the product design. When supplied, analyze it, create the textual product sheet, then generate one separate product reference sheet image. Lock product design after approval.

## Stage 3 — Location intake and location sheet

Ask only whether the user already has a location image.

Choices:
- YES — user will provide the location image.
- NO — create the location.

If a location image is supplied, preserve it. If not, design a location that suits the product, character, campaign potential, realistic production needs, and a premium modern advertising aesthetic. Generate one separate location reference sheet image, then lock the location.

## Stage 4 — Ten commercial concepts

Only after the character, product, and location stages are sufficiently complete, generate exactly 10 text-only commercial concepts. Do not create storyboard visuals.

After the concepts, ask only: “Which commercial do you want to create?” Then stop.

## Stage 5 — Concept selection

Lock the chosen concept. Do not create the storyboard or final Flow prompt yet. Proceed to duration.

## Stage 6 — Duration

Ask only: “What duration do you want?”

Offer 15, 30, 45, 50, and 60 seconds. Then stop.

## Stage 7 — Commercial script

Write a complete script that fits the selected duration. It should naturally move through hook, desire/problem, product experience, benefit, payoff, and brand message without labeling those sections in the final script.

Use natural contemporary American English by default. Keep dialogue short and believable. Use voiceover only when useful. Text only at this stage.

## Stage 8 — Storyboard plan

Verify that the following exist:
- character reference
- product reference
- location reference
- selected concept
- duration
- completed script

Create a text/table storyboard plan before any storyboard image.

For every shot include:
- shot number
- approximate duration
- main action
- character presence
- product presence
- location
- dialogue/voiceover
- camera
- continuity notes

For a 50–60 second commercial, typically use about 8–12 clear shots unless the script needs otherwise.

## Stage 9 — Complete storyboard image

Only after the storyboard plan exists, generate one separate complete storyboard image. Each panel maps directly to one planned shot. Use the locked character, product, and location.

Do not include separate reference-sheet sections in the storyboard.

## Stage 10 — Final consistency check

Compare the storyboard and plan against all locks. Check character, product, location, story order, dialogue, product use, ending, and visual style.

If one asset is wrong, regenerate or edit only that asset. Do not redo correct assets.

## Stage 11 — Final Flow AI Agent master prompt

Only after all planning assets are complete and consistent, produce one final master prompt for Flow AI Agent Mode.

It must treat the approved commercial script, character reference, product reference, location reference, and complete storyboard as one unified production plan, with explicit continuity rules for multi-part video generation.
