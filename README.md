# skimly

Chrome extension that summarizes the current page with an LLM

## How to use

```bash
# open any article, click the icon, get a 5-bullet summary
```

## Getting started

```bash
# chrome://extensions -> load unpacked -> select this folder
# set your API base + key on the options page
```

## Features

- Reads the page, extracts main text, sends to your endpoint
- Manifest V3 service worker, no build step
- Popup shows a 5-bullet summary
- Options page for API base and key

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   └── config.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── options.html
├── popup.html
└── popup.js
```

## License

MIT. Do whatever you want.
