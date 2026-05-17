# ColorDrop — Extract Color Palettes from Images

Drop any image and instantly extract its dominant colors. Get complementary and analogous color schemes.

**Live Demo:** [colordrop-tool.surge.sh](https://colordrop-tool.surge.sh/)

## Features

- **6 dominant colors** — K-means clustering extracts the main palette
- **Color percentages** — See how much of each color is in the image
- **Complementary** — Auto-generated complementary color
- **Analogous** — 4 analogous colors for harmonious schemes
- **Click to copy** — Click any color to copy its hex value
- **Export** — Copy as CSS variables or array
- **Drag & drop** — Drop images directly onto the page

## Tech

- Pure HTML/CSS/JavaScript — zero dependencies
- Canvas API for pixel sampling
- K-means color quantization
- HSL color space for harmony calculations

## License

MIT
