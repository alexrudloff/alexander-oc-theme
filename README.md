# alexander

A neon cyberpunk / Miami Vice inspired theme for [OpenCode](https://opencode.ai).

## Preview

Dark mode with electric cyan, magenta, green, and yellow highlights on a deep navy background. Warm orange-red for errors and structural elements. Near-white text for readability.

## Colors

| Role | Hex |
|------|-----|
| Background (main) | `#0E1422` |
| Background (sidebar) | `#161922` |
| Cyan (primary) | `#00D4FF` |
| Magenta (accent) | `#D946FF` |
| Green (success) | `#39FF14` |
| Yellow (warning) | `#FFE600` |
| Sky (info) | `#00E5FF` |
| Coral (error) | `#FF6B4A` |

## Installation

### Option 1: Copy the theme file

```bash
mkdir -p ~/.config/opencode/themes
cp alexander.json ~/.config/opencode/themes/
```

Then open OpenCode and run `/theme` to select **alexander**.

### Option 2: Clone the repo

```bash
git clone https://github.com/alexrudloff/alexander-oc-theme.git
cp alexander-oc-theme/alexander.json ~/.config/opencode/themes/
```

### Option 3: Direct download

Download [alexander.json](https://raw.githubusercontent.com/alexrudloff/alexander-oc-theme/main/alexander.json) and place it in `~/.config/opencode/themes/`.

## Requirements

- OpenCode >= latest
- Terminal with **truecolor** (24-bit) support

Check with: `echo $COLORTERM` — should output `truecolor` or `24bit`.

## License

MIT
