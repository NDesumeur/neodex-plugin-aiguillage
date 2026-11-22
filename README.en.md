# Aiguillage

A steam train rhythm game, through fields, forests, villages and rivers. At every switch, one track carries a wagon and the other ends at a buffer stop: switch to the right side just as the engine gets there. Every wagon you take (logs, crates, coal, tank, passengers, fruit) makes the train longer. Play the 1200 tracks from the Rythme plugin, or your own music.

*Version française : [README.md](README.md)*

## How to play

- **← or D/F**: left · **→ or J/K**: right. A **click** works too: on the left or right half of the screen.
- The **arrow** in front of the switch shows the wagon's side; the other track ends at a **red buffer stop**. The wrong side leads to a **dead end**.
- A **golden siding**: hold the key until it rejoins the line, or the combo breaks.
- A **crossing** (yellow sign): both sides almost together.
- **Keys of your choice**: in the options, click a box then press the key you want. Arrows and the gamepad always work.
- **Gamepad**: the d-pad and left buttons for left, the right buttons for right.

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

## My town

Every wagon you catch is delivered to your town: wood, crates, coal, water, passengers or fruit, depending on the wagon. Game after game, these deliveries build twelve buildings along the track: the station, the sawmill, the houses, the market, the mine, the water tower, the hotel, the school, the mill, the factory, the fountain and the theatre. Each one needs an amount of one kind of goods. The “My town” card, below the song list, shows what is built and what is missing for the next one; the end screen says how many wagons you delivered and what was just built.

## Seasons, tunnels, drawbridges and oncoming trains

Each song has its season: spring (cherry blossoms, petals), summer, autumn (russet leaves, falling leaves) or winter (snow, frozen rivers, snowflakes). From Normal, the train goes through a tunnel for 4 bars every 24 bars: a “TUNNEL AHEAD!” banner warns you just before; inside, the track is hidden and each switch arrow only lights up at the last moment (a little over half a second before): press on its side, keeping to the beat of the music (low notes left, high notes right). One golden track in two crosses a drawbridge: it only comes down if you hold the key. In Hard and Expert, a red train sometimes comes the other way on a side track: do not switch to that side (“AVOIDED” if you stay, “COLLISION” otherwise).
