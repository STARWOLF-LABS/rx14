# STARWOLF LABS // RX-14 v0.4 TRANSFER PROTOCOL

Field-tested mobile architecture.

## Active signal banks
- NEON N01 — SomaFM DEF CON Radio
- NEON N02 — SomaFM Suburbs of Goa
- NEON N03 — SomaFM Mission Control
- TEZETA C01 — Ethio Jazz Radio
- WORLD D01 — Radio Garden

## Offline / reserved
- GHOST — signal bank offline while a reliable mobile vintage-radio source is selected
- QUANTUM — signal bank offline while a reliable mobile ambient/new-age source is selected

## Transfer behavior
ACQUIRE SIGNAL no longer attempts internal audio playback. It performs the terminal sequence:

HANDSHAKE...
ROUTING AUDIO CARRIER...
SIGNAL ACQUIRED
STAND BY FOR TRANSFER

Then it transfers the current browser window to the selected station.

Upload/replace `index.html`, `stations.js`, `manifest.webmanifest`, and `README.md` in the existing `rx14` repository. `icon.svg` can remain untouched.
