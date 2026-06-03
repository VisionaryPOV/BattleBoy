# Battle Boy

A high-quality, self-contained HTML5 twin-stick arena shooter inspired by *Battle-Girl* (1997, Ultra/United Games). Clean **TripTronic** vector visuals, procedural tracker-style techno, and escalating wave intensity — playable in any modern browser with zero dependencies.

## Play online

**https://visionarypov.github.io/BattleBoy/**

Works on desktop and iPhone/iPad — no install, no local server. Tap to start; use the on-screen twin sticks on mobile.

### Desktop (local)

1. Clone this repo, or open [`index.html`](index.html) directly.
2. Click the canvas once to unlock audio, then press **Enter** or click **START**.

### iPhone / iPad

Open the **Play online** link above in Safari.

1. **Tap** the screen to start (unlocks audio).
2. **Left stick** — move; **right stick** — aim and fire.
3. The game **enters fullscreen automatically** when a run starts (or tap **FULLSCREEN** top-right).
4. Optional: **Share → Add to Home Screen** for an app-like shortcut without Safari chrome.

<details>
<summary>Local Wi‑Fi server (optional dev fallback)</summary>

```bash
cd /path/to/BattleBoy
python3 -m http.server 8080
```

On iPhone Safari: `http://YOUR_MAC_IP:8080` (same Wi‑Fi as your Mac).
</details>

## Controls

| Input | Action |
|-------|--------|
| **Left stick** (touch) | Move |
| **Right stick** (touch) | Aim + fire (push past dead zone) |
| **WASD** / **Arrow keys** | Move (desktop) |
| **Mouse** | Aim (desktop) |
| **Hold LMB** | Fire toward cursor |
| **IJKL** / **Numpad** | 8-direction fire (keyboard-only fallback) |
| **Gamepad** | Left stick move, right stick aim, **RT** fire |
| **Tap** / **Enter** / **Space** | Start / restart |
| **F** / **FULLSCREEN** button | Toggle fullscreen (during play) |
| **P** | Pause (desktop) |

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