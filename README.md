# Wes Portfolio V2

Interactive monochrome metaball / SDF composition with a Gray-Scott reaction-diffusion background, sci-fi WebAudio, and an oscilloscope — the portfolio's hero, work grid, capabilities and contact flow live inside it.

Live: https://hindsightvisuals.github.io/wes-portfolio-v2/

Single self-contained page: open `index.html` in a browser (no build step). GSAP and Lenis load from CDNs; Loos comes from a Typekit kit that only serves on hindsightvisuals.github.io, so local runs fall back to Krona One.

## Controls

- **Move** — cursor attracts/repels the goo; bass drone modulates near centre
- **Click** — pluck, shockwave, chromatic-aberration flash, RD bloom, layout morph (the first click also wakes the audio)
- **Scroll** — sections morph the layout; echoing clicks as you go
- **Nav** — Work / Capabilities / About; the emblem opens the contact page, where typing grows the goo
- **HUD** — dot slider, invert / orbit / mute switches, joystick (pushes the field, or tilts the camera in orbit mode)
- **M** — mirror · **I** — invert · **Space** — morph · **D** — debug panel

## URL flags

- `?contact` — open on the contact page
- `?nomail` — demo the send takeover without opening a mail draft
- `?layout=N` — start in formation N
- `?debug` — show the debug panel
