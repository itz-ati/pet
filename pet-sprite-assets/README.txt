Pet sprite assets

Files:
- sprite_atlas.png: 8 columns x 4 rows, 128 x 160 px cells; rows are walk (6), sit (4), think (3), roll (8). Empty cells are transparent.
- walk.gif, sit.gif, think.gif, roll.gif: looping animated previews.
- Each animation folder contains transparent per-frame PNGs, aligned to the bottom of a 128 x 160 cell.
- frames.json: frame counts, row locations, and suggested frame delays.
- blow_kiss_portrait.png and expression_*.png: optional cutouts.
- source_sheet.png: provided source image.

Note: the source checkerboard was baked into the image. Background removal is approximate and may leave a faint fringe around some sprite edges. GIFs use a limited palette; use the PNG atlas for app rendering.