# psoptkern
### PostScript Optical Kerning

An optical kerning engine for spacing adjacent glyphs of arbitrary fonts visually uniformly.

The algorithm attempts to normalise the area between adjacent glyphs by tracing the contours and eliminating statistical and optical outliers, then the gap distances are used to compute an overall statistical average, and characters are shifted horizontally to normalise that value. By ‘average’ we mean a value having minimal Median Absolute Deviation, although Standard Deviation is used instead in some situations.

More to follow…
