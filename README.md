# 🎵 Web Harmonium

A browser-based harmonium you can play with your keyboard, mouse, or touchscreen — no plugins or installs needed.

**Live demo (GitHub Pages):** `https://ogtanmay.github.io/wb-harmonium-/`

---

## Features

- 🎹 **Visual piano keyboard** with white & black keys, labeled with sargam notation (Sa Re Ga Ma Pa Dha Ni)
- ⌨️ **QWERTY keyboard mode** — an on-screen button grid perfect for mobile phones
- 📱 **Full touch support** — tap keys on any smartphone or tablet
- 🎵 **Harmonium-style sound** synthesised in the browser with Web Audio API (sawtooth + waveshaper reed character)
- 🔊 **Volume slider** and **octave shift** (± 2 octaves)

---

## Keyboard Mapping

| Physical Keys | Notes |
|---|---|
| `Z X C V B N M` | C D E F G A B (octave 3 – white keys) |
| `S D G H J` | C# D# F# G# A# (octave 3 – black keys) |
| `Q W E R T Y U I O P` | C D E F G A B C D E (octave 4-5 – white keys) |
| `2 3 5 6 7 9 0` | C# D# F# G# A# C# D# (octave 4-5 – black keys) |

Use the **QWERTY Mode** button to switch to a full on-screen button grid — great for mobile phones where you tap the QWERTY-labeled tiles to play.

---

## Hosting on GitHub Pages

1. Go to the repository **Settings → Pages**
2. Set *Source* to **Deploy from a branch**, branch `main` (or whichever branch this is on), folder `/` (root)
3. Save — your harmonium is live at `https://<username>.github.io/<repo>/`
