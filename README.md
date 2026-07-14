# DSP & Music

A collection of projects exploring digital signal processing, synthesis, and music — from interactive browser-based synthesizers to visual guides on transform theory.

---

## Synthesizers

| Project | Description |
|---------|-------------|
| [Synth Additive](https://github.com/BrendanJamesLynskey/Synth_Additive) | Web-based additive synthesizer — 32 partials, 40+ presets, real-time harmonic editor |
| [Synth Physical Modelling](https://github.com/BrendanJamesLynskey/Synth_Physical_Modelling) | Karplus-Strong, waveguides, and modal synthesis — 5 models, 30+ presets, desktop & mobile |
| [Synth Granular](https://github.com/BrendanJamesLynskey/Synth_Granular) | Granular texture engine — hundreds of micro-grains, 6 source types, audio-reactive WebGL visuals |
| [Synth Orthodox](https://github.com/BrendanJamesLynskey/Synth_Orthodox) | Byzantine Orthodox chant synthesizer — 8 Echoi modes, ison drone, cathedral reverb, pure sine tones |
| [Synth Modular](https://github.com/BrendanJamesLynskey/Synth_Modular) | Fully-featured modular web synthesizer — dual oscillators, multi-mode filter, LFO, effects chain |
| [Synth Spectralist](https://github.com/BrendanJamesLynskey/Synth_Spectralist) | Generative ambient synthesizer — evolving spectral textures, drifting harmony, audio-reactive visuals |
| [Synth FM](https://github.com/BrendanJamesLynskey/Synth_FM) | Browser-based FM synthesizer — 2-operator and 4-operator (DX7-style) with 8 algorithms, ADSR envelopes, 20+ presets, polyphonic keyboard |

## Early Western Music

A themed set of browser synthesizers that trace the birth of Western music —
from the unison chant of the early Church to the polyphony of the Gothic
cathedrals and the secular song and dance of the medieval courts. Each app
recreates one style in real time, **voiced as it was historically performed** —
sung with **formant vocal synthesis** where voices were used (chant, organum,
the sung motet, troubadour song), and played with instrumental synthesis where
instruments were (the subtractive vielle drone, the physically-modelled dance
band). Each carries an in-app description of its style and how it relates to the others.

**The lineage.** Everything begins with unaccompanied plainchant. Add a second
voice to chant and you get *organum*; discipline those voices with rhythm and
you reach the *Ars Nova*. Running alongside the sacred line is a secular,
vernacular branch — the monophonic songs of the *troubadours*, which fed the
instrumental *estampie* dances:

```
 SACRED     Plainsong ──► Organum ──► Ars Nova ──► (Renaissance polyphony)
 (chant → polyphony)   add a 2nd    rhythmic
                        voice        independence

 SECULAR    Troubadour song ──► Estampie (instrumental dance)
 (vernacular monophony → dance)
```

| Project | Style · Era | Voicing &amp; synthesis technique |
|---------|-------------|---------------------|
| [Synth Gregorian](https://github.com/BrendanJamesLynskey/Synth_Gregorian) | Plainsong / Gregorian chant · 9th–10th c. | Sung — **formant vocal synthesis** (glottal pulse through resonant vowel formants) |
| [Synth Organum](https://github.com/BrendanJamesLynskey/Synth_Organum) | Notre-Dame polyphony (Léonin, Pérotin) · c. 1160–1250 | Sung — **FOF vocal synthesis** (formant-wave-function, the CHANT method) in **Pythagorean just intonation**; beatless consonances |
| [Synth Ars Nova](https://github.com/BrendanJamesLynskey/Synth_ArsNova) | 14th-c. isorhythmic polyphony (Machaut) · 14th c. | Sung upper voices + instrumental tenor — **formant vocal synthesis** with an isorhythmic *talea/color* engine |
| [Synth Troubadour](https://github.com/BrendanJamesLynskey/Synth_Troubadour) | Troubadour / trouvère secular song · 12th–13th c. | Sung melody — **formant vocal synthesis** over a **subtractive**-synth vielle drone |
| [Synth Estampie](https://github.com/BrendanJamesLynskey/Synth_Estampie) | Medieval instrumental dance · 13th–14th c. | Instrumental — **physical modelling** (Karplus–Strong strings over a hurdy-gurdy drone) |

## Vocal Synthesis

A dedicated hub exploring how the **singing voice** itself is synthesized — a
historically-complete survey from the earliest mechanical speaking machines to
modern neural methods. An interactive **explorer** lets you A/B every technique
on the same note and vowel; a companion [`HISTORY.md`](https://github.com/BrendanJamesLynskey/Vocal_Synthesis/blob/main/HISTORY.md)
tells the full story. All techniques share one interchangeable library
(`vocal-voices.js`) that also powers the sung early-music apps above.

**[Vocal Synthesis explorer & history](https://github.com/BrendanJamesLynskey/Vocal_Synthesis)** — [launch the app](https://brendanjameslynskey.github.io/Vocal_Synthesis/)

Eight techniques run live in the browser (sample-free, dependency-free), spanning the timeline:

| Era | Technique | Milestone |
|-----|-----------|-----------|
| 1939 | **Channel vocoder / VODER** | Dudley's buzz+hiss through a filter bank (Bell Labs) |
| 1953–80 | **Formant synthesis** (parallel + **Klatt** cascade) | PAT/OVE; the Klatt synth behind DECtalk |
| 1961–62 | **Kelly–Lochbaum vocal tract** | the first singing computer — "Daisy Bell" |
| 1971–78 | **LPC** (all-pole) | Speak & Spell |
| 1979–84 | **FOF / CHANT** | IRCAM's formant-wave-function synthetic choir |
| 1986–90 | **Additive / sinusoidal** | McAulay–Quatieri, SMS |
| 2020 | **DDSP-style harmonic + noise** | the differentiable-DSP bridge to the neural era |

Described in the history (need samples or trained models): PSOLA/MBROLA, VOCALOID, STRAIGHT/WORLD, HMM synthesis, and the neural stack (WaveNet, Tacotron, HiFi-GAN, DiffSinger).

## Analysis & Effects

| Project | Description |
|---------|-------------|
| [Audio Analyser](https://github.com/BrendanJamesLynskey/Audio_Analyser) | Real-time audio spectral analyser — STFT, CWT, DWT, and Constant-Q analysis in the browser |
| [Phase Vocoder](https://github.com/BrendanJamesLynskey/PhaseVocoder) | Three implementations of the phase vocoder for time-stretch and pitch-shift (Python, Windows) |
| [Musical Time-Stretching & Pitch-Shifting](https://github.com/BrendanJamesLynskey/MusicalTimeStretchingPitchShifting) | Interactive presentation covering the history and mathematics from 1940s tape splicing to neural synthesis |
| [Counterpoint](https://github.com/BrendanJamesLynskey/Counterpoint) | Browser-based counterpoint music generator and player with real-time harmonic analysis |
| [DAFX Python3](https://github.com/BrendanJamesLynskey/DAFX_Python3) | Python 3 ports of the MATLAB scripts from *DAFX: Digital Audio Effects* (2nd edition) |
| [Vocoder](https://github.com/BrendanJamesLynskey/Vocoder) | Channel vocoder — 8-32 band filter bank, envelope followers, multiple carrier types (sawtooth, noise, chord), real-time mic processing |
| [Room Acoustics & Reverb](https://github.com/BrendanJamesLynskey/Room_Acoustics_Reverb) | 2D ray-tracing room simulator, Schroeder algorithmic reverb designer, impulse response display, RT60 and acoustic metrics |
| [Spatial Audio & Ambisonics](https://github.com/BrendanJamesLynskey/Spatial_Audio_Ambisonics) | HRTF binaural panner, first-order Ambisonics encoder/decoder, VBAP speaker configurations, sound field visualisation |

## Audio Plugins

A hub-and-spoke set on **audio plugins** — the software modules (EQs, compressors,
reverbs, synthesisers) that shape almost every recorded sound. A central presentation
covers the history, the plugin formats, the types commonly built, and the frameworks; an
in-depth **JUCE** tutorial builds a real plugin from an empty folder; and seven example
plugins each pair a **live, playable browser demo** — real hand-written DSP running in the
Web Audio API — with the equivalent **JUCE C++**.

| Project | Description |
|---------|-------------|
| [Audio Plugins](https://github.com/BrendanJamesLynskey/Audio_Plugins) | The hub — history (Sound Tools → VST 1996 → AU → RTAS/AAX → VST3 → CLAP 2022), formats (VST3, AU/AUv3, AAX, CLAP, LV2), the types commonly built, plugin anatomy and the real-time audio contract, and the frameworks (JUCE, iPlug2, DPF, nih-plug, Faust, RNBO), with live in-browser audio |
| [JUCE Tutorial](https://github.com/BrendanJamesLynskey/JUCE_Tutorial) | In-depth build-from-nothing JUCE tutorial — CMake project, `AudioProcessor` lifecycle, `AudioProcessorValueTreeState` parameters, `processBlock` and the `dsp` module, editor and custom `LookAndFeel`, MIDI and the `Synthesiser` class, state/presets, validation and packaging; interactive zipper-noise demo |
| [Plugin Example — EQ](https://github.com/BrendanJamesLynskey/Plugin_Example_EQ) | Parametric equaliser — six hand-written RBJ-cookbook biquads, draggable frequency-response curve, live spectrum analyser; JUCE `dsp::IIR` listing |
| [Plugin Example — Compressor](https://github.com/BrendanJamesLynskey/Plugin_Example_Compressor) | Feed-forward dynamics — envelope detector, soft-knee gain computer, attack/release ballistics, gain-reduction metering, parallel mix; hand-rolled JUCE `processBlock` |
| [Plugin Example — Reverb](https://github.com/BrendanJamesLynskey/Plugin_Example_Reverb) | Algorithmic reverb — a Freeverb 8-comb/4-allpass network, measured impulse response, energy-decay curve and RT60; JUCE `dsp::Reverb` and convolution |
| [Plugin Example — Delay](https://github.com/BrendanJamesLynskey/Plugin_Example_Delay) | Delay / echo — interpolated circular-buffer delay line, filtered feedback, ping-pong, tempo sync, tape-wobble modulation; JUCE `dsp::DelayLine` |
| [Plugin Example — Distortion](https://github.com/BrendanJamesLynskey/Plugin_Example_Distortion) | Distortion / saturation — five waveshapers, Chebyshev harmonic generation, aliasing and an oversampling A/B; JUCE `dsp::Oversampling` and `WaveShaper` |
| [Plugin Example — Modulation](https://github.com/BrendanJamesLynskey/Plugin_Example_Modulation) | Chorus, flanger and phaser from one swept LFO — modulated fractional delays and an allpass cascade, animated notch response; JUCE `dsp::Chorus` |
| [Plugin Example — Synth](https://github.com/BrendanJamesLynskey/Plugin_Example_Synth) | A playable polyphonic subtractive synthesiser — PolyBLEP oscillators, a TPT state-variable filter, ADSR envelopes, 8-voice polyphony, presets; JUCE `Synthesiser` |

## Signal Processing Guides

Interactive, animated visual guides — zero dependencies, pure HTML/Canvas/JS.

| Guide | Topic |
|-------|-------|
| [Short-Time Fourier Transform](https://github.com/BrendanJamesLynskey/ShortTimeFourierTransform) | 10-chapter guide from first principles to applications, with full equation derivations |
| [Wavelet Transform](https://github.com/BrendanJamesLynskey/WaveletTransformGuide) | 7-chapter walkthrough — Morlet, Haar, Mexican Hat, Daubechies, with interactive scalograms |
| [Constant-Q Transform](https://github.com/BrendanJamesLynskey/ConstantQ-Transform) | Log-frequency analysis that mirrors musical pitch perception — FFT vs CQT comparisons |
| [Minimum & Maximum Phase Filters](https://github.com/BrendanJamesLynskey/MinimumMaximumPhaseFilters) | Interactive z-plane exploration, allpass decomposition, group delay and energy analysis |
| [Wavelets for Sound](https://github.com/BrendanJamesLynskey/Wavelets_for_Sound) | Kronland-Martinet, Grossmann & Morlet — history, CWT mathematics, Morlet wavelet explorer, scalogram builder, ridge extraction, wavelet synthesis, transient detection, sound transformations, with interactive audio throughout |
| [STFT for Sound](https://github.com/BrendanJamesLynskey/STFT_for_Sound) | Gabor, Allen & Rabiner, Portnoff, the phase vocoder — history, window library, Heisenberg boxes, filter-bank view, COLA round-trip, phase-vocoder time-stretch, Griffin–Lim inversion, spectral subtraction, mel-spectrogram frontend, with interactive audio throughout |
| [Constant-Q Transform for Sound](https://github.com/BrendanJamesLynskey/Constant_Q_Transform_for_Sound) | Brown & Puckette, Schörkhuber & Klapuri — history from Helmholtz to modern MIR, log-frequency kernel inspector, FFT-vs-CQT flagship comparison, sparse-kernel efficiency, chromagram + chord estimation, onset detection, invertible CQT row-shift pitch-shift, with interactive audio throughout |
| [MDCT for Sound](https://github.com/BrendanJamesLynskey/MDCT_for_Sound) | Princen & Bradley, TDAC — the transform inside every MP3/AAC/Opus codec: basis functions, TDAC cancellation, Princen-Bradley condition checker, round-trip encode/quantise/decode, toy codec with bit allocation, block-switching for pre-echo, with interactive audio throughout |
| [MFCC for Sound](https://github.com/BrendanJamesLynskey/MFCC_for_Sound) | Cepstrum, Davis & Mermelstein — the 30-year ASR workhorse: cepstrum/vowel explorer, mel filterbank, full pipeline visualiser, MFCC similarity matrix, deltas and delta-deltas, the log-mel successor, with interactive audio throughout |
| [Sound Transforms — History and Practical Guide](https://github.com/BrendanJamesLynskey/Sound_Transforms_History) | The meta-guide — how STFT, CWT, CQT, MDCT, and MFCC grew over two centuries; flagship same-signal-three-lenses demo; comparison table; decision tree for which to reach for when |
| [Laplace Transform](https://github.com/BrendanJamesLynskey/LaplaceGuide) | 7-section visual guide — complex exponential decomposition, pole-zero maps, transfer functions |

## Dispersion, Causality & Complex Analysis

Deep treatments of the mathematics that ties frequency-domain responses
together — causality, analyticity, dispersion relations.

| Guide | Topic |
|-------|-------|
| [Kramers–Kronig Relations](https://github.com/BrendanJamesLynskey/Kramers_Kronig_Relations) | 31-chapter presentation (Markdown + interactive HTML) — complex-analysis foundations, the K–K integrals, cross-discipline sign and plot conventions, and applications to DSP minimum-phase / Bode / dielectric spectroscopy / optical constants / FDTD / VNA / communications / audio |

## Companions to Julius O. Smith III's Online Textbooks

Interactive browser-first guides that sit alongside the five [CCRMA online
textbooks](https://ccrma.stanford.edu/~jos/) by Julius O. Smith III — each
repo is a single-file HTML presentation with live canvas visualisations,
Web Audio playback, KaTeX-rendered mathematics, and historical context.

| Companion | JOS Book | Topics & Demos |
|-----------|----------|----------------|
| [Companion to *Mathematics of the Discrete Fourier Transform* by Julius O. Smith III](https://github.com/BrendanJamesLynskey/Companion_JOS_Mathematics_of_the_DFT) | [MDFT](https://ccrma.stanford.edu/~jos/mdft/) | Bombelli → Wessel → Gauss; click-and-drag complex plane, three proofs of Euler's identity with convergence meter, four-panel phasor, basis-vector projection explorer, orthogonality polygon sum, Fourier-theorem demos, N=8 radix-2 butterfly diagram, $N^2$ vs $N\log N$ complexity widget, Cooley–Tukey history, Web Audio chord spectrum |
| [Companion to *Introduction to Digital Filters* by Julius O. Smith III](https://github.com/BrendanJamesLynskey/Companion_JOS_Introduction_to_Digital_Filters) | [Filters](https://ccrma.stanford.edu/~jos/filters/) | Black, Bode, Zadeh, Kaiser, Parks–McClellan history; flagship draggable z-plane (click to add poles/zeros, live magnitude/phase/group-delay/IR), convolution slider, elementary filter library (1-pole, biquad, notch, shelving, peaking), min/max-phase zero-reflection, DF-I/DF-II/TDF-II/cascade structure diagrams, FIR window + bilinear-Butterworth IIR designer, allpass cascade, 3-band EQ on drum loop with Web Audio A/B |
| [Companion to *Spectral Audio Signal Processing* by Julius O. Smith III](https://github.com/BrendanJamesLynskey/Companion_JOS_Spectral_Audio_Signal_Processing) | [SASP](https://ccrma.stanford.edu/~jos/sasp/) | McAulay–Quatieri, Serra & Smith SMS, Atal, Itakura, de Cheveigné, Auger & Flandrin; quadratic peak interpolation viz, MQ sinusoidal-tracking flagship with track-birth/death + oscillator resynth audio, SMS deterministic+stochastic split, LPC envelope with Levinson visualiser, YIN pitch monitor, reassigned spectrogram, chirp-z spiral contour, full Parseval and reassignment derivations |
| [Companion to *Physical Audio Signal Processing* by Julius O. Smith III](https://github.com/BrendanJamesLynskey/Companion_JOS_Physical_Audio_Signal_Processing) | [PASP](https://ccrma.stanford.edu/~jos/pasp/) | Helmholtz → Raman → McIntyre/Woodhouse → Karplus/Strong → Smith waveguide; flagship plucked-waveguide string with audio, bouncing D'Alembert wave on finite string, Karplus–Strong explorer, two-port scattering junction, bowed-string stick-slip, clarinet reed+bore, 2-D FDTD membrane with virtual mic, modal synthesis presets, 12-key commuted piano, 4-line Hadamard FDN reverb |
| [Companion to *Audio Signal Processing in Faust* by Julius O. Smith III](https://github.com/BrendanJamesLynskey/Companion_JOS_Audio_Signal_Processing_in_Faust) | [Faust](https://ccrma.stanford.edu/~jos/aspf/) | Mathews → Puckette → Orlarey/Fober/Letz; block-diagram algebra with five composition operators, live type-inference constructor, Faust listings for phasor/polyBLEP/biquad/KS/8×8 Householder FDN, recursion (`~`) semantics derived to a z-plane pole, `faust2…` toolchain tour, channel-strip and FreeVerb case studies, all demos audible via Web Audio |

## Cross-Domain (DSP + ML)

| Project | Description |
|---------|-------------|
| [DDSP — Differentiable DSP](https://github.com/BrendanJamesLynskey/DDSP_Differentiable_DSP) | Interactive DDSP explorer — additive + subtractive synthesis controlled by neural-style parameter curves, gradient visualisation, resynthesis presets |

## Neural / ML Audio Synthesis

A twelve-part interactive series on the **machine-learning techniques that generate
sound** — the human voice, music, and instruments. From WaveNet's sample-by-sample
gamble to diffusion models and language models that compose, each part derives its
core mathematics, animates its architecture, and lets you **hear the technique run
live** in the browser (Web Audio, no samples). Indexed from a dedicated hub, in the
same single-file house style as the rest of this collection.

**[Neural Sound Synthesis — series hub](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis)** — [launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis/)

| # | Part | Pillar | Topics &amp; demos |
|---|------|--------|--------|
| 01 | [Foundations &amp; the Landscape](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_01_Foundations_and_Landscape) | Core | Representation domains, generative-model taxonomy, μ-law quantization, dilated convs, evaluation (MOS/FAD/CLAP) — four live demos ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_01_Foundations_and_Landscape/)) |
| 02 | [Autoregressive Waveform Models](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_02_Autoregressive_Waveform) | Core | WaveNet, dilated causal convolutions, μ-law, SampleRNN, WaveRNN — live AR sampler ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_02_Autoregressive_Waveform/)) |
| 03 | [Neural Vocoders (GAN)](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_03_Neural_Vocoders_GAN) | Voice | MelGAN, Parallel WaveGAN, HiFi-GAN, multi-period/multi-scale discriminators — live Griffin–Lim A/B ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_03_Neural_Vocoders_GAN/)) |
| 04 | [End-to-End TTS](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_04_End_to_End_TTS) | Voice | Tacotron 1/2, FastSpeech 1/2, VITS (flow + VAE + adversarial) — attention aligner, duration control ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_04_End_to_End_TTS/)) |
| 05 | [Neural Singing Voice](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_05_Neural_Singing_Voice) | Voice | DiffSinger, NNSVS, voice conversion (so-vits-svc, RVC) — F0+vibrato sung-vowel editor ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_05_Neural_Singing_Voice/)) |
| 06 | [Differentiable DSP](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_06_Differentiable_DSP) | Core | DDSP harmonic-plus-noise, multi-scale spectral loss, timbre transfer — live resynthesiser ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_06_Differentiable_DSP/)) |
| 07 | [GAN Instrument Synthesis](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_07_GAN_Instrument_Synthesis) | Core | WaveGAN, SpecGAN, GANSynth, instantaneous frequency, latent timbre morphing ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_07_GAN_Instrument_Synthesis/)) |
| 08 | [Diffusion &amp; Flow Models](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_08_Diffusion_and_Flow) | Core | DDPM/score-based, DiffWave, WaveGrad, noise schedules, guidance — live forward/reverse diffusion ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_08_Diffusion_and_Flow/)) |
| 09 | [Neural Audio Codecs](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_09_Neural_Audio_Codecs) | Music | SoundStream, EnCodec, DAC, residual vector quantization — live RVQ visualiser ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_09_Neural_Audio_Codecs/)) |
| 10 | [Language-Model Music Generation](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_10_LM_Music_Generation) | Music | AudioLM, MusicLM, MusicGen, Jukebox, tokens over transformers — live token-LM melody ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_10_LM_Music_Generation/)) |
| 11 | [Latent Diffusion: Text-to-Audio](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_11_Latent_Diffusion_Text_to_Audio) | Music | AudioLDM, Stable Audio, Riffusion, CLAP conditioning — live spectrogram-diffusion denoiser ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_11_Latent_Diffusion_Text_to_Audio/)) |
| 12 | [Real-Time, Control &amp; Frontiers](https://github.com/BrendanJamesLynskey/Neural_Sound_Synthesis_12_Realtime_Control_Frontiers) | Core | RAVE, streaming, evaluation, watermarking &amp; ethics — live streaming-latent knob + FAD explainer ([launch](https://brendanjameslynskey.github.io/Neural_Sound_Synthesis_12_Realtime_Control_Frontiers/)) |

## Hardware & Algorithms

| Project | Description |
|---------|-------------|
| [CORDIC](https://github.com/BrendanJamesLynskey/CORDIC) | Synthesisable SystemVerilog implementations of the CORDIC algorithm |
