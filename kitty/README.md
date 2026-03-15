# Kitty Terminal Configuration

A clean, modern configuration for [Kitty Terminal](https://sw.kovidgoyal.net/kitty/) with transparency, blur effects, and a dark theme.

<img width="800" alt="image" src="https://github.com/user-attachments/assets/2f9757c6-ecd2-4ede-9296-44fb307e83fa" />

## ✨ What's included

🎨 **Modern aesthetics**

- Semi-transparent background (85% opacity)
- Subtle blur effect for depth
- Clean dark theme with blue accents

⚡ **Enhanced productivity**

- 10,000 lines of scrollback history
- Automatic URL detection and styling
- Opens directly in your development folder

🚀 **Optimized workflow**

- Intuitive keyboard shortcuts
- Cross-platform keybindings
- Minimal borders for clean look

## Installation

1. Install Kitty:

   ```bash
   # macOS
   brew install kitty

   # Linux
   curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh /dev/stdin
   ```

2. Copy configuration:

   ```bash
   # Backup existing config
   mv ~/.config/kitty ~/.config/kitty.backup

   # Apply this config
   cp -r /path/to/this/config ~/.config/kitty
   ```

3. Restart Kitty

## Key Bindings

| Action        | macOS     | Linux/Alt |
| ------------- | --------- | --------- |
| New tab       | `Cmd+T`   | `Ctrl+T`  |
| New window    | `Cmd+N`   | `Ctrl+N`  |
| Close tab     | `Cmd+W`   | `Alt+W`   |
| Close window  | `Cmd+⇧+W` | `Ctrl+W`  |
| Next tab      | `Cmd+]`   | `Alt+]`   |
| Previous tab  | `Cmd+[`   | `Alt+[`   |
| Go to tab 1-9 | `Cmd+1-9` | `Alt+1-9` |

## Customization

**Change transparency:**

```conf
background_opacity 0.85  # 0.0 = transparent, 1.0 = opaque
```

**Change startup directory:**

```
cd /your/preferred/directory
```

**Adjust blur:**

```conf
background_blur 15  # pixels (0 to disable)
```

## Color Scheme

- Background: `#1f1f1f`
- Foreground: `#f8f8f8`
- Accent: `#79b8ff`
- Selection: `#79b8ff`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

_Clean terminal setup for modern development_ ⚡
