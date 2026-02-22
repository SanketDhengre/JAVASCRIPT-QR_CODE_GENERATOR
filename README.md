# ⬛ QR Studio Pro

<p align="center">
  <img src="https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JavaScript-black?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Design-Glassmorphism%20Split%20Panel-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Library-QR%20Code%20Styling-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
</p>

<p align="center">
  A premium, Silicon Valley-grade QR Code design studio built with pure HTML, CSS, and JavaScript.<br>
  No frameworks. No backend. No API calls. Just beautiful, styled QR codes — generated entirely in your browser.
</p>

---

## ✨ Features

### 🎨 6 Style Presets
| Style | Description |
|---|---|
| **Classic** | High-contrast square modules for maximum scanner compatibility |
| **Rounded** | Soft extra-rounded dots and corner frames — modern and elegant |
| **Dots** | Every module rendered as a perfect circle — very artistic |
| **Gradient** | Purple-to-blue linear gradient swept across all dots — truly stunning |
| **Classy** | Circular corner markers with stylized inner dot patterns |
| **Dark** | Inverted — crisp white modules on a deep black background |

### 🌈 6 Color Themes
Apply any solid color to Classic, Rounded, Dots, Classy, or Dark presets:
`Obsidian` · `Violet` · `Electric` · `Rose` · `Emerald` · `Amber`

### ⚡ Power Features
- **Live Preview** — QR code auto-generates 600ms after you stop typing
- **Scan-line animation** — a purple laser sweep plays while rendering
- **Copy to Clipboard** — copies the QR code as a PNG directly to your clipboard
- **Download PNG** — saves a high-quality export to your computer
- **Toast Notifications** — smooth feedback messages after copy/download
- **`Ctrl+Enter` / `Cmd+Enter`** — keyboard shortcut to generate instantly
- **Shake validation** — empty input triggers a smooth shake animation, no alerts
- **Error Correction Level H** — 30% damage recovery so artistic styles still scan reliably
- **Zero dependencies** — single HTML file, no npm, no build step, no framework

---

## 🖥️ Preview

> A professional split-panel UI: QR preview on the left, style + color controls on the right.  
> Powered by the [QR Code Styling](https://github.com/kozakdenys/qr-code-styling) library for client-side rendering.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 Semantic Markup |
| Styling | Vanilla CSS (Glassmorphism, CSS Grid, Custom Properties, Animations) |
| Logic | Vanilla JavaScript (ES6+, Async/Await, ClipboardAPI) |
| QR Engine | [QR Code Styling v1.6](https://github.com/kozakdenys/qr-code-styling) (client-side canvas rendering) |
| Typography | [Inter](https://fonts.google.com/specimen/Inter) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) |

---

## 🚀 Getting Started

### Option 1 — Just Open It (Simplest)
```bash
git clone https://github.com/SanketDhengre/JAVASCRIPT-QR_CODE_GENERATOR.git
cd JAVASCRIPT-QR_CODE_GENERATOR

# Windows
start index.html

# macOS / Linux
open index.html
```

### Option 2 — Local Dev Server (Python)
```bash
python -m http.server 8000
# Then open → http://localhost:8000
```

### Option 3 — VS Code Live Server
1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension
2. Right-click `index.html` → **Open with Live Server**

---

## 📖 How to Use

1. **Enter your payload** — Type any URL, plain text, Wi-Fi credentials, or contact info into the input field. The QR code starts generating automatically after you pause typing.
2. **Pick a style** — Choose from 6 visual presets: Classic, Rounded, Dots, Gradient, Classy, or Dark.
3. **Pick a color** — Select one of 6 color themes (applies to non-gradient styles).
4. **Generate** — Click **Generate Code** or press `Ctrl+Enter`.
5. **Export** — Hit **Copy** to send the PNG to your clipboard, or **Download** to save the file locally.

---

## 📐 Design Philosophy

> *"Design is not just what it looks like and feels like. Design is how it works."* — Steve Jobs

Every decision in this project was intentional:

- **Split-panel layout** — Controls and output live side-by-side, like a real design tool
- **No API calls** — QR codes render entirely on-device using canvas, making it instant and offline-capable
- **No alerts or popups** — Validation is communicated through motion (shake animation)
- **No configuration overload** — The most complex output parameter (resolution) is set to Ultra HD automatically
- **Living preview** — The code updates live as you type, making it feel immediate and responsive

---

## 👤 Author

**Sanket Dhengre**

> Engineered with precision. Designed with intent.

- 🐙 GitHub: [@SanketDhengre](https://github.com/SanketDhengre)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
