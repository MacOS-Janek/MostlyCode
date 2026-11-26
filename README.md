# Mostly Code website

A responsive black-and-violet landing page for Mostly Code. It uses plain HTML and CSS (no build tools, frameworks, or external libraries).

## Files

- `index.html` — the complete website.
- `MostlyCode.exe` — **not included**; add your actual, built Windows application executable.

## Make the Download button work

Put the real `MostlyCode.exe` in the same folder as `index.html`:

```text
mostly-code-website/
├── index.html
├── README.md
└── MostlyCode.exe
```

Both the navigation Download button and the hero/footer buttons link to `./MostlyCode.exe` and request the browser to download it with that filename.

## Preview locally

Open `index.html` in a browser. The landing page itself needs no server, login, package manager, or external libraries.

## Publish

Upload `index.html` and the matching `MostlyCode.exe` together to your static website host. Keep the executable at the same path as `index.html`, or update the three `href="./MostlyCode.exe"` links to match the URL where you host it.

The executable is intentionally not fabricated or replaced with a placeholder. Add your actual compiled Windows `.exe` before publishing so the download link points to a real application.
