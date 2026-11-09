# GitPulse — 3D Interactive GitHub Visualizer

A polished, high-performance GitHub profile visualizer featuring interactive 3D perspective physics, authentic collectible mascot companions, and telemetry dashboards.

![GitPulse Mascot](assets/mascot-transparent.png)

## ✨ Highlights

- **3D Interactive Mascot Toy**:
  - Real-time cursor-tracking perspective tilt (`rotateX`, `rotateY`).
  - Dynamic 3D specular glare sweep across the curved finish.
  - Orbiting 3D contribution cubes floating in space with individual Z-depth parallax.
  - Interactive expression transitions (switches to smiling face on input focus and hover).
  - Click-to-bounce squash-and-stretch spring physics.
- **Dynamic Snake Wave Runner**:
  - Serpentine contribution cube wave track.
  - Animated mascot actor surfing the sinusoidal wave path with bank-angle tilting and speed aura.
  - Real-time telemetry gathering progress indicator.
- **Deep Profile Metrics & Visualizer**:
  - Dynamic developer archetype categorization (e.g. Open Source Engineer, Systems Architect).
  - Full 365-day Matrix Contribution Calendar.
  - Multi-language technology ecosystem breakdown.
  - Monthly commit velocity trajectories & streak analytics.
  - Linear/CodEyes-inspired "Card Story" generation.
- **Resilient Telemetry Fetching**:
  - Direct GitHub REST API v3 integration with persistent `localStorage` cache.
  - CORS proxy mirror fallback to handle unauthenticated rate limits seamlessly.
  - In-app PAT management to expand capacity to 5,000 req/hr.

## 🚀 Getting Started

Simply serve the project folder with any local web server:

```bash
# Python 3
python3 -m http.server 7777

# Node / npx
npx serve -l 7777 .
```

Then open `http://localhost:7777` in your browser.

## 🛠️ Tech Stack

- Vanilla JavaScript (ES2022+ Async/Await, Web Components, DOM APIs)
- Modern CSS (Custom properties, 3D Transforms, Glassmorphism, Keyframe animations)
- Semantic HTML5
- GitHub REST API v3 & Jogruber Contribution Matrix API
