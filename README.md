# ORBITA — Space Communications

A front-end concept website for a sovereign space communications infrastructure provider. Built as a static HTML/CSS/JS single-page site with 16 supporting pages covering constellation architecture, services, spectrum, partnerships, and organizational detail.

## Project Structure

```
space-communications/
├── index.html                          # Main landing page
├── contact.html                        # Contact / inquiry form
├── capabilities-satellite-broadband.html
├── capabilities-secure-government.html
├── capabilities-maritime-aviation.html
├── capabilities-direct-broadcast.html
├── capabilities-scientific-relay.html
├── network-leo-constellation.html
├── network-geo-platform.html
├── network-ground-stations.html
├── network-spectrum-portfolio.html
├── network-orbital-filing.html
├── organization-about.html
├── organization-partnerships.html
├── organization-itu-compliance.html
├── organization-careers.html
├── organization-press-media.html
└── README.md
```

### Page Groups

| Section | Pages | Description |
|---|---|---|
| **Landing** | `index.html` | Hero, stats bar, satellite architecture, services, frequencies, collaboration partners, ground stations, live telemetry, CTA |
| **Contact** | `contact.html` | Mission control contact form and inquiry routing |
| **Capabilities** | 5 pages | Satellite Broadband, Secure Government, Maritime & Aviation, Direct Broadcast, Scientific Telemetry Relay |
| **Network** | 5 pages | LEO Constellation, GEO Platform, Ground Stations, Spectrum Portfolio, Orbital Filing |
| **Organization** | 5 pages | About ORBITA, Partnerships, ITU Compliance, Careers, Press & Media |

## Tech Stack

- **HTML5** — Static pages (no build step, no framework)
- **CSS3** — Custom properties, grid, flexbox, clip-path, animations, responsive breakpoints
- **Vanilla JS** — Canvas starfield, waveform visualizer, scroll reveal, animated counters, telemetry ticker, custom cursor

## Design

- **Fonts:** Orbitron (display), Exo 2 (body) — via Google Fonts
- **Palette:** Black `#020408`, Gold `#FFD700`, Amber `#FF6B00`, White `#FFF8F0`
- **Theme:** Dark space-operations aesthetic with orbital ring animations and signal-waveform visualizations
- **Cursor:** Custom gold dot with trailing ring, enlarges on interactive elements

## Features

- Animated starfield background canvas
- Orbital ring rotation system on hero and satellite sections
- Scroll-triggered reveal animations
- Animated statistics counter bar
- Interactive signal waveform visualizer with band switching
- Live telemetry data stream ticker
- SVG satellite and orbital illustrations
- Frequency band utilization bars with scroll-triggered animation
- Responsive layout (desktop → tablet → mobile)
- Reduced-motion support via `prefers-reduced-motion`

## Getting Started

No build step or server required. Open any `.html` file directly in a browser:

```
open index.html
```

For local development, any static file server works:

```
npx serve .
```

## Navigation

The footer on every page contains three link columns — Capabilities, Network, and Organization — providing full cross-site navigation. The landing page nav bar anchors to on-page sections (`#satellites`, `#services`, `#frequencies`, `#collaboration`, `#ground-stations`).

## License

All rights reserved. This is a concept project.
