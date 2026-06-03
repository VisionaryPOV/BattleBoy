# Battle Boy

A high-quality, self-contained HTML5 twin-stick arena shooter inspired by *Battle-Girl* (1997, Ultra/United Games). Clean **TripTronic** vector visuals, procedural tracker-style techno, and escalating wave intensity — playable in any modern browser with zero dependencies.

## Play

### Desktop

1. Clone this repo.
2. Open [`index.html`](index.html) in Chrome, Firefox, Safari, or Edge.
3. Click the canvas once to unlock audio, then press **Enter** or click **START**.

### iPhone / iPad (recommended)

Safari cannot run arbitrary local files reliably — serve the game over HTTP on your Mac, then open it on your phone on the **same Wi‑Fi**:

```bash
cd /path/to/BattleBoy
python3 -m http.server 8080
```

On your Mac, find your LAN IP (System Settings → Network, or `ipconfig getifaddr en0`). On iPhone Safari, open:

`http://YOUR_MAC_IP:8080`

Example: `http://192.168.1.42:8080`

1. **Tap the screen** to start (unlocks audio).
2. Use the **left analog stick** to move and the **right stick** to aim — push the right stick to fire.
3. Optional: Safari → **Share** → **Add to Home Screen** for a full-screen app icon.

Other options: deploy [GitHub Pages](#) on `main`, use iCloud Drive + open in Safari, or AirDrop `index.html` to Files (Safari may still prefer a URL).

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