# Magic GPX Editor — Support Website

This folder contains the support website hosted on GitHub Pages at [jamesmoriarty.github.io/gpx-editor](https://jamesmoriarty.github.io/gpx-editor/).

## Reporting a bug or requesting a feature

Please [open a GitHub issue](https://github.com/jamesmoriarty/gpx-editor/issues/new) with:

- **Bug reports**: macOS version, app version (shown in the top bar), steps to reproduce, and what you expected vs. what happened. Attach a sample `.gpx` file if relevant.
- **Feature requests**: describe the workflow you're trying to achieve and why the current app doesn't cover it.

For private matters (billing, account questions) email [jamespaulmoriarty@proton.me](mailto:jamespaulmoriarty@proton.me).

## Files

| File | Purpose |
|---|---|
| `index.html` | Main support page |
| `styles.css` | Stylesheet |
| `screenshot.png` | Hero screenshot shown on the page |
| `icon.png` | App icon used in the top bar |
| `privacy.txt` | Privacy policy |

## Local development

```bash
cd docs
python3 -m http.server 8000
# Open http://localhost:8000
```

## Deploying

The site deploys automatically via GitHub Pages from the `/docs` folder on the `main` branch. Push to `main` and changes are live within a minute.
