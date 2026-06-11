# GutJourney

A first/third-person educational ride through the human digestive and urinary
systems, built with [Three.js](https://threejs.org/). Pick a food or drink and a
host, then watch your chosen morsel get chewed, drowned in stomach acid, stripped
of nutrients across the intestines, and finally expelled into the toilet — as a
3D **poop** (solids) or a **droplet** of urine (liquids), complete with a splash
and procedural Web Audio sound.

## Features

- Anatomically themed organs with displaced, mottled flesh-tube geometry
- Third-person camera that trails a real 3D food/poop/droplet avatar
- Sphincter "iris" transitions between organs (no black cuts)
- Procedural soundscape (gut rumbles, heartbeat, pee/plop splashes)
- Realistic toilet bowl with refractive water and a splash finale

## Running locally

It's a single static file — no build step. Serve the folder with any static
server and open the root:

```bash
npx serve .
# then open http://localhost:3000
```

Or just open `index.html` directly in a browser.

## Deploying

This is a static site. On [Vercel](https://vercel.com), import the repo and deploy
with the default settings — `index.html` is served at the root, no framework or
build command required.

## Media credits

- `meow.mp3` — ["Meow"](https://commons.wikimedia.org/wiki/File:Meow.ogg) by Dan Crosby, Wikimedia Commons, [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
- `fart1.wav` — ["Human fart"](https://commons.wikimedia.org/wiki/File:Human_fart.wav) by Subhashish Panigrahi, Wikimedia Commons, [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
- `fart2.wav` — ["Flatulence"](https://commons.wikimedia.org/wiki/File:Flatulence.wav) by JohnSumisu, Wikimedia Commons, [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
- `fart3.wav` — ["Flatus"](https://commons.wikimedia.org/wiki/File:Flatus.wav), Wikimedia Commons, [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
- Bathroom poster — ["Taylor Swift at the 2023 MTV Video Music Awards"](https://commons.wikimedia.org/wiki/File:Taylor_Swift_at_the_2023_MTV_Video_Music_Awards_(2)_(cropped).png) by iHeartRadioCA, Wikimedia Commons, [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) (loaded at runtime).
- [Three.js](https://threejs.org/) r128, MIT license (vendored as `three.min.js`).
