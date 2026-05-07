# 💻 IT'S A GAME!

A pixel-art platformer where you fix devices, stomp enemies and survive the
school IT support shift from hell. Single-file HTML5 canvas game — no build
step, no dependencies (just a Google Fonts CDN).

🎮 **Play it:** https://sambayford.github.io/IT-S-A-GAME/ 

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | Arrow keys / WASD | ◀ ▶ buttons |
| Jump | Space / W / Up arrow | 🔼 button |
| Fix a device | Walk into it | Walk into it |
| Stomp an enemy | Jump on top of it | Jump on top of it |
| Continue after a zone clears | Space / Enter / tap | Tap |
| Restart after death | R | Tap **Reboot** |
| Mute / unmute | 🔊 button in the HUD | 🔊 button in the HUD |

## Gameplay

- 🔧 Walk into broken devices to start fixing — hold position until the
  progress bar fills.
- 👟 Jump on enemies' heads to stomp them. Touching them any other way costs
  HP.
- ☕ Coffee gives you 5 seconds of turbo speed and faster fixes.
- 💾 floppy disks, 🔌 ethernet cables and 📘 manuals are score pickups.
- 🍩 Donuts heal 1 HP.
- ⚠️ Every 10th zone is a **boss zone** — face the Headteacher.

## Local development

It's a single static HTML file. Open it directly in a browser:

```sh
open index.html
```

…or serve it locally if you want to test on a phone:

```sh
python3 -m http.server 8000
# then visit http://<your-mac-ip>:8000 from the phone
```

## Browser support

Any chromium based browser or Safari. Tested in Chrome, Edge, Brave, Safari (macOS / iOS). Uses standard Canvas 2D and Web Audio APIs.

## Licence

MIT — see [LICENSE](LICENSE).
