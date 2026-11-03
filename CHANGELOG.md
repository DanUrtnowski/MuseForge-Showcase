# MuseForge — public milestone record

Publicly verifiable milestones only. The development changelog stays private.

## 2026-11-01 — Playable minigames

- Three keyboard minigames built on the existing audio clock: Starshot Melody,
  Beat Blaster and a two-player Duet.
- Per-pad and per-note key rebinding; an unaided "hints off" mode scored
  separately from aided runs.
- Rhythm minigame progression and remap behaviour covered by automated browser
  checks.
- An independent audit of the minigame work was recorded, including its open
  findings.

## 2026-10-31 — Playable prototype

- One event timeline and one audio clock driving staff, tab and game highway.
- Synthesized guitar, click and count-in, entirely offline and deterministic.
- Tempo control from 50–100 % without pitch change.
- A/B looping with clean seams; light and dark themes; phone layout.
- AudioWorklet pitch/onset detection feeding live scoring with explicit
  uncertainty (hit, wrong pitch, octave, uncertain, missed) and a calibration
  routine.
- Authored key versus a labelled key hypothesis, with abstention.
- 43 unit tests and browser-driven checks passing in the cloud environment.

### Stated limitation

Every result above was produced with synthetic signals in a Linux cloud
environment. Windows and real-instrument validation had not been performed at
the time of writing.

## Not yet started

Real-instrument validation, polyphony, Session Mode, desktop packaging.
