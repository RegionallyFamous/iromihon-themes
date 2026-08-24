# Iromihon Themes

Twenty hostile little native Omarchy themes in one manifest-free collection. The original ten are complete three-wallpaper systems with custom unlock artwork, icon and keyboard choices, launcher/menu/notification treatments, and one additional signature Omarchy shell surface. Each original also has a genuinely reimagined opposite-mode mutation rather than a mechanical palette inversion.

| Original system | Opposite-mode mutation |
|---|---|
| <img src="themes/xerox-riot/preview.png" alt="Xerox Riot preview" width="560"><br>**Xerox Riot** — shredded flyers, toner grime, hot pink, and toxic chartreuse. | <img src="themes/xerox-riot-cleanroom/preview.webp" alt="Xerox Riot Cleanroom preview" width="560"><br>**Xerox Riot Cleanroom** — the copier disaster sealed inside a bright evidence lab. |
| <img src="themes/cable-rat-king/preview.png" alt="Cable Rat King preview" width="560"><br>**Cable Rat King** — wet circuitry, impossible wiring, oxidized copper, and terminal teal. | <img src="themes/cable-rat-king-emergency-lighting/preview.webp" alt="Cable Rat King Emergency Lighting preview" width="560"><br>**Cable Rat King Emergency Lighting** — the nest under brutal maintenance lamps. |
| <img src="themes/safety-third/preview.png" alt="Safety Third preview" width="560"><br>**Safety Third** — industrial warning paint, bad decisions, hazard orange, and radioactive lime. | <img src="themes/safety-third-day-shift/preview.webp" alt="Safety Third Day Shift preview" width="560"><br>**Safety Third Day Shift** — a sun-bleached incident scene still failing inspection. |
| <img src="themes/channel-zero/preview.png" alt="Channel Zero preview" width="560"><br>**Channel Zero** — dead broadcast equipment, violet signal ghosts, scanlines, and no reception. | <img src="themes/channel-zero-day-signal/preview.webp" alt="Channel Zero Day Signal preview" width="560"><br>**Channel Zero Day Signal** — spectral broadcast debris exposed on a white studio cyclorama. |
| <img src="themes/thermal-runaway/preview.png" alt="Thermal Runaway preview" width="560"><br>**Thermal Runaway** — receipt avalanches, dying registers, checkout cyan, and refund pink. | <img src="themes/thermal-runaway-night-shift/preview.webp" alt="Thermal Runaway Night Shift preview" width="560"><br>**Thermal Runaway Night Shift** — fluorescent receipts burning through a closed register bay. |
| <img src="themes/carpet-burn/preview.png" alt="Carpet Burn preview" width="560"><br>**Carpet Burn** — a casino carpet that has started moving. | <img src="themes/carpet-burn-daylight/preview.webp" alt="Carpet Burn Daylight preview" width="560"><br>**Carpet Burn Daylight** — the infestation dragged into unforgiving lobby daylight. |
| <img src="themes/pinball-autopsy/preview.png" alt="Pinball Autopsy preview" width="560"><br>**Pinball Autopsy** — a dead machine opened on the table. | <img src="themes/pinball-autopsy-service-manual/preview.webp" alt="Pinball Autopsy Service Manual preview" width="560"><br>**Pinball Autopsy Service Manual** — the machine flattened into a frantic paper schematic. |
| <img src="themes/fruit-sticker-fever/preview.png" alt="Fruit Sticker Fever preview" width="560"><br>**Fruit Sticker Fever** — a produce counter buried in fictional labels. | <img src="themes/fruit-sticker-fever-after-hours/preview.webp" alt="Fruit Sticker Fever After Hours preview" width="560"><br>**Fruit Sticker Fever After Hours** — fluorescent labels running wild after the market closes. |
| <img src="themes/specimen-leak/preview.png" alt="Specimen Leak preview" width="560"><br>**Specimen Leak** — an entomology drawer after containment failure. | <img src="themes/specimen-leak-bleached/preview.webp" alt="Specimen Leak Bleached preview" width="560"><br>**Specimen Leak Bleached** — the outbreak chemically overexposed on a clinical tray. |
| <img src="themes/seismic-panic/preview.png" alt="Seismic Panic preview" width="560"><br>**Seismic Panic** — graph paper under geological assault. | <img src="themes/seismic-panic-night-watch/preview.webp" alt="Seismic Panic Night Watch preview" width="560"><br>**Seismic Panic Night Watch** — neon traces monitoring a fault in total darkness. |

Each child under `themes/<slug>/` is an ordinary native Omarchy theme. [Iromihon](https://github.com/RegionallyFamous/iromihon) browses this repository, shows what each child can change, previews all of its wallpapers, and installs only the child you choose.

## Browse the collection

Install Iromihon on stock Omarchy Quattro:

```bash
omarchy plugin add https://github.com/RegionallyFamous/iromihon.git --enable
omarchy restart shell
```

Open **Iromihon** from Apps. This collection opens automatically on first launch, so no source URL is required. To return after choosing **Change source**, use:

```text
https://github.com/RegionallyFamous/iromihon-themes.git
```

Iromihon clones the collection once, validates every child, and exposes only the themes you deliberately install. Installed children remain ordinary native themes managed by Omarchy.

## Open one child directly

Append any directory slug as the URL fragment when pasting the source into Iromihon:

```text
https://github.com/RegionallyFamous/iromihon-themes.git#xerox-riot
https://github.com/RegionallyFamous/iromihon-themes.git#cable-rat-king-emergency-lighting
https://github.com/RegionallyFamous/iromihon-themes.git#pinball-autopsy-service-manual
https://github.com/RegionallyFamous/iromihon-themes.git#seismic-panic-night-watch
```

Every fragment reuses the same collection clone. Choosing **Change source** forgets the active collection without deleting installed themes.

## Repository contract

There is deliberately no collection manifest and no executable setup code. Iromihon discovers lowercase child slugs directly under `themes/`, validates each native theme, and exposes only the children a user chooses. A child can use the complete current Omarchy theme contract: colors, wallpapers, icons, keyboard colors, unlock art, launcher/menu/notification styling, and narrow shell surface overrides.

See the [full runtime gallery](GALLERY.md) for all twenty themes in a disposable x86_64 Omarchy guest. Artwork production notes and prompt directions live in [ARTWORK.md](ARTWORK.md).

## License

MIT. Artwork and theme configuration are by RegionallyFamous.
