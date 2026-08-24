# Artwork notes

The six themes added on 2026-08-23 use original raster artwork generated with OpenAI Imagegen in built-in mode. Every concept received two independent Imagegen passes: a primary wallpaper and a more aggressive alternate composition. The alternate is both a real selectable wallpaper and the source for `preview.png`, so the catalog never advertises an image the theme cannot display.

The generated PNG masters remain intact in the local Codex generated-image cache. The repository contains optimized, metadata-stripped 3840×2160 WebP wallpaper derivatives and 1600×900 PNG previews. No real brands, logos, copyrighted characters, or meaningful printed copy were requested.

## Second-edition production

The 2026-08-23 second-edition pass used OpenAI Imagegen in built-in mode for 34 additional original raster assets: ten transparent unlock emblems, fourteen alternate or event wallpapers, and ten opposite-mode mutation wallpapers. Wallpaper generations requested a chaotic 16:9 composition, no readable copy or logos, usable negative space for desktop windows, and a material vocabulary specific to the theme. Unlock generations requested one centered emblem on true transparency with no glow cut off at the canvas edge. The generated PNG masters were deterministically converted to metadata-stripped 3840×2160 WebP wallpapers; unlock masters were resized to 520×520 sRGBA PNGs so Omarchy's Plymouth compositor retains its intended field placement. Every `preview-unlock.png` was assembled from the final unlock file with Omarchy's real lock, entry, and bullet assets.

The compact prompt ledger below records the distinguishing art direction layered over those shared production constraints.

| Theme family | Unlock emblem direction | New alternate/event direction | Opposite-mode mutation direction |
|---|---|---|---|
| Xerox Riot | A battered copier button built from torn fluorescent registration marks and toner dust. | Toner flood and copier catastrophe: ripped paper waves, broken rollers, hot pink and chartreuse errors, dirty neutral center. | **Xerox Riot Cleanroom:** overexposed evidence-lab white, magenta toner smears, chartreuse registration targets, sealed plastic and clinical glare. |
| Cable Rat King | A knotted cable crown with oxidized plugs and wet teal indicator lights. | Nest voltage and grid consumption: impossible cable anatomy consuming circuit panels around a dark service void. | **Cable Rat King Emergency Lighting:** bright maintenance bay, bleached conduit, emergency teal and rust-orange wiring under hard work lamps. |
| Safety Third | A dented warning triangle made from hazard tape, bolts, and radioactive paint. | Cone collapse and incident command: crushed barricades and warning geometry escalating into an uncontrolled industrial scene. | **Safety Third Day Shift:** sun-blasted concrete, washed warning paint, broken orange controls, inspection-board red, no sense of actual safety. |
| Channel Zero | A broken cathode-ray eye with violet static and offset RGB scan marks. | Signal possession and transmitter meltdown: haunted broadcast equipment, violet ghosts, scanline eruptions, dark usable studio center. | **Channel Zero Day Signal:** white cyclorama invaded by pale broadcast hardware, lavender signal burns, black registration debris, exposed daylight static. |
| Thermal Runaway | A receipt roll fused into a cyan-and-pink warning flame. | Point of no return: paper avalanche and failing register hardware finally overtaking the checkout surface. | **Thermal Runaway Night Shift:** closed black register bay, phosphorescent cyan receipts, refund pink heat, emergency orange status lamps. |
| Carpet Burn | A woven eye-knot in magenta, teal, gold, and singed carpet fiber. | The floor is alive: the casino pattern becomes an actual perimeter infestation closing on the dark center. | **Carpet Burn Daylight:** pale lobby floor under unforgiving daylight, magenta ornamental organisms, turquoise paths, tobacco stains, exposed worn fiber. |
| Pinball Autopsy | A mechanical heart assembled from bumpers, coils, chrome rails, and one yellow lamp. | Multiball failure: machine organs, balls, rails, and lamps erupting from the opened cabinet. | **Pinball Autopsy Service Manual:** bright aged paper schematic, exploded red and blue parts, grease fingerprints, ruler marks, frantic diagram rhythm without readable labels. |
| Fruit Sticker Fever | A bitten fruit seal buried under fictional colorful produce labels. | Produce apocalypse: bruised fruit and abstract labels breaking loose from the market counter in every direction. | **Fruit Sticker Fever After Hours:** black market counter, fluorescent labels, ultraviolet bruised fruit, scale-blue hardware, hot pink and green nocturnal color. |
| Specimen Leak | An iridescent beetle containment seal cracked open over dark museum velvet. | The drawer opened itself: imaginary wings, legs, vials, and archival fragments actively escaping the case. | **Specimen Leak Bleached:** bright chemical tray, cyan exoskeleton fragments, ultraviolet stains, amber fluid, overexposed clinical paper and hard shadows. |
| Seismic Panic | A fractured seismograph dial crossed by a hot-pink fault line. | Fault rupture: graph paper, core samples, ink traces, and survey marks physically splitting across the desktop. | **Seismic Panic Night Watch:** midnight monitoring room, neon pink fault trace, cyan grids, orange recorder lights, black glass and geological debris. |

