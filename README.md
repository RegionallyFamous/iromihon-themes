# Iromihon Themes

Four hostile little native Omarchy themes in one manifest-free collection:

- **Xerox Riot** — shredded flyers, toner grime, hot pink, and toxic chartreuse.
- **Cable Rat King** — wet circuitry, impossible wiring, oxidized copper, and terminal teal.
- **Safety Third** — industrial warning paint, bad decisions, hazard orange, and radioactive lime.
- **Channel Zero** — dead broadcast equipment, violet signal ghosts, scanlines, and no reception.

Each child under `themes/<slug>/` is a complete ordinary Omarchy theme. [Iromihon](https://github.com/RegionallyFamous/iromihon) browses this repository and installs one child without adding the others to the stock theme picker.

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
```

Every fragment reuses the same collection clone. Choosing **Change source** inside Iromihon forgets the active collection without deleting installed themes.

## Repository contract

There is deliberately no collection manifest and no executable setup code. Iromihon discovers lowercase child slugs directly under `themes/`, validates each native theme, and exposes only the children a user chooses. The repository shape remains compatible with a future native Omarchy collection interface.

## License

MIT. Artwork and theme configuration are by RegionallyFamous.
