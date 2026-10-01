# A.S.S. — V7 Native Audio + Fresh Icon URLs

This build deliberately avoids the two mechanisms that were failing on mobile.

## Audio
- No Web Audio API / AudioContext.
- Includes 10 real WAV files under /audio.
- Slider values 0–9 each play their own progressively higher 8-bit WAV.
- Audio elements are preloaded and primed from a direct touch/pointer gesture.

## Icons
- All previous icon files were removed.
- Every icon has a brand-new v7 filename to defeat browser/PWA icon caches.
- Fresh favicon ICO + 32/64 PNG.
- Fresh 180px Apple touch icon.
- Fresh 192/512 PWA icons.
- Fresh versioned manifest filename and start URL.

The V3 visual experience, 1,000-result database, special scores, and Transmit Score are preserved.
