# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

The file Hell_Sink_GM.jpg in this folder is a map of a Mutant: Year Zero zone. The zone consists of multiple sectors that are depicted as a grid with black lines on the image. Sector names consist of a letter and a number so that the letter can be found from the first column on the left, and the number from the first row on the top.

The file map.md contains a brief description of sectors that have been visited. Visited sectors are listed by sector names, and the names adhere to the format described above.

When prompted to update the map of visited sectors, update the file Hell_Sink_visited.jpg. Tint the sector with a colored box, in the same style as the boxes that are already on the map. The map must stay visible below the tint.

Use this color for the tint:

- Blue: a visited sector with no threat and no rot.
- Green: high rot.
- Red: a threat that is not rot, for example zone ghouls, or something unknown that is a threat at first.

## How to tint a sector

Hell_Sink_GM.jpg is the clean map. Hell_Sink_visited.jpg is the same image with the tint boxes added. The two files are identical except in the tinted sectors. To change the color of a sector, first copy that area from Hell_Sink_GM.jpg, then draw the new box.

Grid geometry of both images (5000 x 3000):

- Row A starts at y = 12, column 1 starts at x = 25.
- Cell pitch is 163.2 px in both directions.

Box style, measured from the boxes on the map:

- Fill: the tint color at 27 % alpha over the map.
- Stroke: 6 px, drawn inside the grid line.
- Fill color / stroke color: blue 36,92,229 / 50,101,205. Sample green and red from an existing box.
- The box is inset a few pixels from the grid lines. Take the exact position from a box that is already on the map, because the boxes are hand-placed.

Save with JPEG quality 92 and 4:4:4 chroma, to keep the grid lines sharp.
