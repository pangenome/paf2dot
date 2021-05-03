# paf2dot

Use gnuplot to generate a dotplot from sequence alignments in PAF format.
Only the alignment / mapping start and end are plotted.

## usage

To render a png (out.png):

```
paf2dot png large z.paf
```

For an interactive plot, zoomable with mouse scroll and right-click bounding box:

```
paf2dot x11 large z.paf
```
