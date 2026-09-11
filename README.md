How Many Bananas Away 🍌🎯


Basic Details


Team Name: blaah
Team Members
Team Lead: Aadithyan Unnikrishnan - [sngce]

Project Description
A GPS-powered journey tracker and navigation web app that completely bans all sensible metric and imperial units (meters, kilometers, miles). Instead, it calculates your physical displacement in real-time and converts it exclusively into bananas, giraffes, double-decker buses, blue whales, and vaguely-sized city blocks.

The Problem (that doesn't exist)
For centuries, humanity has suffered under the cold, unfeeling tyranny of the metric and imperial systems. Telling someone you walked "1.2 kilometers" inspires zero emotional resonance. How can anyone truly comprehend physical effort without knowing how many standard Cavendish bananas laid tip-to-stem it would take to bridge the gap? Standard GPS apps are boring, excessively precise, and painfully un-curved.

The Solution (that nobody asked for)
"How Many Bananas Away" intercepts raw satellite GPS coordinates, runs them through an internal Haversine distance engine, ruthlessly scrubs all traces of meters from the user interface, and renders your journey in a bold, high-contrast Neo-Brutalist aesthetic. It features an interactive Leaflet map, a built-in "Demo Walk" simulator for indoor sofa-explorers, Web Audio fanfare chimes, and an achievement system rewarding milestones like "Couch Potato" (staying completely still for 45 seconds).


Technical Details

Technologies/Components Used
For Software:
Languages used: HTML5, CSS3 (Neo-Brutalism design system), JavaScript (ES2022)
Frameworks used: Self-contained client-side architecture (compatible with Vite / GitHub Pages)
Libraries used:
Leaflet.js v1.9.4 (OpenStreetMap engine with custom contrast/saturation tile filters)
Web Geolocation API (navigator.geolocation.watchPosition with high accuracy mode)
Web Audio API (procedural 8-bit fanfare chime synthesis with zero external audio assets)
Tools used:
OpenStreetMap Tile Servers
Vite dev server & bundler
Git & GitHub
Implementation
For Software:
Installation
code
Bash
# Clone the repository
git clone https://github.com/your-username/how-many-bananas-away.git

# Navigate into the project folder
cd how-many-bananas-away

# Install dependencies (optional if running standalone index.html)
npm install
Run
code
Bash
# Run local dev server with Vite
npm run dev

# Or simply open index.html directly in any web browser!
Project Documentation
Screenshots
![Dashboard Overview](<img width="1592" height="825" alt="Image" src="https://github.com/user-attachments/assets/ae9051dd-488e-4bef-b1d3-fb79ee60ce1e" />)
Main Neo-Brutalist Dashboard displaying real-time banana counter, active expedition chronometer, and tempo detection.
![Leaflet Map & Route Tracker](<img width="660" height="607" alt="Image" src="https://github.com/user-attachments/assets/1bdcff64-7f3b-4e3b-9265-1d442ef4ebaa" /> )
High-contrast Leaflet.js satellite canvas plotting GPS coordinates with custom thick strokes and pulsing red markers.
![Stamps & Trophies Grid]( <img width="866" height="852" alt="image" src="https://github.com/user-attachments/assets/4957fa94-dd6a-4d75-8a55-0f97db10d601" /> )
Neo-brutalist achievement sticker grid showing unlocked badges (Unit Collector, Couch Potato, Marathoner, etc.).

#diagram 
```

                    ┌────────────────────────┐ 
                    │  Physical User Motion  │
                    └───────────┬────────────┘
                                │
                                ▼
                    ┌────────────────────────┐
                    │  Web Geolocation API   │
                    │  (Lat / Lon / Acc)     │
                    └───────────┬────────────┘
                                │
                                ▼
                    ┌────────────────────────┐
                    │ Low-Pass Jitter Filter │
                    │ (Rejects drift < 3.2m) │
                    └───────────┬────────────┘
                                │
                                ▼
                    ┌────────────────────────┐
                    │  Haversine Math Core   │
                    │  (Calculates Δ dist)   │
                    └───────────┬────────────┘
                                │
                                ▼
                    ┌────────────────────────┐
                    │ Obfuscation Matrix     │
                    │ (Purges SI units)      │
                    └───────────┬────────────┘
                                │
      ┌───────────┬─────────────┼─────────────┬───────────┐
      │           │             │             │           │
      ▼           ▼             ▼             ▼           ▼
  🍌 Bananas   🦒 Giraffes   🚌 Buses    🏈 Fields   🐋 Whales
  (~0.178m)    (~5.0m)       (~9.5m)     (~100.0m)   (~30.0m)
      │           │             │             │           │
      └───────────┴─────────────┼─────────────┴───────────┘
                                │
                                ▼
                    ┌────────────────────────┐
                    │ Neo-Brutalist UI       │
                    └───────────┬────────────┘
                                │
 ┌─────────────────┬────────────┴────────────┬──────────────────┐
 │                 │                         │                  │
 ▼                 ▼                         ▼                  ▼
Giant Readout    Leaflet Map             Motion State      Audio Toasts &
& Unit Pill      Polyline & Marker       Analyzer          Achievements
Project Demo
```
Video
[https://youtu.be/ATiBDjKMt98]
Demonstrating live GPS walk tracking, switching measurement units in real-time, triggering simulated demo locomotion, and unlocking the "Couch Potato" achievement.
Additional Demos
Live Hosted Application(using vercel): [https://uselessprojectbananatraveller.vercel.app/]

Team Contributions

Aadithyan Unnikrishnan: Core GPS tracking logic, Haversine formula calculation, signal jitter filter, and Web Audio API synthesizer.

Team Member 2: Neo-Brutalist UI system architecture, high-contrast color styling, and Leaflet map tile rendering.

Team Member 3: Achievement trigger engine, unit configuration matrix, and responsive mobile adaptations.

Made with ❤️ at TinkerHub Useless Projects
![Image](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Image](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)
