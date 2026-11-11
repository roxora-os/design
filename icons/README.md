# App icons

Icons for the two Roxora tools. Both sit on the same dark rounded tile as the org avatar, so they read as one family. Colours are the ones in the top-level README.

| App | Picture | Files |
| --- | --- | --- |
| Hardware tool (`hwtool/`) | The Roxora mark as the die of a chip, with pins above and below. | `roxora-hwtool.svg` |
| Imager (`imager/`) | An SD card in the three Roxora bands, in front of an eMMC chip (ball grid). | `roxora-imager.svg`, plus `roxora-imager-small.svg` for 16 and 24 px (the ball grid is dropped because it turns to noise at that size) |

Each folder also has:

- `png/`: 16, 24, 32, 48, 64, 128, 256 and 512 px renders. For Linux, install them as `hicolor/<size>x<size>/apps/`.
- `*.ico`: Windows icon with 16 to 256 px.
- `*.icns`: macOS icon.
- `*-symbolic.svg`: 16 px single-colour icon for GNOME (`hicolor/symbolic/apps/`), in Adwaita's `#2e3436`, recoloured by the theme.

Do not redraw or recolour these. Regenerate the PNG, ICO and ICNS files from the SVGs if the SVGs change, and use the small SVG for the imager's 16 and 24 px sizes.