The mutation previews are honest crops of their installable wallpapers. None of the opposite-mode themes were made by algorithmically inverting the parent; each received a separate Imagegen composition and a separately authored Omarchy palette.

## Thermal Runaway

- Primary prompt: A chaotic 16:9 overhead desktop wallpaper made from a failing retail checkout counter, runaway curls of thermal receipt paper, fragments of fictional old registers, pink and cyan paper accents, orange warning marks, toner grime, and a broad dirty-cream center left calm enough for windows; tactile editorial photography, no readable copy or logos.
- Alternate prompt: Recompose the reference into a denser receipt-paper vortex around the frame, with obsolete register fragments pushed to the side edges, stronger cyan, refund pink, and emergency orange interruptions, and a clear battered cream center; not clean, not minimal, no readable copy or logos.
- Files: `themes/thermal-runaway/backgrounds/1-thermal-runaway.webp`, `themes/thermal-runaway/backgrounds/2-receipt-vortex.webp`, and `themes/thermal-runaway/preview.png`.

## Carpet Burn

- Primary prompt: A chaotic 16:9 overhead desktop wallpaper of ruined near-black casino carpet, impossible wormlike ornamental paths in hot magenta, nocturnal teal, token gold, and burnt orange, worn fibers and old stains, with the loud pattern concentrated toward the perimeter and a dark usable center; fictional pattern, no text or logos.
- Alternate prompt: Push the reference into a more aggressive crawling carpet infestation with brighter edge patterns, denser woven texture, stranger asymmetry, and a deep nearly empty navy-black center for desktop legibility; no text or logos.
- Files: `themes/carpet-burn/backgrounds/1-carpet-burn.webp`, `themes/carpet-burn/backgrounds/2-lost-token.webp`, and `themes/carpet-burn/preview.png`.

## Pinball Autopsy

- Primary prompt: A chaotic 16:9 top-down desktop wallpaper showing a fictional pinball machine disassembled like an autopsy, chrome rails, solenoids, bulbs, coils, scratched black wood, aged ivory plastics, cherry red, cobalt blue, and butter yellow hardware arranged around a calm central work surface; no brand marks or readable labels.
- Alternate prompt: Turn the reference into a stronger radial exploded view, with chrome rails and glowing bumper hardware firing inward from every edge, more bulbs and mechanical detail, and a broad black center kept usable for windows; entirely fictional, no text or logos.
- Files: `themes/pinball-autopsy/backgrounds/1-pinball-autopsy.webp`, `themes/pinball-autopsy/backgrounds/2-bumper-explosion.webp`, and `themes/pinball-autopsy/preview.png`.

## Fruit Sticker Fever

- Primary prompt: A chaotic 16:9 overhead desktop wallpaper of a battered produce counter buried in hundreds of fictional abstract fruit labels, bruised fruit fragments, an obsolete market scale near the edge, cobalt blue, tomato red, market yellow, leaf green, and hot pink around a scratched cream center; no readable words, brands, or logos.
- Alternate prompt: Escalate the reference into a dense avalanche of abstract circular produce stickers around all four edges, with fruit and an old scale partly entering the frame, while keeping a large scuffed cream center empty enough for desktop windows; handmade print texture, no readable copy or real brands.
- Files: `themes/fruit-sticker-fever/backgrounds/1-fruit-sticker-fever.webp`, `themes/fruit-sticker-fever/backgrounds/2-label-avalanche.webp`, and `themes/fruit-sticker-fever/preview.png`.

## Specimen Leak

- Primary prompt: A chaotic 16:9 overhead desktop wallpaper of a dark olive museum specimen drawer after containment failure, imaginary beetles, moth wings, pinned fragments, old cards, and glass vials around the perimeter, iridescent cyan, ultraviolet purple, blue, and amber glints, with a calm velvet-dark center; no readable labels or real species plates.
- Alternate prompt: Make the reference feel like a denser iridescent specimen outbreak, with more imaginary insects and wing fragments breaching the drawer edges, richer cyan-purple reflections and preservative amber, while protecting a dark olive center for desktop use; unsettling museum tactility, no readable text.
- Files: `themes/specimen-leak/backgrounds/1-specimen-leak.webp`, `themes/specimen-leak/backgrounds/2-drawer-breach.webp`, and `themes/specimen-leak/preview.png`.

## Seismic Panic

- Primary prompt: A chaotic 16:9 overhead desktop wallpaper built from worn graph paper, seismograph traces, broken geological core samples, survey paint, stone fragments, recorder ink, hot pink and emergency orange marks, with a pale central field held relatively quiet for windows; tactile archival mess, no readable labels or logos.
- Alternate prompt: Recompose the reference into a stronger diagonal aftershock frame of recorder paper, core samples, black seismic traces, torn grid sheets, hot pink survey marks, and emergency orange, surrounding a battered cream graph-paper center; energetic and damaged, no readable text.
- Files: `themes/seismic-panic/backgrounds/1-seismic-panic.webp`, `themes/seismic-panic/backgrounds/2-aftershock.webp`, and `themes/seismic-panic/preview.png`.
