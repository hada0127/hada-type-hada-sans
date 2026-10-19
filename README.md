# 하다 산스 · Hada Sans — Hada Type

하다 산스 무료 한글 폰트 — 미리보기·다운로드: https://hada-type.com/hada-sans

Hada Sans, a free Korean font by Hada Type — previews and downloads: https://hada-type.com/hada-sans

This repository holds the published webfont files of Hada Sans only.
The source build repository is private; load these files through
jsDelivr's GitHub CDN endpoint and keep the version pinned.

## CDN

Whole files — one WOFF2 per weight/style:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type-hada-sans@v2026.10.19/css/hada-sans.css">
```

Sliced — the same faces cut into unicode-range pieces, so the browser
downloads only the pieces the page's text uses:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type-hada-sans@v2026.10.19/css/hada-sans-subset.css">
```

Without the `@v2026.10.19` tag the URL follows the latest release
(`https://cdn.jsdelivr.net/gh/hada0127/hada-type-hada-sans/css/hada-sans.css`). Pin the tag in production.

Direct WOFF2 example:

```css
@font-face {
  font-family: "Hada Sans";
  src: url("https://cdn.jsdelivr.net/gh/hada0127/hada-type-hada-sans@v2026.10.19/woff2/HadaSans-Thin.woff2") format("woff2");
  font-weight: 100;
  font-style: normal;
  font-display: swap;
}
```

## Files

- `css/hada-sans.css` — whole-file stylesheet (`woff2/`)
- `css/hada-sans-subset.css` — sliced stylesheet (`woff2-subset/`)
- `woff2-subset/manifest.json` — slice list with codepoints and SHA-256

## Packages

TTF, OTF and WOFF2 ZIPs are attached to the GitHub release:

[HadaSans-TTF.zip](https://github.com/hada0127/hada-type-hada-sans/releases/download/v2026.10.19/HadaSans-TTF.zip) · [HadaSans-OTF.zip](https://github.com/hada0127/hada-type-hada-sans/releases/download/v2026.10.19/HadaSans-OTF.zip) · [HadaSans-WOFF2.zip](https://github.com/hada0127/hada-type-hada-sans/releases/download/v2026.10.19/HadaSans-WOFF2.zip)

Each ZIP includes `WEBFONT-USAGE.txt`, `LICENSE.txt` and `COPYRIGHT.txt`.
The WOFF2 ZIP also includes `WEBFONT.css` for self-hosted use.

## Other Hada Type families

- 하다 바탕 · Hada Batang — https://github.com/hada0127/hada-type-hada-batang
- 하다 모노 · Hada Mono — https://github.com/hada0127/hada-type-hada-mono
- 하다 라운드 · Hada Round — https://github.com/hada0127/hada-type-hada-round
- 하다 콘덴스드 · Hada Condensed — https://github.com/hada0127/hada-type-hada-condensed
- 춤추는사람들 · Dancing Peoples — https://github.com/hada0127/hada-type-dancing-peoples
- 춤추는사람들 고정폭 · Dancing Peoples Mono — https://github.com/hada0127/hada-type-dancing-peoples-mono
- 레벨업 · LevelUp — https://github.com/hada0127/hada-type-levelup

## License

The fonts are distributed under the SIL Open Font License 1.1.
