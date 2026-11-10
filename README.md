# EYEWITNESS

The project presents 12 astronomy chapters. Chapter 5 uses the supplied Dark Ages animation; Chapter 6 covers the first stars; Chapter 7 introduces galaxies, their growth, and evolution; Chapter 8 compares galaxy shapes, sizes, interactions, and active nuclei with the supplied Types of Galaxies animation and real, credited NASA observations. The Chapter 8 categories overlap where astronomy does: a galaxy can be a barred spiral and also a Seyfert, while “dwarf” describes scale and “interacting” describes a state. The animation is clearly labelled as conceptual artwork, not a photographic or chronological record. The former Milky Way model and video have been removed from Chapter 8.

The shared speed control goes from 0.25× to 2×. Chapters 5–11 default to 2×; chapters 1–4 and 12 default to 1×. The chapter menu and bottom timeline jump directly to each chapter. The supplied chapter animations are embedded in `index.html`; standalone HTML copies of the Dark Ages, First Stars, Galaxies, Solar System, and Cosmic Timeline experiences are included for reference. The app uses NASA images first and Wikimedia Commons as a fallback, with image credits and source links shown alongside each image.

## Publish with GitHub Pages

1. Upload `index.html` to the top level of your GitHub repository and commit it to the `main` branch. The standalone animation files and `README.md` are optional; the chapter animations are embedded in `index.html`.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/(root)`. Save.
4. Open the website link shown in the Pages settings screen after publishing finishes.

No build step is required. Three.js, display fonts, and the NASA image service require an internet connection; gallery cards fall back to Wikimedia Commons when NASA cannot provide a matching image.