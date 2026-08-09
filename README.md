# ASS — Runtime Fix

The stuck-at-000 bug was caused by a JavaScript ReferenceError:
`punchline` was referenced after the variable had been removed.

This build restores the variable and runtime-tests nonzero classifications before packaging.

Tested codes:
000, 100, 010, 001, 555, 919, 999.

Clicking Amount, Smell, or Sound now updates the three-digit code before rendering the result.
