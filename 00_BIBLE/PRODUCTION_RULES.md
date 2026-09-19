# PRODUCTION RULES

## Core rule
**SHOT != PROMPT.**

Every shot is a controlled production unit with:
- SHOT_ID
- script intent
- IN state
- action
- OUT state
- character state IDs
- environment ID
- prop IDs
- camera and screen direction
- lighting/time state
- audio/dialogue
- production method
- dependencies
- reference frames
- version
- validation status

## Continuity chain
For continuous action:
1. define F_IN;
2. define key action;
3. validate F_OUT;
4. use validated F_OUT as the next shot's F_IN reference where appropriate.

Never regenerate a validated identity/state merely for variety.

## Production methods
Each shot must be assigned deliberately:
- I2V
- T2V
- still + camera motion
- compositing
- lip-sync
- FX pass
- multi-pass combination

Do not force one workflow onto the whole film.

## Text and screens
Legible terminal text, timestamps, labels and surveillance overlays are added in compositing unless a locked method proves reliable. Do not rely on a generative video model for critical typography.

## Cost gate
Complex multi-character/action shots are produced only after their character, environment and prop references pass QC.

## Hard-fail examples
- E*NKI heterochromia reversed.
- E*NKI iconic outfit appearing before acquisition.
- U*TTU wrong limb count.
- U*TTU silk represented as magic.
- N*ABU receiving techwear prematurely.
- G*BOY represented as a fox.
- VIAL-V1 confused with BOTTLE-H1.
- Required carried prop disappearing without an explicit action.
- Geography or screen direction changing without a motivated transition.
- Final open door rendered closed.
- Post-credit containment subject revealed.

## Validation statuses
DRAFT -> READY_FOR_REF -> REF_LOCKED -> READY_FOR_ANIMATION -> GENERATED -> QC_REVIEW -> LOCKED

Only LOCKED material may be treated as final continuity reference.
