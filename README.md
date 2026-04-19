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

## Hardware & Algorithms

| Project | Description |
|---------|-------------|
| [CORDIC](https://github.com/BrendanJamesLynskey/CORDIC) | Synthesisable SystemVerilog implementations of the CORDIC algorithm |
