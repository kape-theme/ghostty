# ☕ Kape for Ghostty

Kape is a warm, dark color scheme for **Ghostty** terminal emulator, rooted in coffee, earth, and amber tones.

## Installation

### Option 1: Manual Installation

1. Create the themes directory if it doesn't exist:
   ```bash
   mkdir -p ~/.config/ghostty/themes
   ```

2. Copy the theme file:
   ```bash
   cp kape ~/.config/ghostty/themes/
   ```

3. Enable the theme in your Ghostty configuration:
   - Open or create `~/.config/ghostty/config`
   - Add the following line:
     ```
     theme = kape
     ```

4. Reload Ghostty or restart the application for changes to take effect

### Option 2: Using Git (Recommended for Updates)

1. Navigate to your Ghostty themes directory:
   ```bash
   cd ~/.config/ghostty/themes
   ```

2. Clone this repository:
   ```bash
   git clone https://github.com/kape-theme/ghostty.git kape
   ```

3. Add to your `~/.config/ghostty/config`:
   ```
   theme = kape
   ```

4. To update in the future:
   ```bash
   cd ~/.config/ghostty/themes/kape
   git pull
   ```

## Color Palette

| Color | Value |
|-------|-------|
| Background | `#181616` |
| Foreground | `#d4be98` |
| Red | `#b53535` |
| Green | `#b4c76e` |
| Yellow | `#e7bb5c` |
| Blue | `#7b8fd4` |
| Purple | `#b06880` |
| Cyan | `#689d8a` |
| White | `#c2c2c2` |

See the main [Kape repository](https://github.com/kape-theme/kape) for the complete palette with RGB and HSL values.

## Customization

You can customize specific colors by editing `~/.config/ghostty/config`:

```
theme = kape
# Override specific colors
palette = 1=#ff0000  # Override red
```

## Contributing

Found an issue or have a suggestion? Open an issue or PR on the [main Kape repository](https://github.com/kape-theme/kape).

## License

MIT © gabiuz
