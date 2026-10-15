# EspressU website

A six-page static website for [EspressU](https://github.com/EspressU/EspressU-Emu): home, features, setup, FAQ, community and about. No build step and no dependencies besides Google Fonts.

Made by MuffinEMU. Content is taken from EspressU's README and app source.

## Preview it

```
python3 -m http.server 8765
```

Then open http://localhost:8765/.

## Things to know

- The download buttons point at `EspressU-1.0.ipa` in the v1.0 release. For a new version, search the pages for `EspressU-1.0.ipa` and update it.
- The icon is EspressU's app icon (`assets/icon.png`).
- Light and dark themes follow the visitor's device, with a toggle in the header.
- The footer credits "Based on MuffinEMU by Void".
