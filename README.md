<p align="center">
  <br/>
  <img src="https://img.shields.io/github/stars/hututu-ai/new-brutalism-theme?style=for-the-badge&logo=github&logoColor=000&labelColor=eee&color=84cc16" alt="stars">
  <img src="https://img.shields.io/badge/dynamic/json?style=for-the-badge&logo=visual-studio-code&logoColor=000&labelColor=eee&color=84cc16&label=installs&query=$.installationCount&url=https://vs-util.vercel.app/api/installs/new-brutalism-light" alt="installs">
  <img src="https://img.shields.io/badge/license-MIT-84cc16?style=for-the-badge&logo=&labelColor=eee" alt="license">
  <img src="https://img.shields.io/badge/version-0.1.0-84cc16?style=for-the-badge&logo=&labelColor=eee" alt="version">
  <br/>
  <br/>
</p>

<h1 align="center">
  🌱 New Brutalism Light
</h1>

<p align="center">
  <b>A brutalist light theme for VS Code</b><br/>
  Pure black borders. Lime green accents. White cards on light gray. Hard shadows.
</p>

<p align="center">
  <code>#f7f7f7</code> · <code>#ffffff</code> · <code>#000000</code> · <code>#84cc16</code>
</p>

<br/>

<p align="center">
  <i>New Brutalism (新粗野风) — bold, raw, unapologetic.</i>
</p>

<br/>

## 👀 Preview

> Open [`preview.html`](preview.html) in your browser for a full visual walkthrough.

```
┌─────────────────────────────────────────────────────────┐
│  🌱 New Brutalism Light                                 │
│  ┌─────────────────────────────────────────────────────┐│
│  │  const theme: Theme = {                            ││
│  │    name: "New Brutalism Light",  ← lime green       ││
│  │    type: "light",                                    ││
│  │    count: 42,            ← yellow number             ││
│  │  };                                                  ││
│  └─────────────────────────────────────────────────────┘│
│  ● main  ▶  New Brutalism Light    Ln 12, Col 24  UTF-8│
└─────────────────────────────────────────────────────────┘
```

<br/>

## 🧠 Philosophy

**New Brutalism** (新粗野风 / Neo-Brutalism) rejects the polished, invisible UI of modern design. It embraces raw structure, bold contrasts, and intentionally striking aesthetics.

| Principle | Expression |
|-----------|-----------|
| **Pure Black Borders** | Every panel, card, and widget has a `2px solid #000` border |
| **Lime Green Energy** | `#84cc16` as the primary accent — fresh, unmistakable, alive |
| **White on Gray** | White cards on `#f7f7f7` background — clean, structural, honest |
| **Hard Shadows** | `3px 3px 0 #000` — no blur, no opacity, no excuses |
| **No Subtlety** | No gradients. No rounded corners. Every pixel earns its place. |

> *"Good design is invisible." — Modernist mantra*  
> **"Great design punches you in the face." — New Brutalism**

<br/>

## 🎨 Color Palette

| Role | Hex | Sample |
|------|-----|--------|
| **Background** | `#f7f7f7` | <img src="https://placehold.co/15x15/f7f7f7/f7f7f7" alt=""> |
| **Card / Surface** | `#ffffff` | <img src="https://placehold.co/15x15/ffffff/ffffff" alt=""> |
| **Text / Border** | `#000000` | <img src="https://placehold.co/15x15/000000/000000" alt=""> |
| **Primary Accent** | `#84cc16` | <img src="https://placehold.co/15x15/84cc16/84cc16" alt=""> |
| **Light Accent** | `#c7e97a` | <img src="https://placehold.co/15x15/c7e97a/c7e97a" alt=""> |
| **Yellow Accent** | `#fde047` | <img src="https://placehold.co/15x15/fde047/fde047" alt=""> |
| **Dark Green** | `#65a30d` | <img src="https://placehold.co/15x15/65a30d/65a30d" alt=""> |
| **Error Red** | `#dc2626` | <img src="https://placehold.co/15x15/dc2626/dc2626" alt=""> |

### Syntax Highlighting

