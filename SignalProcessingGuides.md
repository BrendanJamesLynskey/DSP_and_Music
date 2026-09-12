# Signal Processing Guides

[← Back to DSP & Music](README.md)

Interactive, animated visual guides — zero dependencies, pure HTML/Canvas/JS.

## Transforms

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

## Matrix Methods

The linear-algebra view of filters and networks — what the *structure* of a matrix
(symmetry, definiteness, unitarity) guarantees about the physical system it describes.
Three companion decks in the same interactive style, each with a long-form PDF
alongside. They pick up where the Laplace, minimum/maximum-phase and Kramers–Kronig
guides above leave off, and the third takes the whole apparatus to a real design
problem.

| Guide | Topic |
|-------|-------|
| [Digital Filters — State, Structure and Stability](https://github.com/BrendanJamesLynskey/Matrix_Concepts_Digital_Filters) | The three matrix structures behind filter design — eigenvalues of the state matrix and the unit circle, Wiener–Hopf with Toeplitz Hermitian PSD autocorrelation, the eigenfilter as a Rayleigh quotient, paraunitary banks and perfect reconstruction. Interactive pole explorer (push the radius past 1 and watch it go unstable), eigenfilter bowl with snap-to-eigenvector, and a paraunitary rotation you can deliberately break |
| [Network Parameters — S, Z and Y](https://github.com/BrendanJamesLynskey/Matrix_Methods_Network_Parameters) | The continuous-time companion, for RF and high-speed digital — reciprocity as transpose symmetry, passivity as positive semidefiniteness, losslessness as unitarity; poles and zeros as eigenvalues of the state matrix, causality and Kramers–Kronig, Hamiltonian passivity enforcement, the Smith chart as a Möbius map. Interactive two-port scattering explorer, pole–zero explorer, and bilinear map |
| [Equalisation in High-Speed Serial Links](https://github.com/BrendanJamesLynskey/SerDes_Equalisation) | The applied deck — one 28 GBd backplane channel characterised from its S-parameters, turned into a pulse response, and equalised block by block (CTLE, transmit FFE, receive FFE, DFE) to a noise budget that lands 1.36 dB short of 10⁻¹². Then seven remedies priced in dB, PAM4 and why FEC stopped being optional, LMS adaptation and link training, and the road to 224 Gb/s. Interactive via-stub explorer and a full equaliser chain with live budget, Q and BER |
