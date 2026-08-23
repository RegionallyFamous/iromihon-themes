# Iromihon Themes

Ten hostile little native Omarchy themes in one manifest-free collection:

- **Xerox Riot** — shredded flyers, toner grime, hot pink, and toxic chartreuse.
- **Cable Rat King** — wet circuitry, impossible wiring, oxidized copper, and terminal teal.
- **Safety Third** — industrial warning paint, bad decisions, hazard orange, and radioactive lime.
- **Channel Zero** — dead broadcast equipment, violet signal ghosts, scanlines, and no reception.
- **Thermal Runaway** — runaway receipt paper, dying registers, retail grime, checkout cyan, and refund pink.
- **Carpet Burn** — a casino carpet that has started moving, hot magenta, token gold, and nocturnal teal.
- **Pinball Autopsy** — a dead machine opened on the table, chrome rails, bumper red, cobalt coils, and lamp yellow.
- **Fruit Sticker Fever** — a produce counter buried in fictional labels, bruised fruit, scale blue, and market-stall primaries.
- **Specimen Leak** — an entomology drawer after containment failure, museum olive, beetle cyan, ultraviolet purple, and preservative amber.
- **Seismic Panic** — graph paper under geological assault, recorder black, survey pink, core-sample gray, and emergency orange.

Each child under `themes/<slug>/` is a complete ordinary Omarchy theme. [Iromihon](https://github.com/RegionallyFamous/iromihon) browses this repository and installs one child without adding the others to the stock theme picker.

## New collection previews

The six newest themes each ship with two selectable 4K wallpapers, a dedicated 1600×900 preview derived from the second wallpaper, a complete accessible palette, matching icon and keyboard color choices, and concept-specific Omarchy shell treatments for the launcher, menus, and notifications.

| | |
|---|---|
| <img src="themes/thermal-runaway/preview.png" alt="Thermal Runaway preview" width="560"><br>**Thermal Runaway** | <img src="themes/carpet-burn/preview.png" alt="Carpet Burn preview" width="560"><br>**Carpet Burn** |
| <img src="themes/pinball-autopsy/preview.png" alt="Pinball Autopsy preview" width="560"><br>**Pinball Autopsy** | <img src="themes/fruit-sticker-fever/preview.png" alt="Fruit Sticker Fever preview" width="560"><br>**Fruit Sticker Fever** |
| <img src="themes/specimen-leak/preview.png" alt="Specimen Leak preview" width="560"><br>**Specimen Leak** | <img src="themes/seismic-panic/preview.png" alt="Seismic Panic preview" width="560"><br>**Seismic Panic** |

## Browse the collection

Install Iromihon on stock Omarchy Quattro:

```bash
omarchy plugin add https://github.com/RegionallyFamous/iromihon.git --enable
omarchy restart shell
```

Open **Iromihon** from Apps. On a fresh install, this collection opens automatically:

```text
https://github.com/RegionallyFamous/iromihon-themes.git
```

No URL setup is required unless you previously chose **Change source**. In that case, paste the address above to return. Iromihon clones the collection once, validates every child, and exposes only the themes you deliberately install. Installed children remain ordinary native themes managed by Omarchy.

## Open one child directly

Append a child slug as the URL fragment when pasting it into Iromihon:

```text
https://github.com/RegionallyFamous/iromihon-themes.git#xerox-riot
https://github.com/RegionallyFamous/iromihon-themes.git#cable-rat-king
https://github.com/RegionallyFamous/iromihon-themes.git#safety-third
https://github.com/RegionallyFamous/iromihon-themes.git#channel-zero
https://github.com/RegionallyFamous/iromihon-themes.git#thermal-runaway
https://github.com/RegionallyFamous/iromihon-themes.git#carpet-burn
https://github.com/RegionallyFamous/iromihon-themes.git#pinball-autopsy
https://github.com/RegionallyFamous/iromihon-themes.git#fruit-sticker-fever
https://github.com/RegionallyFamous/iromihon-themes.git#specimen-leak
https://github.com/RegionallyFamous/iromihon-themes.git#seismic-panic
```

Every fragment reuses the same collection clone. Choosing **Change source** inside Iromihon forgets the active collection without deleting installed themes.

## Repository contract

There is deliberately no collection manifest and no executable setup code. Iromihon discovers lowercase child slugs directly under `themes/`, validates each native theme, and exposes only the children a user chooses. The repository shape remains compatible with a future native Omarchy collection interface.

## License

MIT. Artwork and theme configuration are by RegionallyFamous.
