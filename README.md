# A.S.S. — V5 Audio Fix

The synthwave V3 experience with mobile-safe 8-bit slider audio.

Audio changes:
- AudioContext is created/resumed directly on pointer/touch/mouse/keyboard interaction
- Output is primed during the user gesture for iOS/Safari autoplay restrictions
- Slider movement then plays a louder 8-bit oscillator tone
- Pitch rises clearly from 0 through 9
- Amount, Smell, and Sound retain distinct chip-style voices
- No external audio files and no extra UI controls
