# binary-bit-flipper

> An interactive 11-bit binary to decimal converter. Click any bit to toggle it and watch the decimal value update in real time.

![HTML](https://img.shields.io/badge/HTML-single%20file-e34f26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-custom%20properties-1572b6?logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-vanilla-f7df1e?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## What it is

A tiny, dependency-free widget for learning how binary works. Flip individual bits and see the decimal value change instantly. Place values run from **1 up to 1024** (11 bits total).

Built as a single self-contained HTML file — no build step, no framework, no install.

---

## Features

- **Click to toggle** — every bit is a button; click it to flip between `0` and `1`
- **Live decimal readout** — updates on every flip with a small pop animation
- **Binary mirror** — shows the current bit pattern as a string below the value
- **Keyboard friendly** — `←` / `→` move between bits, `↑` / `↓` toggle the focused bit
- **Random & clear** — one-click reset or randomization
- **Accessible** — proper `aria-label`, `aria-pressed`, `aria-live` regions, and visible focus rings
- **Responsive** — bit cells scale down on narrow screens
- **Reduced-motion aware** — animations disabled when the user prefers reduced motion

---

## Bit layout

| Bit index | 0     | 1    | 2    | 3    | 4   | 5   | 6   | 7   | 8  | 9  | 10 |
|-----------|-------|------|------|------|-----|-----|-----|-----|----|----|----|
| Power     | 1024  | 512  | 256  | 128  | 64  | 32  | 16  | 8   | 4  | 2  | 1  |

Maximum representable value: **2047** (`11111111111`).

---

## Usage

1. Clone or download the repo
2. Open `binary_bit_flipper.html` in any modern browser

That's it.

```bash
git clone https://github.com/your-username/binary-bit-flipper.git
cd binary-bit-flipper
open binary_bit_flipper.html   # or just double-click it
