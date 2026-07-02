# Unified Design System

**unifiedspec.org** — beta preview via GitHub Pages

A design language synthesised from four workstation traditions:

| Lineage | Contribution |
|---------|-------------|
| **Solarized** (Schoonover 2011) | Tonal palette — CIELAB-calibrated base tones |
| **Okabe-Ito** (2002) | Semantic color — CVD-safe accent assignments |
| **Plan 9 / Acme** (Bell Labs 1992) | Structure — utility-first, tag-bar grammar, worm strip |
| **Solaris / CDE** (Sun 1993) | Chrome — CDE titlebar, Motif depth |

## Documents

| File | Description |
|------|-------------|
| [`styleguide.html`](https://denzuko.github.io/unifiedspec/styleguide.html) | Design system & style guide v2.1 |
| [`cua.html`](https://denzuko.github.io/unifiedspec/cua.html) | Common User Access specification v1.0 |
| [`tokens.json`](tokens.json) | Design tokens — W3C DTCG format |
| [`tokens.schema.json`](tokens.schema.json) | JSON Schema for token validation |

## Design decisions

- **Mouse**: B1 select/activate, B2 context menu, B3 optional/platform-dependent
- **Keyboard**: CDE-style Alt+key mnemonics derived from tag-bar command names
- **Focus**: Acme model — user initiates, HTMX swaps never auto-focus
- **Animations**: None (heritage practice). Exception: `prefers-reduced-motion`-guarded only
- **Viewport**: Desktop + tablet first. Mobile third-class.

## Conformance

Implementations must satisfy criteria C-01 through C-15 in [`cua.html#conformance`](https://denzuko.github.io/unifiedspec/cua.html#conformance).

## Status

`beta` — specification under active development. Not yet at unifiedspec.org.

See [roadmap](https://denzuko.github.io/unifiedspec/#roadmap) for version history.

## License

BSD-2-Clause © 2026 Da Planet Security

## Related

- [cispec.org](https://cispec.org) — Change Item attribution namespace
- [dwightaspencer.com](https://dwightaspencer.com) — practitioner publication
