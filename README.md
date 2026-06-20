**Link:** https://zm-engineer.github.io/assignment-team/index.html

# Team Project — Landing Page

A small responsive website built with **vanilla HTML and CSS only** (no
libraries, no frameworks, no SASS, no build tools, no JavaScript). It is a
faithful copy of a provided design and is laid out entirely with **Flexbox**.

## Tech & constraints

- Vanilla HTML5 + CSS3 only.
- **Layout with Flexbox only — no CSS Grid anywhere.** Use `flex-wrap` /
  `flex-direction` for responsive behavior.
- Roboto font is **self-hosted** locally via `@font-face` (no Google Fonts link).
- All code and comments in English.

## Design tokens

Defined as `:root` custom properties in [`css/variables.css`](css/variables.css).

| Token                 | Value     | Usage                                              |
| --------------------- | --------- | -------------------------------------------------- |
| `--color-dark`        | `#1F2937` | Hero & footer background; info header & quote text |
| `--color-light`       | `#F9FAF8` | Hero title, logo                                   |
| `--color-gray-light`  | `#E5E7EB` | Secondary text, header links, quote background     |
| `--color-blue`        | `#3882F6` | Buttons, call-to-action background                 |
| `--font`              | `'Roboto', sans-serif` | Global font family                    |

Type scale:

| Element            | Size   | Weight        |
| ------------------ | ------ | ------------- |
| Hero title         | 48px   | 900           |
| Logo               | 24px   | 700           |
| Info header        | 36px   | 900           |
| Quote              | 36px   | 300 (italic)  |
| Secondary text & links | 18px | 400         |

## File structure

```
/
├── index.html        # Home page (Sections 1–4 + Footer)
├── page-2.html       # Secondary page stub
├── page-3.html       # Secondary page stub
├── css/
│   ├── reset.css     # Modern CSS reset
│   ├── variables.css # Design tokens (:root custom properties)
│   ├── base.css      # @font-face, global typography, .container helper
│   └── index.css     # Page-specific styles (section comments only for now)
├── img/              # Images (.gitkeep keeps the empty folder in git)
├── fonts/            # Self-hosted Roboto ttf files
└── README.md
```

## Fonts

The Roboto font is self-hosted. These files must be present in `/fonts` and are
referenced by the `@font-face` rules in [`css/base.css`](css/base.css):

| File                      | Weight | Style  |
| ------------------------- | ------ | ------ |
| `roboto-light.ttf`        | 300    | normal |
| `roboto-regular.ttf`      | 400    | normal |
| `roboto-bold.ttf`         | 700    | normal |
| `roboto-black.ttf`        | 900    | normal |
| `roboto-light-italic.ttf` | 300    | italic |

## Task split

- **Ziuling:** Section 1 (Header + Hero), Section 2 (Information / 4 cards) + one
  secondary page.
- **Monica:** Section 3 (Quote / testimonial), Section 4 (Call to action),
  Footer + one secondary page.

## Team rules

- **Flexbox only — no CSS Grid.** Use `flex-wrap` / `flex-direction` for
  responsive layouts.
- **Git workflow:** work on **feature branches** and merge through **pull
  requests** (no direct commits to `main`). Each member commits from their own
  GitHub account.
