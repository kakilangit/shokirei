<p align="center">
  <img src="icon.png" alt="Shokirei icon" width="128">
</p>

# Shokirei

[![Latest release](https://img.shields.io/github/v/release/kakilangit/shokirei)](https://github.com/kakilangit/shokirei/releases/latest)

*Shot* + *kirei* (綺麗, Japanese for "beautiful"), said "sho-kee-ray".

A native macOS app that makes screenshots beautiful, built with Rust and [GPUI](https://www.gpui.rs/). Capture an area, a window, or the whole screen, or bring in an image or a piece of code, and put it on a gradient backdrop with padding, rounded corners, and a shadow. Mark it up with arrows, boxes, text, and blur, copy the text in it, or hide what's sensitive in one click. Everything runs on your Mac: no account, no uploads, no tracking.

> **Status:** early development.

<p align="center">
  <img src="https://raw.githubusercontent.com/kakilangit/static/refs/heads/main/shokirei/shokirei_screenshot.png" alt="Shokirei showing a screenshot on a gradient backdrop, marked with a box and an arrow: capture and code at the top, the annotation tools under the picture, and backdrop and style controls in the sidebar" width="800">
</p>

## Features

- Capture an area, a window, or the whole screen Shokirei is on, with the system capture tool
- Capture an area from any app with `⇧⌘2`, or another shortcut of your choice
- An icon in the menu bar to capture or bring the window back; closing the window keeps Shokirei
  running there
- Open an image file (PNG, JPEG, or TIFF) or paste one from the clipboard
- Everything in one window: where a picture comes from in the bar at the top, the tools for marking
  it up floating under it, and how it looks in the sidebar
- Backdrops: gradient presets and a plain color, your own colors and angle, a picture of your own,
  or Auto, which picks a gradient from the screenshot's colors
- Adjustable padding, corner radius, and shadow strength
- Sizes for social sites: 1:1, 4:5, 16:9, 9:16, and 1.91:1
- Balance: centers the content with even margins on every side
- Saved styles: keep a look and apply it to later screenshots
- Annotations: arrows, boxes, text, and blur, which hides passwords and names, in six colors
- Blur sensitive text in one click: email addresses, card numbers, IP addresses, API keys
- Copy text from a screenshot, all of it or a selected area, recognized on your Mac
- Code snippets as pictures: click Code or paste code, and it's highlighted in an editor window, in
  24 languages, dark or light, with or without line numbers
- Watermark: your logo in a corner or the center, with adjustable opacity and size
- Recent: reopen any of your last six screenshots; they stay on your Mac, and Clear removes them
- Shokirei hides while you capture and comes back with the result
- Copy the finished picture, or save it as PNG, JPEG, or TIFF, at full resolution
- Smaller files: standard resolution and stronger compression, about a quarter of the size
- Light and dark themes; override with `SHOKIREI_THEME=light|dark`

## Install

macOS (Apple silicon and Intel), with [Homebrew](https://brew.sh):

```sh
brew install --cask kakilangit/tap/shokirei
```

Or download `Shokirei-<version>-universal.dmg` from [Releases](https://github.com/kakilangit/shokirei/releases/latest) and drag Shokirei to Applications. The app is not notarized yet, so macOS blocks it until you clear the quarantine flag (Homebrew does this for you):

```sh
xattr -cr /Applications/Shokirei.app
```

The first capture asks for the Screen Recording permission, in System Settings → Privacy & Security → Screen Recording.

## Feedback

Report bugs and ideas in [Issues](https://github.com/kakilangit/shokirei/issues).

## License

Shokirei is free to use, but not open source: see [LICENSE](LICENSE). This repository holds only its
releases. Versions up to 0.3.1 were released under the MIT License. The app includes open-source
software under its own licenses, listed in `THIRD_PARTY_LICENSES.txt` inside the app.
