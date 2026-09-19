# SHOT REGISTRY — THE BREACH

The shot registry is the production execution layer.

## Record schema
Every shot record must contain:
- SHOT_ID
- sequence
- story function
- location/environment ID
- character state IDs
- prop IDs
- IN_STATE
- ACTION
- OUT_STATE
- camera/screen direction notes
- dialogue/audio
- production method
- reference requirements
- continuity dependencies
- risk class
- status

## Status vocabulary
DRAFT -> READY_FOR_REF -> REF_LOCKED -> READY_FOR_ANIMATION -> GENERATED -> QC_REVIEW -> LOCKED

## Risk
- A: still/composite/insert or low identity risk
- B: controlled single/dual-character animation
- C: complex anatomy, multi-character interaction, action, silk, transformation, or critical raccord

## Source integrity
A shot may only be marked READY_FOR_REF when its story content is supported by the locked storyboard/canon. Unknown details are marked TODO/AUDIT, never invented.
