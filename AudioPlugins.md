# Audio Plugins

[← Back to DSP & Music](README.md)

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
