# Carry the Light

A small, meditative browser toy. Breathe gently into your phone's microphone to lift a balloon carrying a glowing memory from a dawn meadow, through open sky and twilight, up into the stars.

There are no scores, timers or ways to fail. When the balloon reaches the top, the memory leaves its harness and becomes a new star.

## Play

The whole experience is one file, `index.html`, with no build step and no asset files. All graphics and sounds are generated in the browser.

The microphone only works over HTTPS (or `localhost`). Enable GitHub Pages for this repository and open the Pages URL on your phone.

## Controls

- **Breath:** blow softly and steadily. Too little and the balloon drifts down. Too much and it sways and struggles.
- **Without a microphone:** press and hold anywhere, or hold the space bar. Hold with two fingers, or with Shift (or the B key), for a strong gust.
- **Sound:** the speaker icon in the top-right corner mutes the soundscape.

A short calibration runs after you tap Begin. It measures the room's background noise, then one gentle breath.

## Previewing a stage

Add an anchor to the URL to start partway through the journey:

| Anchor | Where you start |
|---|---|
| `#p25` | Open sky |
| `#p50` | High atmosphere |
| `#p72` | Twilight |
| `#p95` | Just below the stars |
