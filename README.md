# GL-8 Groovebox

The Grid Looper's drum kit and synths behind a hardware-style panel: 8 drum tracks,
Bass/Lead/Pad synths, an on-screen KEYS piano (3 octaves of a real 88-key range, a range bar to slide through it, EXPAND for big keys, and recorded pianos and electric pianos on the SOUND key, see `piano/LICENSES.md`) and round drum PADS that record into the loop (live, or a step at a time while stopped),
synth effects (echo, funk and space sets), 8 patterns, live record and Web MIDI out/in.
A SIMPLE key in the top strip hides everything but the sounds, keys or pads, tempo, REC/PLAY/STOP, UNDO and the ready-made LOOPS, for playing by ear.

Live: https://cwlorentz.github.io/groovebox/

Single-file web app (`index.html`), installable as a PWA (`manifest.webmanifest`,
network-first `sw.js`). Bump `VERSION` in `sw.js` when changing files.
Main looper: https://github.com/cwlorentz/midi-grid-looper
