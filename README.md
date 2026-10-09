# Offline HTML Formatter & Minifier

> A lightweight, zero-dependency, client-side HTML beautifier, prettifier, and minifier contained in a single offline HTML file.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Dependencies: None](https://img.shields.io/badge/dependencies-none-brightgreen.svg)]()
[![Privacy: 100% Client-Side](https://img.shields.io/badge/privacy-100%25%20local-success.svg)]()

A fast, private, and portable in-browser developer tool to tidy, format, structure, or compress HTML markup. It requires **no installation, no build steps, no Node.js runtime, and no internet access**. 

---

## Why Use This HTML Formatter?

* **100% Client-Side Privacy**: Code never leaves your machine. Safe for proprietary code, internal templates, and sensitive intranet data.
* **Zero Dependencies**: Entirely standalone. Built in pure vanilla JavaScript, HTML5, and CSS.
* **Offline-First**: Save `html-formatter.html` to your local drive or USB stick and run it anywhere—even without network access.
* **Dual Engine**: Instantly switch between pretty-printing (beautification) and code minification (file size compression).

---

## Key Features

* **HTML Beautifier & Pretty-Printer**:
  * Indentation options: 2 spaces, 4 spaces, 8 spaces, or raw tabs.
  * Intelligent line wrapping (80, 120, 160 characters, or disabled).
  * Auto-wraps long tag attributes into clean multi-line elements.
  * Preserves `<pre>`, `<code>`, and `<textarea>` content strictly as-is.
* **Embedded Language Support**:
  * Formats CSS declarations inside `<style>` tags.
  * Re-indents JavaScript inside `<script>` blocks.
  * Formats and pretty-prints embedded JSON-LD schema (`application/ld+json`).
* **HTML Minifier & Compressor**:
  * Strips whitespace, unnecessary breaks, and non-essential characters.
  * Removes standard comments while safely keeping conditional comments (`<!--[if IE]>`).
* **Syntax & Structural Diagnostics**:
  * Identifies unclosed tags and mismatched closing tags with explicit line numbers without altering your source structure.
* **Developer Workflow UI**:
  * Drag-and-drop file upload, clipboard copy, and `.html` file export.
  * Automatic dark/light theme detection matched to system preferences.
  * Persistent local settings (retains your formatting preferences across sessions).

---

## Quick Start

1. Download or clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git
