# Part 2 — The Climb

A standalone browser platformer for the ARG.

## Controls
- A / D or Left / Right: move
- Space: jump
- E: enter a glowing gate when you are beside it
- R: recover at the last saved checkpoint
- Music button: toggle soundtrack

## Save behavior
Progress is stored in browser localStorage under a versioned save key. Fragment collection is saved by permanent fragment IDs, so refreshing the page does not respawn already-collected fragments.

Level progression, learned mechanics, checkpoints, the ending state, and music preference are also saved.

## Recovery
Every level has safe checkpoints. Falling automatically returns the player to the latest checkpoint. Press **R** at any time during gameplay to return there manually.

## Part 2 soundtrack
The supplied `assets/music/part2.mp3` file is used locally by the game.
