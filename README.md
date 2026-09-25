# aftellen-elari

Countdown screen for a landscape TV, in the [Elari](https://design.elari.nl/home) brand style.
It's a single `index.html`: no build step and no dependencies (only the Google Fonts Bricolage Grotesque and Inter).

## Setting the date and text

Change the defaults in the `CONFIG` block at the bottom of `index.html`, or pass them in the URL:

```
https://aron-over.github.io/aftellen-elari/?date=2026-12-18T16:00&title=Almost%20time%20for%20the%20Christmas%20party
```

| Parameter | Example | Meaning |
|---|---|---|
| `date` | `2026-12-18T16:00` | Target moment in local time |
| `title` | `Almost there` | Large heading |
| `done` | `It's time!` | Text shown when the countdown reaches 0 |
| `text` | `Utrecht office` | Small text bottom right |
| `theme` | `light` / `dark` | Colour theme |

## On the TV

- Double-click to toggle fullscreen; the mouse cursor hides after 3 seconds.
- The screen stays on (Wake Lock, https only).
- The page reloads every hour, so changes reach the TV automatically.

## Hosting

Settings → Pages → Deploy from branch → `main` / root.