| Token | Color | Style |
|-------|-------|-------|
| Keywords & Storage | `#84cc16` | **Bold green** |
| Strings & Constants | `#84cc16` | — |
| Functions | `#000000` | **Bold** |
| Types & Classes | `#000000` | **Bold** |
| Numbers | `#fde047` | — |
| Built-ins | `#84cc16` | **Bold** |
| Comments | `#999999` | *Italic* |
| Operators | `#000000` | **Bold** |
| Attributes | `#84cc16` | **Bold** |

<br/>

## 📦 Installation

### Via VS Code Marketplace

```
Extensions (⌘⇧X) → search "New Brutalism Light" → Install
```

### Via CLI

```bash
code --install-extension new-brutalism-light
```

### Via VSIX

1. Download the latest `.vsix` from [Releases](https://github.com/hututu-ai/new-brutalism-theme/releases)
2. Extensions panel → `⋯` → **Install from VSIX...**

### From Source

```bash
git clone https://github.com/hututu-ai/new-brutalism-theme.git
cd new-brutalism-theme
code --install-extension .
```

Then press `⌘K ⌘T` and select **New Brutalism Light**.

<br/>

## ⚙️ Customization

Tweak the theme to your liking in `settings.json`:

```jsonc
{
  "[New Brutalism Light]": {
    "editor.fontFamily": "'JetBrains Mono', 'Source Han Sans CN', monospace",
    "editor.fontWeight": "500",
    "editor.lineHeight": 1.8,
    "editor.letterSpacing": 0.5,
    "editor.bracketPairColorization.enabled": false,
    "editor.renderLineHighlight": "all",
    "editor.roundedSelection": false
  }
}
```

### Override Colors

```jsonc
{
  "workbench.colorCustomizations": {
    "[New Brutalism Light]": {
      "editor.background": "#f0f0f0",
      "sideBar.background": "#fafafa"
    }
  }
}
```

### Disable Italic Comments

```jsonc
{
  "editor.tokenColorCustomizations": {
    "[New Brutalism Light]": {
      "textMateRules": [
        {
          "scope": "comment",
          "settings": { "fontStyle": "" }
        }
      ]
    }
  }
}
```

<br/>

## 🖥️ Screenshots

<details open>
<summary><b>TypeScript</b></summary>

```typescript
interface Theme {
  name: string;
  colors: Record<string, string>;
  activate(): void;
}

class BrutalistTheme implements Theme {
  constructor(public name: string) {}

  activate(): void {
    console.log(`Rendering ${this.name}...`);
  }
}

const count: number = 42;
```
</details>

<details>
<summary><b>Python</b></summary>

```python
from typing import Optional

class BrutalistTheme:
    """A bold, raw theme for VS Code."""

    def __init__(self, name: str) -> None:
        self.name = name
        self.colors = {"bg": "#f7f7f7"}

    def render(self) -> None:
        print(f"Rendering {self.name}...")
```
</details>

<details>
<summary><b>HTML / JSX</b></summary>

```html
<div class="container">
  <h1 id="title">New Brutalism</h1>
  <p>Raw design for raw developers.</p>
  <button onclick="brutalize()" class="primary">🌱</button>
</div>
```
</details>

<details>
<summary><b>CSS</b></summary>

```css
:root {
  --bg: #f7f7f7;
  --border: #000000;
  --accent: #84cc16;
}

.card {
  background: #fff;
  border: 2px solid #000;
  box-shadow: 3px 3px 0 #000;
}

.card:hover {
  transform: translate(-2px, -2px);
}
```
</details>

<br/>

## 🏗️ Development

```bash
git clone https://github.com/hututu-ai/new-brutalism-theme.git
cd new-brutalism-theme

# Open in VS Code — press F5 to start Extension Dev Host
code .

# Package into .vsix
npm install -g @vscode/vsce
vsce package

# Publish to Marketplace
vsce publish
```

<br/>

## 🙏 Credits

- Inspired by the **Neo-Brutalism** design movement and [Creator OS](https://github.com) dashboard
- Color palette built around `#84cc16` — the perfect lime green
- Built for developers who believe UI should have an opinion

<br/>

## 📄 License

[MIT](LICENSE) © hututu-ai

---

<p align="center">
  <sub>Made with 🌱 thick borders and green energy.</sub>
</p>
