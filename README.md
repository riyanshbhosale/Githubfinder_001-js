# GitPulse — Premium GitHub Profile Visualizer

A polished, high-performance GitHub profile visualizer and developer analytics platform. Built with an editorial Obsidian dark theme, sub-second telemetry fetching, and deep repository insights.

![GitPulse Banner](assets/mascot-transparent.png)

---

## ⚡ Key Features

### 🎯 Accurate Developer Telemetry
- **Accurate Star Metrics**: Accurately tracks starred repositories and authored code stars without distortion.
- **Smart Fork Filtering**: Excludes third-party forks from authored counts and personal repository metrics.
- **Technology Ecosystem**: Real multi-language byte breakdown powered by GitHub Linguist with instant toggle between **Personal Repositories** and **All Repos + OSS**.
- **Contribution Calendar Heatmap**: 365-day interactive matrix visualization with commit frequency and inspection tooltips.
- **Streak & Velocity Analytics**: Current streak, longest streak, active days, and monthly commit trajectory bars.

### 💎 Editorial Obsidian UI
- **Zero-Glow Executive Design**: Clean, modern dark mode inspired by developer tools like Linear, Raycast, and GitHub Next.
- **Interactive Mascot Companion**: Subtle 3D spatial tilt physics and dynamic expressions responsive to user interaction.
- **Developer Card Story**: Auto-generated milestone chapters summarizing developer journey, top achievements, and archetypes.
- **Sharable Executive Badge**: High-density profile card ready for export and sharing.

### 🚀 Resilient & Fast Data Architecture
- **Sub-Second Loading**: Parallelized `Promise.all` data pipeline delivers complete profiles in under a second.
- **Multi-Proxy Rate-Limit Bypass**: Built-in multi-tier fallback (Direct API → CORS Proxy Mirrors) ensures smooth browsing even when GitHub's unauthenticated 60 req/hr rate limit is reached.
- **Optional GitHub PAT Support**: Easily connect your own Personal Access Token to unlock 5,000 requests/hour.
- **Smart TTL Caching**: 15-minute persistent `localStorage` cache with automatic version validation to save bandwidth and prevent redundant API roundtrips.

---

## 🛠️ Tech Stack

- **Frontend**: Vanilla JavaScript (ES2022+ Async/Await, Canvas API, DOM APIs)
- **Styling**: Vanilla CSS3 (Custom Properties, Flexbox/Grid, 3D CSS Transforms)
- **APIs**: GitHub REST API v3, GitHub Linguist endpoint, Jogruber Contribution Matrix API
- **Zero Dependencies**: 100% pure vanilla web technologies with no build steps or bundlers required.

---

## 🏁 Quick Start

Clone the repository and launch a local static server:

```bash
git clone https://github.com/riyanshbhosale/Githubfinder_001-js.git
cd Githubfinder_001-js
```

Run with Python:
```bash
python3 -m http.server 7777
```

Then open your browser and navigate to:
```
http://localhost:7777
```

Or simply open `index.html` directly in any modern web browser.

---

## 📁 Project Structure

```
├── index.html        # Main application layout and dashboard structure
├── app.js            # Telemetry client, data processing, and UI controllers
├── style.css         # Obsidian design system, layouts, and typography
├── assets/           # Mascot artwork and static visual assets
└── README.md         # Project documentation
```

---

## 📄 License

MIT License © [Riyansh Bhosale](https://github.com/riyanshbhosale)
