# STARWOLF LABS // RX-14 v0.41 HOTFIX

Hotfix for v0.4.

v0.4 contained one orphaned JavaScript statement from the previous external-source handler.
That syntax error prevented the RX-14 boot sequence from running, leaving only the CRT background visible.

v0.41 removes the orphaned statement. Both `index.html` inline JavaScript and
`stations.js` were syntax-checked before packaging.

## Signal banks
- NEON: DEF CON Radio / Suburbs of Goa / Mission Control
- GHOST: offline / reserved
- TEZETA: Ethio Jazz Radio
- WORLD: Radio Garden
- QUANTUM: offline / reserved

## Transfer sequence
HANDSHAKE...
ROUTING AUDIO CARRIER...
SIGNAL ACQUIRED
STAND BY FOR TRANSFER

Replace the four files in the existing GitHub repository:
`index.html`, `stations.js`, `manifest.webmanifest`, `README.md`.
`icon.svg` stays untouched.
