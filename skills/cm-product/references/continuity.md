# Final Consistency Check

Perform this check before the final Flow prompt.

## Character

Verify:
- same face/identity
- same hairstyle
- same age appearance
- same body type/proportions
- same wardrobe unless intentionally changed
- same accessories unless intentionally changed

## Product

Verify:
- same shape/proportions
- same materials/colors/finish
- same buttons/controls
- same display
- same logo/branding
- same distinctive design details

## Location

Verify:
- same architecture
- same layout
- same environment
- same furniture/major objects
- same materials/color palette
- same visual identity
- coherent time-of-day/lighting logic

## Story

Verify:
- correct sequence
- correct actions
- correct dialogue/voiceover
- correct product usage
- correct ending/brand message

## Visual style

Verify:
- consistent rendering style
- coherent camera language
- no unexplained wardrobe, prop, or environment changes
- no random style shifts

## Targeted correction rule

If one asset is inconsistent, correct only that asset. Preserve already-correct assets.

Examples:
- storyboard hairstyle error → edit/regenerate storyboard only
- location sheet accidentally contains storyboard panels → regenerate location sheet only
- product design changed in storyboard → correct storyboard only
