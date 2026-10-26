# Pi-hole Zero 2 W Case

A compact two-piece resin (SLA) enclosure for a **Raspberry Pi Zero 2 W** running [Pi-hole](https://pi-hole.net/). The lid has a swept-blade, fan-style vent over the processor, and the Pi-hole logo and wordmark are engraved into the lid.

![Pi-hole Zero 2 W case, isometric view](images/case-iso.png)

<p align="center">
  <img src="images/case-top.png" alt="Lid, top view" width="320">
</p>

## Features

- **Fan-style vent** with 9 curved blade cutouts and a solid hub, centred over the RP3A0 processor so heat can escape through the lid.
- **Engraved Pi-hole logo and "Pi-Hole" wordmark**, 0.5 mm deep. You can fill the engraving with paint to add colour.
- **Cutouts for every port:** mini HDMI, USB OTG, USB power, microSD (with a fingernail notch) and the CSI camera ribbon.
- **ACT LED window** so you can see the activity light with the lid closed.
- **Screws and captive nuts:** four M2.5 screws go through the lid and the board's mounting holes into hex nuts held in the base.
- **Alignment lip** that keys the lid onto the base.

## Files

| File | Part | Size (mm) | Volume |
|---|---|---|---|
| [`stl/PiHole_Lid.stl`](stl/PiHole_Lid.stl) | Lid | 69.5 × 34.5 × 5.45 | 4.6 cm³ |
| [`stl/PiHole_Base.stl`](stl/PiHole_Base.stl) | Base | 69.5 × 34.5 × 6.0 | 5.0 cm³ |

Both files are binary STLs in **millimetres**.

## Printing

Designed and checked for Formlabs-style resin printers.

- **Resin:** any standard or tough resin. One full case uses about **10 mL** of part volume, or roughly **13–16 mL** including supports and raft.
- **Layer height:** 0.1 mm.
- **Orientation:** let PreForm **Auto-Orient** the parts. Don't print either part flat with its open side facing the build platform, because a hollow shell in that position creates suction forces that can make the print fail.
- **Supports:** keep them off the engraved top of the lid. Put them on the inside faces or the edges.
- **Post-processing:** wash and cure the parts fully before fitting the board.

Smallest features, all at or above typical resin printer limits:

| Feature | Size |
|---|---|
| Thinnest engraved stroke ("Pi-") | 0.50 mm |
| Vent ring grooves | 0.40 mm |
| Vent spokes | 0.80 mm |
| Walls (side / lid / floor) | 2.0 / 1.5 / 1.5 mm |

## Hardware

| Qty | Part |
|---|---|
| 4 | M2.5 × 10 mm button-head screws |
| 4 | M2.5 hex nuts (5 mm across flats) |

The screw holes are 2.8 mm clearance holes, and the nut pockets are 5.2 mm across flats.

## Assembly

1. Press the four M2.5 nuts into the hex pockets on the underside of the base.
2. Set the Pi Zero 2 W onto the standoffs with the ports lined up with the side cutouts.
3. Place the lid on top so it seats on the alignment lip.
4. Drive the four screws through the lid and the board into the nuts. Snug them, but don't overtighten them in resin.

## Dimensions and fit

The board position, mounting holes and port cutouts were checked against the official Raspberry Pi Zero 2 W product brief and its 3D model.

| Brief | Model |
|---|---|
| Board 65 × 30 mm | 65 × 30 mm |
| Mounting holes 58 × 23 mm, 3.5 mm from the edges | ±29 × ±11.5 mm |
| Mini HDMI centre 12.4 mm | 12.4 mm |
| USB OTG centre 41.4 mm | 41.4 mm |
| USB power centre 54 mm | 54.0 mm |

The board has 0.25 mm of clearance on each side inside the case, and the lid-to-base joint has a 0.15 mm gap. Resin parts can come out slightly oversized, so if the lid fits too tightly, lightly sand the lip. Print one case and test-fit the board before printing a batch.

The original Pi Zero and Zero W share this board outline and mounting-hole pattern, but this case has only been checked against the Zero 2 W.

## Notes

This is an unofficial case. The Pi-hole name and logo belong to the Pi-hole project, and Raspberry Pi is a trademark of Raspberry Pi Ltd.
