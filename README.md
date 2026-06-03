# Battle Boy

A high-quality, self-contained HTML5 twin-stick arena shooter inspired by *Battle-Girl* (1997, Ultra/United Games). Clean **TripTronic** vector visuals, procedural tracker-style techno, and escalating wave intensity — playable in any modern browser with zero dependencies.

## Play

1. Clone this repo.
2. Open [`index.html`](index.html) in Chrome, Firefox, Safari, or Edge.
3. Click the canvas once to unlock audio, then press **Enter** or click **START**.

Optional: enable [GitHub Pages](https://pages.github.com/) on the `main` branch with `/ (root)` to play online.

## Controls

| Input | Action |
|-------|--------|
| **WASD** / **Arrow keys** | Move |
| **Mouse** | Aim |
| **Hold LMB** | Fire toward cursor |
| **IJKL** / **Numpad** | 8-direction fire (keyboard-only fallback) |
| **Gamepad** | Left stick move, right stick aim, **RT** fire |
| **Enter** / **Space** | Start / restart |
| **P** | Pause |

## Objective

Pilot the Battle Boy strike craft in **The Nexus**. Protect **4 Function Nodes** from Corruptor Drones and Chaos Programmers. If too many nodes fall, the **Terminus Protocol** activates — survive, score high, and chase the local leaderboard.

## Tech

- Single file: vanilla JavaScript, Canvas 2D, Web Audio API
- No build step, no external assets
- High scores stored in `localStorage`

## License

MIT — see [LICENSE](LICENSE).

## Credits

Inspired by *Battle-Girl* and the TripTronic engine (Ultra/United Games, 1997). This is a fan reimagining, not an official port.