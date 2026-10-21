<div align="center">

# Breathing Cosmos

**A generative mandala that breathes with you.**

Real-time light, sound and space, all synthesized in your browser.

[**Enter the cosmos →**](https://YOUR-USERNAME.github.io/breathing-cosmos/) &nbsp;·&nbsp; Headphones recommended

</div>

---

## About

Stand at the center of a vast mandala sphere and watch threads of metallic light drift, swirl and spiral into a glowing throat at the heart of it all.

There are no images and no audio files. Every frame and every sound is generated live, and no two moments are ever the same.

## Controls

| Input | Effect |
|---|---|
| Move the mouse | The light follows you, threads ignite, the view shifts with parallax |
| Drag / tilt your device | Look around (gyroscope supported on mobile) |
| Scroll / two-finger swipe | Move through space, with depth-of-field blur |
| Click | Reveal the controls. Click again or press `Space` to switch between Gold and Jade |
| Hold (or press `B`) | Inhale. Release to exhale. The cosmos follows your breath |
| `V` / mic button | Drive the visuals with your voice: sound to exhale, silence to inhale |
| Drop in an audio file | Let your own music shape the visuals while the original sound fades out |
| `M` mute · `G` gyroscope off · `E` trigger a random event | |

## Features

- **Spherical space**: you stand at the center of the world and can look in any direction
- **Vortex horizon**: a gravitational throat pulls threads into a spiral and hints at another world within
- **A living breath**: one cycle takes about 11 seconds, and each peak sends a dispersive ring of light outward
- **Chance events**: raindrop ripples, fireflies, light curtains, heartbeats and prism shifts, never on a schedule you can predict
- **Synthesized sound**: deep drones, metallic bells and granular textures, wrapped in reverb and tape-style delay
- **Adaptive quality**: resolution scales down automatically when the frame rate drops

## Run

Open `index.html` in any modern browser.

The microphone needs `https` or `localhost`, so it will not work when you open the file directly from disk. The hosted version supports it.

```bash
# optional: serve locally
npx serve .
```

## Built with

Vanilla HTML, CSS and JavaScript · WebGL with hand-written GLSL (two-pass rendering, ping-pong buffers for temporal blur) · Web Audio API

## A gentle note

The image is always in motion and the center can be bright. Long sessions may cause eye strain or mild dizziness.

Keep some ambient light in the room, lower your screen brightness, and look into the distance for a moment every 20 minutes.

## License

MIT
