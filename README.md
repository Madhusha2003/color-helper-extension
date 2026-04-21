![Status](https://img.shields.io/badge/Status-Ongoing_Project-orange)
# Universal Color Picker for VS Code

A lightweight Visual Studio Code extension that detects and previews colors across **all file types**, with an integrated color picker for quick editing.

---

## Features

*  Works in **any file** (Python, JavaScript, JSON, Markdown, etc.)
*  Detects and previews:

  * HEX colors (`#ff0000`)
  * RGB (`(255, 0, 0)`)
  * RGBA (`rgba(255, 0, 0, 0.5)`)
* Click on color → open built-in color picker
* Fast and lightweight (no language dependency)
* Real-time color detection as you type

---

## Example

```python
primary = (255, 0, 0)
secondary = #00ff00
transparent = rgba(255, 0, 0, 0.5)
```

✔ Automatically shows color previews next to values

---

## Installation

### From VS Code Marketplace

1. Open Extensions in VS Code
2. Search for **Universal Color Picker**
3. Click Install

### Manual Installation

1. Download `.vsix` file
2. In VS Code:

   * Go to Extensions
   * Click `...` → Install from VSIX
   * Select the file

---

## Usage

* Open any file
* Add a supported color format
* Hover or click the color preview
* Adjust using the color picker

---

## Supported Formats

| Format | Example                |
| ------ | ---------------------- |
| HEX    | `#ff0000`              |
| RGB    | `(255, 0, 0)`          |
| RGBA   | `rgba(255, 0, 0, 0.5)` |

---

## Performance

* Scans files efficiently
* Updates only on changes
* Designed to work smoothly even in large files

---

## Development

Built using the VS Code Extension API.

To run locally:

```bash
npm install
```

Then press:

```
Run → Start Debugging
```

---

## Contributing

Contributions are welcome.

* Fork the repo
* Create a feature branch
* Submit a pull request

---

## Future Improvements

* Color palette generator
* Theme-aware contrast checking
* Export colors to CSS/JSON
* Color history tracking

---
