# Matrix

A dark terminal/CRT theme for [NetNewsWire](https://netnewswire.com), built around a phosphor-green monospace aesthetic.

## Features

### Visual Style
- **Phosphor-green palette** — deep near-black background (`#0a0f0a`) with glowing green text, amber inline code, and red accents
- **CRT vignette** — a radial gradient overlay darkens the screen edges for a vintage monitor feel (macOS only)
- **Boot flicker** — the page and article animate in with a CRT power-on flicker effect
- **Monospace throughout** — SF Mono, Fira Code, Menlo, and Courier New form the font stack

### Article Header
- Feed name is prefixed with a shell prompt: `user@nnw:~$ cat`
- Publish date is prefixed with `# timestamp:`
- External link is prefixed with `# source:`
- Feed icon is rendered in greyscale with a green tint and a pixel-art rendering mode

### Article Title
- **Typewriter animation** — the title types out character by character in reading order, correctly handling titles that span multiple lines
- **Blinking block cursor** (`█`) appears after the last character lands and blinks indefinitely

### Article Body
- Separator line of `─` characters between the header and body
- Headings prefixed with Markdown-style `##`, `###`, `####` markers
- Blockquotes styled with a left border and faint green background
- Code blocks include a fake terminal title bar (`● ● ●  output`) and horizontal scroll on overflow
- Inline code highlighted in amber with a subtle glow
- Tables use uppercase headers, row hover highlights, and a green glow on the border
- Figcaptions prefixed with `// `
- Images are desaturated and dimmed; hovering partially restores colour

### Platform Behaviour
- **iOS** — uses dynamic type sizing, system hyphenation, and respects safe area insets; `html` background is set so native navigation and tab bar blur effects sample the correct dark colour
- **macOS** — includes the CRT vignette, wider padding, and fixed text-size classes (`smallText` → `xxlargeText`)

### Third-party Support
- **Newsfoot** footnote popovers are styled to match the theme
- **Feedbin** article wrappers receive a matching top border

## Installation

1. Download or clone this repository
2. Double-click `Matrix.nnwtheme` to install it into NetNewsWire

## Requirements

- NetNewsWire 6.1 or later
- JavaScript must be enabled in NetNewsWire article settings (required for the typewriter animation)

## Credits

Created by [Stuart Breckenridge](https://stuartbreckenridge.net), developed with the help of [Claude](https://claude.ai).
