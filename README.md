# A.S.S. — Atmospheric Severity System

Three 0–9 inputs:

- A — Amount
- S — Smell
- S — Sound

## 999 descriptive results

Every non-zero three-digit score from 001 through 999 has a unique, deterministic classification.
000 remains the special no-incident state.

The classifier is trait-aware rather than treating the score as a simple total:
- Amount changes the scale/payload language.
- Smell changes odor language.
- Sound changes acoustic language.
- Overall danger rises with the three values, with smell and amount weighted slightly more heavily.
- The dominant category changes the emphasis of the description.

Example:
919 = Amount 9, Smell 1, Sound 9 → huge and extremely loud, but only faintly smelly.

Shared output remains only:
three-digit code
emoji + classification
