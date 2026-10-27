# PDF Flipbook

Turn any PDF into a book you can flip through, right in your browser. It's a single HTML file with no server and no sign-in, and your PDF never leaves your device.

## Use it

**Online:** https://nfahmye.github.io/Book-Reader/ (works on phones too; on iPhone, use Share → Add to Home Screen to open it like an app).

**Offline copy:** download `pdf-flipbook.html` and open it in a browser (Chrome, Edge, Safari, Firefox).

Then tap **Open PDF** or drag a PDF onto the page. The first visit needs an internet connection to load the PDF engine from a CDN.

## Features

- **Realistic book:** two-page spreads on wide screens with the cover shown alone; a single page on phones, switching when you rotate. Page curl, spine shading and soft shadows.
- **Turning pages:** drag a page corner, swipe, tap the left or right edge, or use the arrow keys. Soft paper sound (with mute).
- **Getting around:** page slider, "go to page", and a thumbnail grid.
- **Zoom:** pinch, double-tap, buttons or Ctrl+scroll. Zoomed text is redrawn at the screen's full resolution, as sharp as a native PDF viewer.
- **Highlights:** drag across text in four colours; tap a highlight to recolour, copy or remove it. Highlights list with "Copy all".
- **Bookmarks:** ribbon on bookmarked pages and a bookmarks list.
- **Reading comfort:** remembers your page for each book and offers to continue; night mode (sepia); light/dark background.
- **Big books:** pages render lazily as you approach them, so 200+ page PDFs stay smooth.
- **Friendly errors** for wrong file types, damaged files, password-protected PDFs (with a password prompt) and files over 300 MB.

Bookmarks, highlights and your last page are saved in the browser on that device (localStorage), keyed by file name and page count.

## Keyboard

| Key | Action |
|---|---|
| ← / → , Page Up / Page Down, Space | Previous / next page |
| Home / End | First / last page |
| + / − / 0 | Zoom in / out / reset |
| H | Highlighter on/off |
| B | Bookmark this page |
| F | Fullscreen |
| Esc | Close panels, leave highlighter, reset zoom |

## Built with

- [PDF.js](https://mozilla.github.io/pdf.js/) 3.11.174 (legacy build) for rendering
- [StPageFlip](https://github.com/Nodlik/StPageFlip) 2.0.7 for the page-turn effect
