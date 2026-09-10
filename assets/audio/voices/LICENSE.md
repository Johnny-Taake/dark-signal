# Character voices

All recordings used here are **CC0 1.0 Universal** (public domain dedication):
https://creativecommons.org/publicdomain/zero/1.0/
They may be copied, modified and redistributed, including in commercial games.

| Local files | Original recording and author | Source |
| --- | --- | --- |
| `lis-hurt-1.wav`, `lis-hurt-2.wav` | Female Hurt Grunts & Groans — AuraVoice / Nocturnal_Vanguard | https://opengameart.org/content/female-hurt-grunts-groans |
| `lis-breath-1.wav`, `lis-breath-2.wav` | Female Breathing Heavily (2) — Ashe Kirk / Owlish Media (OwlStorm) | https://freesound.org/people/OwlStorm/sounds/151215/ |
| `matt-hurt-1.wav`, `matt-hurt-2.wav` | 15 vocal male strain/hurt/pain/jump sounds — qubodup | https://opengameart.org/content/15-vocal-male-strainhurtpainjump-sounds |
| `matt-breath-1.wav`, `matt-breath-2.wav` | Breathless Man — Joseph SARDIN / BigSoundBank | https://bigsoundbank.com/breathless-man-s1103.html |
| `undead-*.wav`, `beast-*.wav`, `alien-*.wav` | Monster Sound Effects 2 — Ogrebane | https://opengameart.org/content/monster-sound-effects-2 |

The qubodup source page explicitly changed these sounds to CC0 on 2024-08-30.
The OwlStorm source page explicitly dedicates all their recordings to CC0.
The female breathing source is the publicly available HQ MP3 preview:
https://cdn.freesound.org/previews/151/151215_140737-hq.mp3

Adaptations: selected short excerpts, trimmed silence, mono 24 kHz 16-bit PCM WAV,
90 Hz high-pass / 6.5 kHz low-pass, peak normalization to -3 dB, 8 ms fade-in
and 35 ms fade-out. Matt breathing uses a different male recording with a 75 Hz high-pass, +3 dB at 220 Hz, 4.2 kHz low-pass, pitch/rate 0.92 and 12/40 ms fades. Runtime playback adds slight pitch variation and uses lower
pitch for heavier creatures. `provenance.json` records exact source filenames,
excerpt offsets and SHA-256 hashes of the downloaded source recordings.

These are existing human recordings; no voice synthesis service is used.

## Adding variants

1. Add a licensed recording in this directory and document its source here.
2. Register its explicit URL in `src/config/voices.js` → `VOICE_CLIPS`.
3. Append the clip ID to `OPERATOR_VOICES[skin].breath/hurt` or
   `ENEMY_VOICES[type].idle/hurt/attack`.

Each enemy type has independent arrays even when it shares the initial clips.
Playback selects variants without immediate repetition, limits voices per actor
and globally, and attenuates creature sounds by distance and stereo direction.
