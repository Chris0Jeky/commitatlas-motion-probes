# commitatlas-motion-probes
Synthetic SVG motion compatibility probes for CommitAtlas issue #113

These fixtures are synthetic-only and do not include private data, tokens, or runtime outputs.

## Fixture links
- [Index](tests/fixtures/motion-probes/index.html)
- [css-breathe](tests/fixtures/motion-probes/css-breathe.svg)
- [css-enter](tests/fixtures/motion-probes/css-enter.svg)
- [css-from-state-control](tests/fixtures/motion-probes/css-from-state-control.svg)
- [css-offset-path](tests/fixtures/motion-probes/css-offset-path.svg)
- [css-plot](tests/fixtures/motion-probes/css-plot.svg)
- [smil-animate-motion](tests/fixtures/motion-probes/smil-animate-motion.svg)
- [smil-plot](tests/fixtures/motion-probes/smil-plot.svg)
- [smil-transform](tests/fixtures/motion-probes/smil-transform.svg)
- [reduced-motion-control](tests/fixtures/motion-probes/reduced-motion-control.svg)

## Probe embeds

<img src="tests/fixtures/motion-probes/css-breathe.svg" alt="css-breathe" width="400" />
<img src="tests/fixtures/motion-probes/css-enter.svg" alt="css-enter" width="400" />
<img src="tests/fixtures/motion-probes/css-from-state-control.svg" alt="css-from-state-control" width="400" />
<img src="tests/fixtures/motion-probes/css-offset-path.svg" alt="css-offset-path" width="400" />
<img src="tests/fixtures/motion-probes/css-plot.svg" alt="css-plot" width="400" />
<img src="tests/fixtures/motion-probes/reduced-motion-control.svg" alt="reduced-motion-control" width="400" />
<img src="tests/fixtures/motion-probes/smil-animate-motion.svg" alt="smil-animate-motion" width="400" />
<img src="tests/fixtures/motion-probes/smil-plot.svg" alt="smil-plot" width="400" />
<img src="tests/fixtures/motion-probes/smil-transform.svg" alt="smil-transform" width="400" />

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="tests/fixtures/motion-probes/reduced-motion-control.svg">
  <source media="(prefers-color-scheme: dark)" srcset="tests/fixtures/motion-probes/smil-transform.svg">
  <img src="tests/fixtures/motion-probes/smil-animate-motion.svg" alt="motion-picture-fallback">
</picture>