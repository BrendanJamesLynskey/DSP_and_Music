# Early Western Music

[← Back to DSP & Music](README.md)

A themed set of browser synthesizers that trace the birth of Western music —
from the unison chant of the early Church to the polyphony of the Gothic
cathedrals and the secular song and dance of the medieval courts. Each app
recreates one style in real time. Organum and troubadour song are sung with
**real recorded voices**: actual sung vowels from the
[VocalSet](https://zenodo.org/records/1193957) corpus (CC BY 4.0), pitch-mapped
with formant preservation and given expressive vibrato and breath, over a
subtractive-synth vielle drone for the secular song. Gregorian chant defaults to
an **ethereal pure-sine** wordless chant that blooms slowly into a deep abbey
reverb, with the same sampled choir available at a **Timbre** toggle. Each
carries an in-app description of its style and how it relates to the others.

**The lineage.** Everything begins with unaccompanied plainchant. Add a second
voice to chant and you get *organum* — the first great flowering of polyphony, at
Notre-Dame. Running alongside the sacred line is a secular, vernacular branch: the
monophonic songs of the *troubadours*.

```
 SACRED     Plainsong ──► Organum   (chant → the first polyphony)

 SECULAR    Troubadour song   (vernacular courtly monophony)
```

| Project | Style · Era | Voicing &amp; synthesis technique |
|---------|-------------|---------------------|
| [Synth Gregorian](https://github.com/BrendanJamesLynskey/Synth_Gregorian) | Plainsong / Gregorian chant · 9th–10th c. | Ethereal **pure sine tones** by default (slow-blooming, deep abbey reverb); **Timbre** toggle to **real sampled voices** (VocalSet vowels, formant-preserving pitch-shift) |
| [Synth Organum](https://github.com/BrendanJamesLynskey/Synth_Organum) | Notre-Dame polyphony (Léonin, Pérotin) · c. 1160–1250 | Sung — **real sampled voices** in **Pythagorean just intonation**; plays the actual notated scores (Pérotin & Léonin) |
| [Synth Troubadour](https://github.com/BrendanJamesLynskey/Synth_Troubadour) | Troubadour / trouvère secular song · 12th–13th c. | Sung melody — **real sampled voice** over a **subtractive**-synth vielle drone |
