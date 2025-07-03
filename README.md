# Radix Colors
Radix colors as CSS, SCSS, and JSON

> **Note:** This repo is not owned or managed by WorkOS; it’s provided by me as a convenience to fellow devs. For the official Radix repo, see [radix-ui/colors](https://github.com/radix-ui/colors).

## Usage

| Step | Use case                                | Pairs with                                                 |
|:----:|:----------------------------------------|:-----------------------------------------------------------|
| 1    | Backgrounds                             | Steps 11 & 12 text                                         |
| 2    | Backgrounds                             | Steps 11 & 12 text                                         |
| 3    | Interactive components                  | Step 11 labels, Step 12 text                               |
| 4    | Interactive components                  | Steps 11 & 12 labels                                       |
| 5    | Interactive components                  | Step 12 labels                                             |
| 6    | Borders and separators                  | Steps 1–5 backgrounds                                      |
| 7    | Borders and separators                  | Steps 1–5 backgrounds                                      |
| 8    | Borders, focus rings                    | Steps 1–5 backgrounds                                      |
| 9    | Solid backgrounds, buttons              | White text (or dark text for very bright palettes)         |
| 10   | Solid backgrounds, buttons              | White text (or dark text for very bright palettes)         |
| 11   | Secondary text & links                  | Background colors                                          |
| 12   | High-contrast text                      | Background colors                                          |

## Definitions
- **Backgrounds**: lightest fills, ideal for page or component backgrounds.
- **Interactive components**: hover/focus/active states and other interactive elements.
- **Borders, separators, and focus rings**: borders, dividers, and focus rings (step 8 sometimes used for disabled text in neutral scales).
- **Solid backgrounds, buttons**: pair with high-contrast text (usually white, except in very bright “accent” palettes where dark text may work).
- **Secondary text & links**: used for labels, metadata, captions, and other supporting information.
- **High-contrast text**: used for primary content (e.g., headings and body copy) to ensure maximum readability against background colors.