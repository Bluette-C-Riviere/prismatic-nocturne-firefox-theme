# Prismatic Nocturne

A minimalist dark Firefox theme inspired by prismatic light and translucent abstract folds.

Prismatic Nocturne pairs deep Prussian blue with hydrangea violet-blue, muted aqua, and restrained antique copper-rose-gold accents. It is designed to create a calm, atmospheric, professional browsing environment.

![Prismatic Nocturne theme artwork](images/0.png)

## Design goals

- **Quiet focus:** dark browser surfaces and restrained highlights
- **Cohesive colour:** a small palette built around blue, violet, aqua, and copper
- **Readable interface:** light text against dark surfaces
- **Minimalist atmosphere:** abstract light and glass-like folds rather than decorative UI clutter

## Colour palette

| Role | Hex |
| --- | --- |
| Dusk Prussian Blue | `#101D35` |
| Midnight Slate | `#18283F` |
| Hydrangea Violet-Blue | `#777FC0` |
| Dirty Aqua Blue | `#477F91` |
| Antique Copper Rose Gold | `#BC8B7D` |
| Soft Porcelain | `#F1F0F5` |
| Pale Hydrangea | `#D9D8ED` |

## Project structure

```text
.
├── manifest.json
├── images/
│   └── 0.png
├── README.md
├── CONTRIBUTING.md
├── LICENSE
└── .gitignore
```

## Install locally for testing

1. Open Firefox and navigate to `about:debugging`.
2. Select **This Firefox**.
3. Choose **Load Temporary Add-on…**.
4. Select `manifest.json` from this project directory.

Temporary installation is for local testing. For normal distribution, package the theme and follow Mozilla Add-ons' current submission and review process.

## Validate before release

- Confirm `manifest.json` is valid JSON.
- Confirm `images/0.png` exists at the path referenced in the manifest.
- Package the **contents** of the project directory, not the enclosing directory, so `manifest.json` is at the archive root.
- Run the package through the [Mozilla Add-ons Developer Hub](https://addons.mozilla.org/developers/).
- Review Mozilla's [static theme documentation](https://extensionworkshop.com/documentation/themes/static-themes/) for current compatibility and submission requirements.

## Open-source project

This repository documents the theme's design, colour palette, and packaging so others can inspect and learn from the implementation. Suggestions and corrections are welcome through GitHub Issues.

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines and [LICENSE](LICENSE) for the project's code and configuration licence. The artwork is included as part of this project; check the licence terms before reusing it outside this repository.

## Status

A personal design project prepared for Mozilla Add-ons validation. Public listing and approval status should be updated once confirmed.

## Author

Created by **BChaintreauRiviere**.
