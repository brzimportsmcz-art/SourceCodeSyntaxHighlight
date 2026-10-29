<p align="center">
  <img src="assets/hyperquickview-icon.png" width="160" height="160" alt="HyperQuickView icon" />
</p>

<h1 align="center">HyperQuickView</h1>

<p align="center">
  A fast, native macOS file inspector and Quick Look companion.<br/>
  Swift 6 · SwiftUI · Apple Silicon
</p>

<p align="center">
  <a href="https://maceiofred.gumroad.com"><img alt="Get it on Gumroad" src="https://img.shields.io/badge/Get%20it%20on-Gumroad-ff90e8?logo=gumroad&logoColor=white" /></a>
  <img alt="macOS 14+" src="https://img.shields.io/badge/macOS-14%2B-blue" />
  <img alt="Swift 6" src="https://img.shields.io/badge/Swift-6-orange" />
</p>

HyperQuickView previews and inspects almost any file you throw at it: source code, Markdown, JSON/Plist/XML, binaries, images, PDFs and whole folders. It shows what a file *is* (UTI, MIME type, permissions, checksums, magic bytes), not only what it looks like.

## Features

- **Syntax highlighting** with built-in themes: *Hyper Dark*, *Tokyo Night*, *Dracula*, *GitHub Dark*, *One Dark Pro*, *GitHub Light*, *Solarized Light*.
- **Rendered Markdown** with headers, lists, code blocks and word count.
- **Structured data (JSON / Plist / XML):** automatic beautification, validation and copy actions.
- **Hex view:** 16-byte hex + ASCII dump with magic-byte detection (Mach-O 64-bit ARM64, PDF, PNG, JPEG, ZIP, ...).
- **Media canvas:** zoom, aspect-ratio and dimension overlay, transparency checkerboard.
- **PDF reader:** native PDFKit multi-page viewer.
- **System Quick Look:** one-key trigger (`Space`) plus an embedded `QLPreviewView`.
- **Workspace navigation:** recursive directory tree with file-type icons.
- **Deep file inspector:** UTI, MIME type, POSIX permissions, size, line/word counts, async SHA-256 and MD5.
- **Drag & drop:** drop any file or folder on the window to inspect it.

| Shortcut | Action |
|:--|:--|
| `Cmd+O` | Open file or folder |
| `Space` | System Quick Look |
| `Cmd+Shift+R` | Reveal in Finder |
| `Cmd+Shift+C` | Copy file path |
| `Cmd+Opt+I` | Toggle technical inspector |
| `Cmd+,` | Settings and theme selector |

## Get HyperQuickView

Requires macOS 14 or later (built on Apple Silicon).

**[Get it on Gumroad](https://maceiofred.gumroad.com)**

## Support the project

HyperQuickView is built and maintained by one person. Buying or tipping on **[Gumroad](https://maceiofred.gumroad.com)** is the best way to support new themes, file formats and fixes.

## About this repository

This repository is a fork of [Syntax Highlight](https://github.com/sbarex/SourceCodeSyntaxHighlight) by sbarex, a Quick Look extension for source files built on André Simon's [Highlight](http://www.andre-simon.de/doku/highlight/en/highlight.php) engine. The forked code remains under the **GNU GPL v3** (see `LICENSE.txt`), and all credit for it belongs to its original authors. HyperQuickView is a separate app by Frederico Moreira.

## Author

**Frederico Moreira** ([@hypervanse](https://x.com/hypervanse)), Maceió, Brazil.
