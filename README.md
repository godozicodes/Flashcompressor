# FlashCompressor ⚡

A free, privacy-first browser file compressor. FlashCompressor processes files locally on your device — no sign-up and no upload server.

## Features

- **Smart compression** for common images and text/code files.
- **ZIP any file type** — PDFs, videos, documents, archives, apps, and more can be bundled into a DEFLATE ZIP.
- Adjustable image quality and maximum dimensions.
- Multiple-file drag-and-drop.
- Shows original size, output size, and savings.
- Works as a static site on Vercel or any static host.

> Important: not every file format can be made smaller by recompressing it. FlashCompressor never pretends a larger output is a successful compression; use **ZIP any files** when you need a universal container.

## Run locally

Open `index.html` in a modern browser or serve the folder with any static web server.

## Privacy

Compression happens in the browser. The app does not send selected files to a FlashCompressor backend. The ZIP mode uses JSZip from jsDelivr.
