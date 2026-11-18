# Interferometry_Visualizer
Interactive simulator of what a telescope array would actually see of an Earth-like exoplanet.

- **Simple mode:** an ideal, fully filled array (as sharp as one mirror the size of the array). You set the distance, wavelength, array size, mirror area, brightness and observing time. Closer, bigger or shorter-wavelength gives a sharper image; more area, more time or a brighter planet gives less noise.
- **Advanced mode:** real telescope layouts (2 to 150 telescopes), combined like a hypertelescope. Includes array rotation, spectral channels, phasing errors, starlight suppression, backgrounds, Richardson–Lucy deconvolution, and (u,v) and PSF plots.

Brightness comes from real physics: reflected sunlight plus thermal emission, Poisson photon noise, starlight glare and zodiacal light. Both images share one brightness scale. Every slider also has a box where you can type a value with units (e.g. `10 pc`, `150 km`, `30 h`, `1e-9`).

`index.html` is self-contained: the Earth image is embedded as a data URL. It works by double-clicking the file or from any static host, such as GitHub Pages. `img/earth.jpg` is the source of that embedded image. If you replace it, re-embed it in `index.html`.
