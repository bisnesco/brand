# BISNES — Visual identity

Brand asset structure for **BISNES**. The original symbol is preserved unchanged; variants are created only by changing colors and adapting formats.

## Structure

```text
brand/
├── logos/
│   ├── symbol/
│   │   ├── orange.svg
│   │   ├── black.svg
│   │   └── white.svg
│   ├── wordmark/
│   │   ├── orange.svg
│   │   ├── black.svg
│   │   └── white.svg
│   └── combinations/
│       ├── horizontal/
│       │   ├── orange.svg
│       │   ├── black.svg
│       │   └── white.svg
│       └── vertical/
│           ├── orange.svg
│           ├── black.svg
│           └── white.svg
├── icons/
│   ├── favicon.svg
│   ├── app.svg
│   └── apple-touch-icon.png
├── colors/
│   └── palette.svg
└── README.md
```

## Official colors

| Name | Hex |
|---|---|
| Orange | `#FD5D2A` |
| Black | `#111111` |
| White | `#FFFFFF` |

## Symbol

- Original reference file: `main.svg` (orange symbol).
- Variants in `logos/symbol/`: `orange.svg`, `black.svg`, `white.svg`.
- Geometry is identical to `main.svg`; only the fill color changes.
- Transparent background in all cases.

## Wordmark

- Text: `bisnes` (lowercase).
- **Provisional typographic wordmark** (a final wordmark has not yet been created).
- Font used (provisional): system font stack `system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif`, weight `700`, letter spacing `-1`.
- Variants in `logos/wordmark/`: `orange.svg`, `black.svg`, `white.svg`.
- Transparent background.

## Combinations

- Symbol + `bisnes` wordmark.
- Color variants: orange, black, white.
- Orientations: `horizontal/` and `vertical/`.
- Transparent background; the symbol's proportions are preserved through uniform scaling.

## Icons

- `icons/favicon.svg`: symbol adapted to 32×32.
- `icons/app.svg`: symbol adapted to 512×512.
- `icons/apple-touch-icon.png`: 180×180 px, generated from the symbol (transparent background).

## Notes

- The original files (`main.svg`) have not been modified or removed.
- All SVGs have transparent backgrounds (no background rectangles).
- The original symbol's proportions (240×244) are preserved in all adaptations.
