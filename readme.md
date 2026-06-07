# Abhijeet Room

An interactive 3D room portfolio for Abhijeet Ranjan. The site presents a personal desktop-inspired room with a working computer OS, project gallery, arcade machine, whiteboard signature, resume access, contact links, and personal timeline content.

## Overview

Abhijeet Room is built as a real-time WebGL portfolio experience. Visitors can move through the room, interact with monitors, open the embedded computer interface, browse projects, view the resume, explore the X-style timeline, and play the arcade section.

## Features

- Interactive 3D portfolio room.
- Working desktop-style computer OS inside the room.
- X-style timeline with education, projects, favorites, and personal posts.
- Project gallery featuring CTX, DeploySense, GhostGate, and this portfolio.
- Playable arcade machine.
- Interactive whiteboard with Abhijeet's signature.
- Resume download, contact form, and social links.
- Optimized static assets for a polished browser experience.

## Tech Stack

- Three.js for the 3D scene and WebGL rendering.
- JavaScript for interaction logic and app behavior.
- GLSL shaders for visual effects.
- Webpack for bundling and local development.
- HTML and CSS for the embedded apps and interface screens.
- Blender-generated 3D assets, textures, and baked room elements.

## Projects Included

- CTX: AI memory and context tooling experiments.
- DeploySense: Deployment intelligence and review workflow concept.
- GhostGate: Privacy-focused routing and networking lab.
- Abhijeet Room: This interactive 3D portfolio.

## Getting Started

Install dependencies:

```bash
npm install
```

Run locally:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

The production build is generated in the `dist` directory.

## Netlify Deployment

Netlify should use:

```text
Build command: npm run build
Publish directory: dist
```

The repository includes `netlify.toml` with this configuration.

## Project Structure

```text
src/                         Main Three.js room source
src/Experience/              Room systems, camera, renderer, navigation, and screens
static/assets/               Room models, textures, sounds, icons, and resume
static/apps/abhijeet-os/     Embedded Abhijeet OS app for the computer monitor
static/apps/abhijeet-gallery/Embedded project gallery app for the side monitor
bundler/                     Webpack configuration
```

## Links

- GitHub: https://github.com/Abhi190702
- LinkedIn: https://www.linkedin.com/in/abhijeet-ranjan-7056ab22a/
- Instagram: https://www.instagram.com/abhi.lonelyfans/
- Tame Impala on Apple Music: https://music.apple.com/us/artist/tame-impala/290242959

## License

This project is licensed under the MIT License.
