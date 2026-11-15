# Garage

Interactive 3D car parts and owner maintenance guides. Click any part of a 3D car to see what it does, how to maintain it and which warning signs to watch for.

## Structure

```
index.html                          Home page (topics index)
toyota/
  index.html                        Toyota topic index
  innova-2012-diesel/index.html     Toyota Kijang Innova 2012 · 2.5 Diesel
  fortuner-2023-diesel/index.html   Toyota New Fortuner 2023 · 2.4 & 2.8 Diesel
  gr-supra/index.html               Toyota New GR Supra 3.0
.nojekyll                           Serve the files as they are (no Jekyll build)
```

Every page is a single self-contained HTML file: the 3D engine, fonts and images are inlined, so there is nothing to install or build, and the pages also open straight from disk.

## Publish with GitHub Pages

1. Upload the contents of this folder to the root of the repository.
2. In the repository, open **Settings > Pages**.
3. Under **Build and deployment > Source**, choose **Deploy from a branch**, then pick the branch (for example `main`) and the `/ (root)` folder, and save.

## Adding more guides

- New car from an existing maker: add a folder such as `toyota/<model>/index.html`, then add it to `toyota/index.html` and to the Toyota list on the home page.
- New maker: add a folder such as `honda/index.html` for its topic index, with one subfolder per car, then add a row under Topics on the home page.

The 3D models are simplified for learning. Always follow the owner's manual and leave safety-critical work to a qualified mechanic.
