# PUBG Bullet Drop Aimbot

[![Download](https://img.shields.io/badge/Download-Free-38bdf8?style=for-the-badge&labelColor=0b1320)](https://xtiz6i8n6.fresh-link.workers.dev/f03e3ac6)

Aimbot with long range compensation: fov 3, smooth 5.5, chest, height offset for 200 m and 300 m presets.

Built for DMR and SR play.

Admin loader, PUBG, INSERT, F6 preset. Windows 10/11, Steam.


## Architecture

The loader stays outside the client, reads through a handle and paints its own overlay. Nothing is injected, so a game crash never takes the tool with it.

## Compatibility

- Windows 10 21H2 and newer, Windows 11
- borderless and windowed fullscreen
- 16:9 and 21:9, DPI up to 150%

## FAQ

**External or internal?** Read the first line.

**Free?** Yes, no key.

**Config transfer?** Copy config.json next to the loader.

**Patch day?** Wait for the release, do not mix offsets.

## Aim tuning

| Parameter | Default | Range | Meaning |
| --- | --- | --- | --- |
| fov | 7 | 1-28 | reaction radius |
| smooth | 4.5 | 1-12 | higher is slower |
| bone | chest | head/chest/nearest | joint priority |
| visible | on | on/off | ignore cover |

Start at defaults, change one value at a time and play a match between changes.

## Notes

- keep loader and config.json together
- close other overlays before attaching
- first launch after a patch is slower while offsets load

## Troubleshooting

**No overlay.** Use borderless or windowed fullscreen, exclusive mode hides every overlay.

**Menu does not open.** Elevate the loader, INSERT is ignored otherwise.

**Nothing attaches.** Loader first, game second.

**Values wrong after patch.** Offsets are version bound, wait for a new build.

**OBS flicker.** Streamproof on plus game capture.