# Piano recordings

GL-8's SOUND key plays these recordings. Each folder holds one note every 3 semitones
from A0 (21) to C8 (108), named by MIDI note number, trimmed and re-encoded as mono MP3.

## c5grand: Salamander Grand Piano V3 (Yamaha C5)

- Author: Alexander Holm
- License: CC BY 3.0, https://creativecommons.org/licenses/by/3.0/
- Source: https://archive.org/details/SalamanderGrandPianoV3 (velocity layer 8, via the
  `@audio-samples/piano-mp3-velocity8` npm package)
- Changes: trimmed to 7 s with a fade-out, mixed to mono, re-encoded at 64 kbps.
  HONKY-TONK plays these same files twice, detuned.

## bright, warm, cp, tine, fm, clav, harpsi: FluidR3 GM SoundFont

- FluidR3 SoundFont, Copyright (c) 2000-2002, 2008, 2013 Frank Wen
- License: MIT (below), via the `soundfont-for-samplers` npm package (MIT)
- Instruments: Bright Acoustic Piano (bright), Acoustic Grand Piano (warm), Electric Grand
  Piano (cp), Electric Piano 1 (tine), Electric Piano 2 (fm), Clavinet (clav), Harpsichord (harpsi)
- Changes: mixed to mono, faded out over the last 0.35 s, re-encoded at 48 kbps.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
