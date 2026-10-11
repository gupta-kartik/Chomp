# CHOMP! · make it Singaporean

Starter for the Tech After Dark Singapore live coding showdown: a classic maze-chase arcade game in one file.

## Run it

Open `index.html` in the Copilot app's browser canvas, or in any browser. There's no install and no build step.

**Controls:** arrow keys or WASD to move, Space to start, P to pause, M to mute. Swipe on touch screens.

## The challenge

**Make it Singaporean.** The crowd judges:

1. How Singaporean it feels
2. Whether it still plays
3. The best moment in your 60-second demo

Finish with a one-slide pitch in the PowerPoint canvas.

## Where things live in `index.html`

| What | Where |
| --- | --- |
| Names, colours, on-screen text | `THEME` |
| Speeds, points, lives | `CONFIG` |
| Maze layout (`#` wall, `.` dot, `o` power pellet, `-` ghost door, `P` player, `G` ghost) | `MAZE` |
| How things look | `drawPlayer`, `drawGhost`, `drawDots`, `drawMaze`, `drawHud` |
| Sound effects (synthesised, no audio files) | `SFX` |
| Game rules | `update()` |

## House rules

`.github/copilot-instructions.md` keeps Copilot's suggestions inclusive: celebrate Singapore, never stereotype the people in it.
