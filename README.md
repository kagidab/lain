# lain

A Wikipedia interface styled after Serial Experiments Lain's cyberpunk aesthetic.

## Features

- **Copland OS boot sequence**: Authentic startup animation referencing Tachibana Labs, Accela, PHANTOMa, MJ-12, and Knights of the Eastern Calculus
- **Animated data stream background**: Throttled (~20fps) falling glyphs — katakana, binary, kanji (玲音 / 神) — for performance without sacrificing atmosphere
- **Phantom presence orbs**: CSS-only floating radial gradient blobs that drift across the background
- **Typing quote rotation**: Lain quotes appear with a typewriter cursor effect and cycle automatically
- **Protocol status bar**: Live clock, connection indicator, layer tracking, Accela & PHANTOMa labels
- **Layer cycling**: Each search advances through the 13 episode layers (WEIRD, GIRLS, PSYCHE, etc.)
- **Navi-inspired UI frame**: Pulsing corner brackets with inner tick marks, dual side data tickers
- **CRT effects**: Scanlines, vignette, CSS noise texture overlay, colored sweeping glitch bar
- **Chromatic aberration glitch**: Title splits into red/cyan channels with hue-rotate and skew distortion
- **Search focus dim**: Screen darkens and UI fades when typing for immersive focus
- **Signal degradation**: Footer text glitches and distorts periodically
- **Custom crosshair cursor**: Inline SVG data URI cursor — no external assets
- **Breathing borders**: Search input pulses with a subtle neon glow animation
- **Wikipedia search integration**: Real-time search using Wikipedia's API
- **Responsive layout**: Works on desktop and mobile devices

## Usage

Simply open `index.html` in a web browser to access the interface.

1. Watch the Copland OS boot sequence initialize
2. Enter your search query in the search box
3. Press Enter or click the SEARCH button
4. Browse Wikipedia articles in the signature Lain style
5. Each search advances the layer counter through all 13 episodes

## Technical Details

- Pure HTML/CSS/JavaScript - no dependencies required
- Uses Wikipedia's public API
- Client-side only - can be hosted anywhere
- Canvas-based animated background
- Features include:
  - Copland OS boot sequence with cursor animation
  - Falling data stream canvas throttled to ~20fps (draws every 3rd frame)
  - Wider column spacing (30px) for fewer draw calls
  - CSS-only noise texture via repeating-conic-gradient
  - Floating phantom orbs (CSS animations, no JS)
  - CRT scanline and vignette overlays (consolidated — removed unused layers)
  - Colored horizontal glitch bar with gradient
  - Aggressive chromatic aberration on title (hue-rotate, skew, brightness flashes)
  - Typing effect for rotating Lain quotes
  - Protocol status bar with live clock
  - Pulsing Navi corner frame decorations with inner tick marks
  - Dual ambient side tickers (both edges)
  - Layer indicator pips and episode name cycling
  - Search focus dims the screen
  - Breathing neon glow on search input
  - Signal degradation animation on footer
  - Custom crosshair cursor (inline SVG)
  - Staggered result entry animations
  - Multi-line loading sequence messages
  - No backdrop-filter or unnecessary GPU compositing

## Theme

Deeply inspired by Serial Experiments Lain, this interface recreates the show's atmosphere:
- Monospace Courier New fonts throughout
- Abyss-dark backgrounds (#06040c, #0a0618)
- Violet/purple palette (#d4a0ff, #9070b8, #5a4090, #2a1545)
- Copland OS and Tachibana Labs references
- Accela enhancement module and PHANTOMa service
- MJ-12 surveillance reference
- Navi-style interface frame elements with pulsing glow
- Protocol 7 and Schumann resonance references
- Episode layer names (WEIRD through EGO)
- Knights of the Eastern Calculus mention
- "Let's all love Lain" and "God is here" quotes
- "Present day, present time" and classic Lain quotes
- Japanese katakana and kanji in data streams (レイン / 玲音 / 神)
- Custom crosshair cursor evoking surveillance/Wired presence

## License

Public domain - use freely.