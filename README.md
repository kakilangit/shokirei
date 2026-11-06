<p align="center">
  <img src="assets/icons/shokirei-256.png" alt="Shokirei icon" width="128">
</p>

<h1 align="center">Shokirei</h1>

<p align="center">
  <strong>Turn any screenshot into one worth sharing, in seconds.</strong><br>
  Capture, frame, mark up, and share. It all happens on your Mac.
</p>

<p align="center">
  <a href="https://github.com/kakilangit/shokirei/releases/latest"><img src="https://img.shields.io/github/v/release/kakilangit/shokirei?label=download" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/macOS-Apple%20silicon%20%26%20Intel-black" alt="macOS, Apple silicon and Intel">
  <img src="https://img.shields.io/badge/price-free-brightgreen" alt="Free">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/kakilangit/static/refs/heads/main/shokirei/shokirei_screenshot.png" alt="Shokirei showing a screenshot on a gradient backdrop, marked with a box and an arrow: capture and code at the top, the annotation tools under the picture, and backdrop and style controls in the sidebar" width="800">
</p>

<p align="center">
  <em>Shot</em> + <em>kirei</em> (綺麗, Japanese for "beautiful"). Say it "sho-kee-ray".
</p>

---

Raw screenshots look unfinished. Shokirei makes them look polished: press `⇧⌘2` in any app, drag
over what you want, and your capture comes back on a gradient with soft padding, rounded corners,
and a shadow. You can copy it straight into a post, a doc, or a chat.

## Why Shokirei

- **Fast.** One shortcut from any app, and the result is waiting for you. Shokirei gets out of the
  way while you capture and comes back when you're done.
- **Good-looking by default.** Auto picks a gradient from your screenshot's own colors, and Balance
  evens out the margins, so the first result is usually ready to share.
- **Private.** No account, no uploads, no tracking. Text recognition runs on your Mac too.
- **Free.**

## What it does

### Capture from anywhere

- Capture an area, a window, or the whole screen, or press `⇧⌘2` (or a shortcut you pick) from any app
- Use the menu bar icon to capture, even with the window closed
- Open, paste, or drop in a PNG, JPEG, or TIFF
- Reopen any of your last six screenshots from Recent

### Make it look good

- Gradient presets, a plain color, your own two colors and angle, a picture of your own, or **Auto**,
  which matches the screenshot
- Adjust padding, corner radius, and shadow
- Pick a shape for social posts: 1:1, 4:5, 16:9, 9:16, and 1.91:1
- **Balance** centers the content with even margins
- **Saved styles** keep your look for every screenshot after
- **Watermark** puts your logo in a corner or the center

### Mark it up

- Add arrows, boxes, text, and blur, in six colors
- **Blur sensitive text in one click:** email addresses, card numbers, IP addresses, and API keys
- **Copy the text** in a screenshot, all of it or just the part you select

### Show off your code

Paste code or click **Code**. Shokirei highlights it in an editor window, in 24 languages, dark or
light, with or without line numbers. It's ready to share like any screenshot.

### Share it

- Copy, save, or drag the picture straight into another app, as PNG, JPEG, or TIFF
- Export at full resolution, or pick **Smaller files** for about a quarter of the size
- Saved files get a date and time in the name, so they never overwrite each other
- Light and dark themes follow your system

## Install

With [Homebrew](https://brew.sh):

```sh
brew install --cask kakilangit/tap/shokirei
```

Or download `Shokirei-<version>-universal.dmg` from
[Releases](https://github.com/kakilangit/shokirei/releases/latest) and drag Shokirei to
Applications. Runs on Apple silicon and Intel Macs.

> [!NOTE]
> Shokirei isn't notarized yet, so macOS blocks it at first. Homebrew takes care of that for you.
> If you installed from the `.dmg`, run:
>
> ```sh
> xattr -cr /Applications/Shokirei.app
> ```

On your first capture, macOS asks for the Screen Recording permission (System Settings → Privacy &
Security → Screen Recording). Updates keep it.

## Feedback

Shokirei is young and improving fast. Bug reports and ideas are welcome in
[Issues](https://github.com/kakilangit/shokirei/issues).

## License

Free to use. See [LICENSE](LICENSE).
