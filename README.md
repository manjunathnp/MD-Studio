<p align="center">
  <img src="https://github.com/manjunathnp/MD-Studio/releases/download/v1.0.0/logo.png" alt="MD-Studio logo" width="240">
</p>

# MD-Studio v1.0.0

An offline Markdown editor with live preview, formatting tools, and ready-to-use testing templates. Open one HTML file in your browser—no installation or build step required.

![MD-Studio editor showing a test plan](https://github.com/manjunathnp/MD-Studio/releases/download/v1.0.0/screenshot.png)

MD-Studio v1.0.0 screenshot

## Get started

1. Download [MD-Studio-v1.0.0.html](https://github.com/manjunathnp/MD-Studio/releases/download/v1.0.0/MD-Studio-v1.0.0.html) from the [v1.0.0 release](https://github.com/manjunathnp/MD-Studio/releases/tag/v1.0.0).
2. Open it in a modern desktop browser.
3. Type Markdown, open a `.md`, `.markdown`, or `.txt` file, or choose a template.
4. Export your work to keep a separate copy.

The HTML embeds its logo, favicon, styles, and scripts. Downloading the HTML alone is enough; no assets folder is required. README images are hosted as GitHub release attachments. Remote images or links in your Markdown may still require internet access.

## Features

- Side-by-side editor and live preview with a draggable divider.
- Headings, emphasis, lists, tasks, quotes, tables, links, images, and fenced code blocks.
- Bug Report, Test Case, Test Plan, Regression Checklist, and API Test Notes templates.
- Markdown and rendered HTML clipboard actions.
- Markdown, HTML, Word-compatible `.doc`, and PDF export through the browser print dialog.
- Light and dark themes, fullscreen preview, a Markdown cheat sheet, and document statistics.
- Browser-local draft autosave.

## Shortcuts

| Shortcut | Action |
|---|---|
| Ctrl/Cmd+B | Bold |
| Ctrl/Cmd+I | Italic |
| Ctrl/Cmd+K | Link |
| Tab | Insert two spaces |
| Esc, then Tab | Move focus out of the editor |
| Esc | Close an open panel or exit fullscreen preview |

## Files

```text
MD-Studio/
├── MD-Studio-v1.0.0.html
└── README.md
```

## Developed by

**Manjunath N P**

[manjunathnp.in](https://manjunathnp.in) · [LinkedIn](https://linkedin.com/in/manjunathnp) · [GitHub](https://github.com/manjunathnp)

## License

MD-Studio identifies its application source as MIT licensed. The included third-party libraries and brand marks retain their respective licences and rights.

## Publishing checks

The primary download uses a release attachment so the browser downloads the HTML directly. Release attachments do not update when code is pushed. When publishing an HTML update, upload the intended release asset, download it through the public release link, and verify its SHA-256 matches the HTML from the intended commit before announcing the release.
