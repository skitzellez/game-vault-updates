Shader warm-up lists for xemu (original Xbox), one per game, named by the game's ID as Game Vault shows it
(for example VU-003). Recorded on a Series X while playing; each holds the setups of the shaders the game
used (no pictures, no saves, nothing about the player).

Game Vault 0.16.1.7 and newer fetch every list named in index.txt (all of them, whatever games the player
has, so nothing about the player's games is sent) and xemu 0.9.120.0 and
newer use it only when it has no list of its own for that disc: the game's shaders are then prepared before
they are needed instead of making the first play stutter.

The lists match one xemu list layout (the header says which); xemu ignores a list it cannot read.
