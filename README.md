# Sonic Keystrokes

**A browser-based typing sonification tool — every keystroke plays a sample through a small signal chain, in-browser, offline, with no build step.**

Try it: https://github.com/AFre100/sonic-keystrokes/

Made by [Amnon Freidlin](https://megabloomstudio.com) — designer, sound designer, creative technologist.

---

## What it is

Sonic Keystrokes turns typing into a customizable audio feedback instrument. Each keystroke plays the selected sample through:

- ADSR envelope shaping
- 3-band EQ
- Convolution reverb (dry/wet)
- Master limiter

Per-hit micro-variation (pitch, timing, level, gentle formant shifts) keeps repeated keys from sounding mechanical. Samples are RMS-normalized on load so switching sounds doesn't jump in level.

**Drag in your own WAV or MP3 files (up to six) to remap the entire keyboard.**

Everything runs client-side. The Web Audio graph, the interface, and the base64-encoded audio samples all live in a single HTML file — open it and start typing.

## Origins

Sonic Keystrokes began as a research artifact — an exploration of how tactile audio feedback could support multimodal, immersive interaction inside enterprise AI product surfaces. It was designed as part of a broader design system exploration around how sound, gesture, and interaction feedback could work together to make agent-driven experiences feel more grounded and inhabited.

This is a portfolio-facing standalone version. The underlying signal chain, humanization model, and RMS normalization approach carry over from the original design context.

## Try it

- **Live:** [live URL here after Pages enabled]
- **Or download:** clone the repo, open `index.html` in any modern browser. No install, no build, no server.

## Credits

Concept · UI Design · Visual Design · Interaction Design · Prototyping · Front-End Code · Audio Engineering · Sound Design — [Amnon Freidlin](https://megabloomstudio.com)

## License

Code released under **PolyForm Noncommercial License 1.0.0** — free for personal use, education, research, and portfolios. Commercial use requires separate permission.

See [LICENSE](./LICENSE) for full terms.

The bundled audio samples have separate rights and are not covered by the code license.
