# extra-square-flags

A specialized extension repository for `square-flags`, housing historical variants, regional banners, non-standard entities, and alternate-history flag designs.

## Standards & Formatting
* **Dimensions:** 512×512 px SVG format.
* **Palette:** CSS variables (`var(--flag-palette-...)`) for uniform color management.
* **Naming Convention:** ISO/custom codes at top, full descriptive name at bottom.

## Viewing the Gallery
Visit the live gallery hosted on GitHub Pages:
👉 **[https://mateoperezmatematico.github.io/extra-square-flags/](https://mateoperezmatematico.github.io/extra-square-flags/)**

## Adding New Flags
1. Drop the 512×512 SVG into the `flags/` directory named `<code-name>.svg`.
2. Register the flag metadata in `_data/flags.yml`:
   ```yaml
   - code: your-flag-code
     name: Descriptive Flag Name
