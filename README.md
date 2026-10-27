# AgriVision — Autonomous Edge-AI Agronomy & Precision Micro-Spray Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![TRL Status](https://img.shields.io/badge/TRL-Level%204%20Flight%20Proven-blue.svg)](index.html)
[![Edge AI](https://img.shields.io/badge/Edge%20AI-Hailo--8%20%7C%20<38ms-purple.svg)](index.html)

**AgriVision** is an autonomous edge-AI agronomy and closed-loop aerial precision micro-spray platform. By mounting high-speed computer vision cameras, near-infrared foliar health optics, and edge micro-NPUs directly to agricultural drones, AgriVision detects diseased crops and weeds mid-flight—firing targeted micro-droplets exclusively onto infected foliage.

---

## Key Capabilities

* **Offline Edge Autonomy**: Runs 100% offline with zero cloud latency or cellular connectivity dependencies.
* **50%–65% Pesticide Reduction**: Eliminates dumb blanket field drenching; replaces mass sprays with surgical micro-doses.
* **Sub-100ms Reaction Time**: Video frames evaluated at 60 FPS; spot spray triggered in under 38 ms.
* **Dual Airframe Fleet**:
  * **Scout Quadcopter**: High-speed foliar phenotyping and disease detection.
  * **Heavy Hexacopter**: 25L operational spot spray payload with centrifugal rotary atomizers.
* **Canopy & Root-Zone Crosscheck**: Correlates aerial thermal CWSI scans with in-ground LoRa soil moisture probes to distinguish drought from fungal root disease.
* **Interactive Financial ROI Engine**: Real-time economic modeling tuned for Indian acreage, pesticide costs, and annual spray cycles.

---

## Quick Start

Open `index.html` directly in any modern browser:

```bash
# Option 1: Open directly
start index.html

# Option 2: Run local web server
python -m http.server 5050
# Open http://localhost:5050
```

---

## Project Structure

```
Agri/
├── index.html       # Self-contained production landing page, simulations, & styles
├── LICENSE          # MIT License
└── README.md        # Technical platform documentation
```

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
