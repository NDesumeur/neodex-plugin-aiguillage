# Aiguillage

A train rhythm game through the countryside. At every switch, one track carries a wagon and the other ends at a buffer stop: switch to the right side just as the engine gets there. Every wagon you take makes the train longer. Play the 1200 tracks from the Rythme plugin, or your own music.

*Version française : [README.md](README.md)*

## How to play

- **← or D/F**: left · **→ or J/K**: right. A **click** works too: on the left or right half of the screen.
- The **arrow** in front of the switch shows the wagon's side; the other track ends at a **red buffer stop**.
- The wrong side leads to a **dead end**: the note is missed and the train loses a wagon. Every wagon taken adds one (up to 12).
- The side follows the music: low notes to the left, high notes to the right, never more than 5 times in a row on the same side.
- **Gamepad**: the D-pad, X, A and the left shoulder go left; B, Y and the right shoulder go right; Start starts, Select pauses.
- **Space**: play · **P**: pause · **Full screen** during the game.

## Accuracy and points

Notes are judged by how far they are from the right moment: **Perfect** (about ±45 ms), **Good** (±90 ms), **OK** (±140 ms), otherwise a miss.

A note's points rise by 1 % per note of combo, up to double at 100 notes in a row; a miss resets the combo. At the end, accuracy gives a grade: **S** from 95 %, **A** at 90 %, **B** at 80 %, **C** at 70 %, **D** below.

## Songs and difficulty

The **Songs** tab has the 1200 Rythme tracks, in four difficulties (Easy, Normal, Hard, Expert). Each level's difficulty is computed from its notes (density, busy passages), from 1 to 10 stars.

## My music

In **My music**, create a level from an imported **audio file** or a track from your **NeoMusic** library: the game finds its tempo and strong beats and turns them into a level, at the chosen **difficulty** (1 to 10 stars).

## Settings

- Music **volume**.
- **Hit sound**: the sound played on each note you hit, one of 10 (Soft, Clap, Wood, Kick, Crystal, Pop, Hi-hat, Snare, Pluck, Tock) or none. Losing a combo of 10 or more plays a « combo break » sound.
- **Offset** (−300 to +300 ms): it adjusts itself after each game based on your average lateness or earliness; you can also change it by hand.

## Data and sync

Your scores and grades per level and your settings are stored by NeoDex, backed up and synced between your PCs when sync is on.

## Install

In NeoDex: **NeoStore → Discover → Aiguillage → Install**.

Building a plugin: see the [NeoDex SDK](https://github.com/NDesumeur/neodex-sdk).
