# Recorded samples

The files in this folder are edited, trimmed, looped and packed versions of recordings from two public-domain sample libraries by Versilian Studios:

- **VS Chamber Orchestra: Community Edition (VSCO 2 CE)**, https://github.com/sgossner/VSCO-2-CE, recorded by Sam Gossner and Simon Dalzell, sample cutting by Elan Hickler (Soundemote). License: CC0 1.0 Universal.
  Used for: violin, viola and cello sections (sustain, spiccato, tremolo, pizzicato), solo violin, contrabass, harp, flute, oboe, clarinet, trumpet, French horn and tenor trombone (sustain and staccato), timpani.
- **Versilian Community Sample Library (VCSL)**, https://github.com/sgossner/VCSL. License: CC0 1.0 Universal.
  Used for: Steinway B grand piano (three velocity layers plus release samples), tenor saxophone, vibraphone, marimba, glockenspiel, xylophone, tubular bells, mbira, and the percussion bank (claps, hi-hat, shaker, tambourine, conga, bongos, cowbell, claves, woodblock, triangle, cymbals, gong, snare, tom, bass drum, darbuka, frame drum, cajon, cabasa, agogo, guiro, sleigh bells, mark tree).

CC0 places these recordings in the public domain: they can be used, changed and shared for any purpose, including commercial use, without asking permission. Credit is not required, but we give it gladly.

The samples are stored losslessly as FLAC (16-bit, 48 kHz, resampled from the 44.1/48 kHz originals with SoX-quality resampling and triangular dither). Each `.flac` holds the samples of one instrument (large instruments are split into numbered parts) back to back after a short sync click; `index.json` lists each sample's part, position, root note, velocity layer, round robin, tuning correction and loop points.
