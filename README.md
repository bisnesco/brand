# BISNES — Identidad visual

Estructura de activos de marca para **BISNES**. El símbolo original se conserva sin modificar; las variantes se generan únicamente cambiando colores y adaptando formatos.

## Estructura

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

## Colores oficiales

| Nombre | Hex |
|---|---|
| Naranja | `#FD5D2A` |
| Negro | `#111111` |
| Blanco | `#FFFFFF` |

## Símbolo

- Archivo de referencia original: `main.svg` (símbolo en naranja).
- Variantes en `logos/symbol/`: `orange.svg`, `black.svg`, `white.svg`.
- Geometría idéntica a `main.svg`; solo cambia el color de relleno.
- Fondo transparente en todos los casos.

## Wordmark

- Texto: `bisnes` (minúsculas).
- Wordmark **provisional tipográfico** (no existe aún un wordmark definitivo).
- Fuente utilizada (provisional): pila del sistema `system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif`, peso `700`, interletraje `-1`.
- Variantes en `logos/wordmark/`: `orange.svg`, `black.svg`, `white.svg`.
- Fondo transparente.

## Combinaciones

- Símbolo + wordmark `bisnes`.
- Variantes de color: naranja, negro, blanco.
- Orientaciones: `horizontal/` y `vertical/`.
- Fondo transparente; proporciones del símbolo conservadas mediante escalado uniforme.

## Iconos

- `icons/favicon.svg`: símbolo adaptado a 32×32.
- `icons/app.svg`: símbolo adaptado a 512×512.
- `icons/apple-touch-icon.png`: 180×180 px, generado a partir del símbolo (fondo transparente).

## Notas

- No se han modificado ni eliminado los archivos originales (`main.svg`).
- Todos los SVG mantienen fondo transparente (sin rectángulos de fondo).
- Las proporciones del símbolo original (240×244) se conservan en todas las adaptaciones.
