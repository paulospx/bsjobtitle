# Bullshit Job Title Generator

A lightweight, single-page web app that instantly creates absurdly corporate-sounding job titles — perfect for satire, fiction, presentations, or a quick laugh.

**[Try it live →](https://paulospx.github.io/bsjobtitle/index.html)**

## What it does

Click **Generate another title** and the app randomly combines three word lists into titles like *Senior Paradigm Orchestrator* or *Global Solutions Strategist*. Each click produces a new result with no setup, accounts, or data collection.

## Features

- **One-click generation** — no forms, sign-in, or configuration
- **Copy to clipboard** — share your favorite title in one step
- **Keyboard accessible** — works with Tab, Enter, and Space
- **Screen reader friendly** — generated titles are announced automatically
- **Works offline** — open `index.html` locally; no server required
- **Mobile friendly** — responsive layout for phones and tablets

## Quick start

### Use online

Open the [live demo](https://paulospx.github.io/bsjobtitle/index.html) in any modern browser.

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/paulospx/bsjobtitle.git
   cd bsjobtitle
   ```
2. Open `index.html` in your browser (double-click the file or use a local server).

No build step, package manager, or backend is required.

## How it works

The generator picks one word from each of three lists and joins them:

| Part | Examples |
|------|----------|
| Prefix | Lead, Senior, Global, Chief |
| Middle | Solutions, Paradigm, Branding, Metrics |
| Suffix | Manager, Strategist, Orchestrator, Analyst |

All logic runs in the browser with plain HTML, CSS, and JavaScript.

## Project structure

```
bsjobtitle/
├── index.html          # Main app
├── css/
│   ├── bootstrap.min.css
│   └── signin.css      # App styles
├── img/
│   └── manager.png     # Header illustration
├── LICENSE
└── README.md
```

## Browser support

Works in current versions of Chrome, Firefox, Safari, and Edge. Clipboard copy requires a secure context (HTTPS or `localhost`).

## License

MIT — see [LICENSE](LICENSE).

## Contributing

Found a word that belongs in the generator? Open an issue or pull request on [GitHub](https://github.com/paulospx/bsjobtitle).

If this made you smile, consider giving the project a ⭐.