# Glitch Lab 🌐

A curated showcase of procedural, AI-synthesized, and model-generated 3D interactive worlds and real-time WebGL environments.

Designed to be hosted directly on GitHub Pages (`*.github.io/Glitch-lab`).

## 📁 Repository Structure

```text
Glitch-lab/
├── index.html                # Root hub & world showcase portal (GitHub Pages ready)
├── README.md                 # Project documentation
├── assets/
│   └── thumbnails/           # High-resolution world preview renders
│       ├── atlantis.png      # In-engine WebGL capture of Atlantis
│       ├── neon-megacity.jpg # Cyberpunk megacity concept render
│       └── chrono-mirage.jpg # Shifting desert expanse render
└── worlds/
    └── Atlantis/
        ├── index.html        # "Atlantis: Before the Fall" (Three.js procedural voxel world)
        ├── prompt.txt        # Full generation prompt & rules
        └── thumbnail.png     # World thumbnail
```

## 🚀 Worlds

### 1. Atlantis: Before the Fall
- **World Path:** [`worlds/Atlantis/index.html`](worlds/Atlantis/index.html)
- **Prompt:** [`worlds/Atlantis/prompt.txt`](worlds/Atlantis/prompt.txt)
- **Tech Stack:** Three.js 0.175, Simplex Noise, Unreal Bloom Postprocessing, GSAP, MP4-Muxer
- **Features:**
  - 1,200m × 1,200m procedural concentric ring-city voxel architecture
  - 3rd-person character controller (WASD + Sprint + Atlantean Skiff navigation)
  - 60s scenic world tour & 10-shot cinematic trailer camera modes
  - Dynamic day/night cycle (Dawn, Golden Noon, Sunset, Bioluminescent Night)
  - Procedural Web Audio synthesizer score
  - Built-in in-browser 1080p/60fps MP4 video recording studio

## 💻 Local Preview

You can open `index.html` directly in any modern web browser or serve it using any static HTTP server:

```bash
# Python
python -m http.server 8000

# or Node.js / npx
npx serve .
```

Then visit `http://localhost:8000`.
