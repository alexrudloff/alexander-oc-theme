# alexander

A neon cyberpunk / Miami Vice inspired theme for [OpenCode](https://opencode.ai).

## Preview

[View swatch →](swatch.html)

Dark mode with electric cyan, magenta, green, and yellow highlights on a deep navy background. Warm orange-red for errors and structural elements. Near-white text for readability.

## Colors

### Dark Mode

| Color | Hex | Usage |
|-------|-----|-------|
| <span style="display:inline-block;width:12px;height:12px;background:#0E1422;border-radius:2px;vertical-align:middle"></span> | `#0E1422` | Main background |
| <span style="display:inline-block;width:12px;height:12px;background:#161922;border-radius:2px;vertical-align:middle"></span> | `#161922` | Sidebar background |
| <span style="display:inline-block;width:12px;height:12px;background:#FF6B4A;border-radius:2px;vertical-align:middle"></span> | `#FF6B4A` | Error, keywords, operators |
| <span style="display:inline-block;width:12px;height:12px;background:#00D4FF;border-radius:2px;vertical-align:middle"></span> | `#00D4FF` | Primary, syntax functions |
| <span style="display:inline-block;width:12px;height:12px;background:#D946FF;border-radius:2px;vertical-align:middle"></span> | `#D946FF` | Accent, syntax types |
| <span style="display:inline-block;width:12px;height:12px;background:#FFE600;border-radius:2px;vertical-align:middle"></span> | `#FFE600` | Warning, numbers |
| <span style="display:inline-block;width:12px;height:12px;background:#00E5FF;border-radius:2px;vertical-align:middle"></span> | `#00E5FF` | Info, syntax variables |
| <span style="display:inline-block;width:12px;height:12px;background:#39FF14;border-radius:2px;vertical-align:middle"></span> | `#39FF14` | Success, strings |

[View full swatch →](swatch.html)

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
