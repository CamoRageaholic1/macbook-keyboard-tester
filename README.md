# ⌨️ MacBook Keyboard Tester

A browser-based keyboard tester built to match the MacBook Pro layout. Every key lights up green when pressed so you can quickly verify your entire keyboard is working — no software installs required.

## Features

- **Full MacBook Pro layout** — all keys including `fn`, Touch ID / Power button, and split arrow keys
- **Live press detection** — keys highlight green on keydown, animate on keyup
- **Progress counter** — tracks `X / Y keys tested` in real time
- **Completion state** — header turns green and reads “All Keys Tested!” when every key is confirmed
- **Click-to-test** — `fn` and `Touch ID` can’t be detected by the browser; click them to mark as tested
- **Reset** — clears all state to start a fresh test
- **Zero dependencies** — single self-contained HTML file, works fully offline

## Usage

```bash
git clone https://github.com/CamoRageaholic1/macbook-keyboard-tester.git
open macbook-keyboard-tester/index.html
```

Or just download `index.html` and open it in any browser — no server required.

## Known Limitations

| Key | Behavior |
|---|---|
| `fn` | Not detectable by browser API — click to mark tested |
| `Touch ID / ⏻` | Not detectable by browser API — click to mark tested |
| `F11`, `F12` | May be intercepted by macOS Mission Control |

To free F11 / F12: **System Settings → Keyboard → Keyboard Shortcuts → Mission Control** and unbind the conflicting shortcuts.

## Author

**CamoZeroDay** — [github.com/CamoRageaholic1](https://github.com/CamoRageaholic1)
