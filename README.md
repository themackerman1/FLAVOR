# A.S.S. — V9 Low-Latency Audio

- WAV files remain at repository root for reliable GitHub Pages deployment.
- WAVs are fetched and decoded once after the first user interaction.
- Slider playback uses in-memory Web Audio AudioBuffers rather than HTML Audio seek/play.
- AudioContext requests interactive latency.
- Duplicate rapid events at the same slider value are suppressed.
- No audio subfolder.
- V7 icon/favicon assets remain unchanged.
