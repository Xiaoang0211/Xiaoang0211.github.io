# Paper visuals

`teaser.pdf` is the existing `Teaser_high.pdf` paper figure, unchanged. `teaser.png` is a 2200-pixel-wide render generated with Poppler:

```bash
pdftoppm -singlefile -f 1 -png -scale-to 2200 teaser.pdf teaser
```

The README uses the PNG for browser compatibility; the vector PDF is retained for the project page and publication materials. No third-party template images are included.

`affiliations/` contains the official TUM, MCML, and Obsphera logos used beside the author affiliations. The logos link to the institutions' websites and retain their original proportions and colors. `affiliations/sources.json` records each source. TUM and Obsphera are SVGs; MCML uses the original high-resolution JPEG from its homepage.
