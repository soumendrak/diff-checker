<div align="center">

# Diff Checker

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://soumendrak.github.io/diff-checker/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=flat-square)](https://www.w3.org/TR/html52/)

<!-- Inline SVG logo -->
<svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
<rect width="140" height="140" rx="24" fill="#0a0a14"/>
  <rect x="8" y="24" width="58" height="100" rx="4" fill="#0d0d1a"/>
  <text x="12" y="38" font-family="monospace" font-size="7" fill="#e74c3c">Hello</text>
  <text x="12" y="48" font-family="monospace" font-size="7" fill="#f0ece4">World</text>
  <text x="12" y="58" font-family="monospace" font-size="7" fill="#4caf7d">Earth</text>
  <rect x="74" y="24" width="58" height="100" rx="4" fill="#0d0d1a"/>
  <text x="78" y="38" font-family="monospace" font-size="7" fill="#4caf7d">Hello</text>
  <text x="78" y="48" font-family="monospace" font-size="7" fill="#f0ece4">World</text>
  <text x="78" y="58" font-family="monospace" font-size="7" fill="#f0ece4">Earth</text>
  <text x="37" y="90" text-anchor="middle" font-family="monospace" font-size="9" fill="#e74c3c">−1</text>
  <text x="103" y="90" text-anchor="middle" font-family="monospace" font-size="9" fill="#4caf7d">+1</text>
</svg>

**Compare two texts side-by-side with colour-coded added/removed line highlighting.**

**Live:** [https://soumendrak.github.io/diff-checker/](https://soumendrak.github.io/diff-checker/)

</div>

---

## Features

- Two textareas side by side (stacked on mobile)
- Green background for added lines, red for removed
- Line numbers on both sides
- Character-level diff within changed lines
- Custom LCS diff algorithm in ~100 lines of JS
- Word wrap toggle
- Clear buttons for each textarea
- Dark theme with orange accent (#ff6b35)

## How It Works

A Longest Common Subsequence (LCS) algorithm compares the two texts line-by-line. Lines present only in the left text get a red background; lines present only in the right get green. For changed lines, a character-level LCS pass highlights individual changed characters. Results update on button click.

## Usage

1. Open `https://soumendrak.github.io/diff-checker/` in any browser.
2. No build step, no installation, no server required.
3. Deploy anywhere — GitHub Pages, Netlify, or any static host.

```bash
git clone https://github.com/soumendrak/diff-checker.git
# Open index.html directly
```

## License

Licensed under the [MIT License](LICENSE).

---

<p align="center"><sub>Built with ❤️ and zero dependencies</sub></p>
