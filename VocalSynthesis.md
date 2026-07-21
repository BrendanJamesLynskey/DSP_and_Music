# Vocal Synthesis

[← Back to DSP & Music](README.md)

A dedicated hub exploring how the **singing voice** itself is synthesized — a
historically-complete survey from the earliest mechanical speaking machines to
modern neural methods. An interactive **explorer** lets you A/B every technique
on the same note and vowel; a companion [`HISTORY.md`](https://github.com/BrendanJamesLynskey/Vocal_Synthesis/blob/main/HISTORY.md)
tells the full story. All techniques share one interchangeable library
(`vocal-voices.js`) that also powers the sung early-music apps.

**[Vocal Synthesis explorer & history](https://github.com/BrendanJamesLynskey/Vocal_Synthesis)** — [launch the app](https://brendanjameslynskey.github.io/Vocal_Synthesis/)

The flagship voice is a **real sampled choir** — actual recorded sung vowels ([VocalSet](https://zenodo.org/records/1193957), CC BY 4.0), looped and pitch-mapped with formant preservation. Alongside it, **eight pure-synthesis techniques** run live in the browser, spanning the timeline:

| Era | Technique | Milestone |
|-----|-----------|-----------|
| 1939 | **Channel vocoder / VODER** | Dudley's buzz+hiss through a filter bank (Bell Labs) |
| 1953–80 | **Formant synthesis** (parallel + **Klatt** cascade) | PAT/OVE; the Klatt synth behind DECtalk |
| 1961–62 | **Kelly–Lochbaum vocal tract** | the first singing computer — "Daisy Bell" |
| 1971–78 | **LPC** (all-pole) | Speak & Spell |
| 1979–84 | **FOF / CHANT** | IRCAM's formant-wave-function synthetic choir |
| 1986–90 | **Additive / sinusoidal** | McAulay–Quatieri, SMS |
| 2020 | **DDSP-style harmonic + noise** | the differentiable-DSP bridge to the neural era |

The **sampled voice** now brings the concatenative / **PSOLA** path live (real recorded units, formant-preserving pitch-shift). Still described in the history only (need larger corpora or trained models): MBROLA, VOCALOID, STRAIGHT/WORLD, HMM synthesis, and the neural stack (WaveNet, Tacotron, HiFi-GAN, DiffSinger).
