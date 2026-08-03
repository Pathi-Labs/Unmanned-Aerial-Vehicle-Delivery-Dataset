<div align="center">

# 🚁 UAV Delivery Dataset

### Large-scale Drone Delivery Trajectory Dataset for AI, Robotics & Autonomous Systems

[![Website](https://img.shields.io/badge/Website-pathilabs.com-7A5AF8?style=for-the-badge)](https://pathilabs.com)
[![Dataset](https://img.shields.io/badge/Dataset-UAV%20Delivery-blue?style=for-the-badge)](#download)
[![License](https://img.shields.io/badge/License-GPL%20v3-green?style=for-the-badge)](#license)

</div>

---

# About

The **UAV Delivery Dataset** is a simulated drone trajectory dataset designed to support research in:

- Autonomous Drone Navigation
- AI-powered Delivery Systems
- UAV Path Planning
- Robotics
- Reinforcement Learning
- Drone Fleet Optimization
- Intelligent Transportation
- Autonomous Logistics

The dataset was generated using the **BlueSky Open Air Traffic Simulator (ATS)** together with a custom **UAVTrajectory.py** plugin.

It contains thousands of simulated delivery missions under different operating conditions including multiple UAV speeds, flight altitudes, and wind directions.

---

# Dataset Statistics

| Feature | Value |
|----------|--------|
| Deliveries | **6,911** |
| Simulation Platform | BlueSky ATS |
| Flight Distance | Up to 5 km |
| Wind Conditions | 5 |
| UAV Speed Variations | Multiple |
| Altitude Variations | Multiple |

---

# AI Applications

This dataset can be used for research in:

- 🚁 Drone AI
- 🤖 Robotics
- 🧠 Machine Learning
- 📍 Trajectory Prediction
- 🛰 Autonomous Navigation
- 📦 Drone Delivery
- 📊 Route Optimization
- 🎯 Reinforcement Learning
- ⚡ Autonomous Logistics
- 🌍 Smart Cities

---

# Flight Parameters

Each simulation contains multiple flight configurations.

## Folder Structure

```
UAV_SPEED
WIND_SPEED
UAV_ALTITUDE
```

Each configuration contains five simulations:

- No Wind
- 0° Wind
- 90° Wind
- 180° Wind
- 270° Wind

---

# Dataset Features

| Attribute | Description | Unit |
|-----------|-------------|------|
| simt | Simulation Time | seconds |
| id | UAV Identifier | string |
| type | UAV Model | string |
| lat | Latitude | degrees |
| lon | Longitude | degrees |
| alt | Altitude | meters |
| distflown | Distance Travelled | meters |
| temp | Air Temperature | Kelvin |
| trk | Track Angle | degrees |
| hdg | Heading Direction | degrees |

---

# Sample Applications

Researchers commonly use this dataset for:

- Flight Path Prediction
- Route Planning
- Delivery Optimization
- Drone Swarm Intelligence
- Multi-Agent Systems
- Reinforcement Learning
- Trajectory Forecasting
- AI Navigation Systems
- Autonomous UAV Research

---

# Download

## Dataset

https://drive.google.com/drive/folders/18qwp2zaRoBjtkId5sz83vArWgZxrZLCi?usp=sharing

---

# Simulator

BlueSky Open Air Traffic Simulator

https://github.com/TUDelft-CNS-ATM/bluesky

---

# Citation

If you use this dataset in your research, please cite the original publication.

```bibtex
@inproceedings{rigoni2022delivery,
  title={Delivery with UAVs: a simulated dataset via ATS},
  author={Rigoni, Giulio and Pinotti, Cristina M and Bhumika and Das, Debasis and Das, Sajal K},
  booktitle={2022 IEEE 95th Vehicular Technology Conference (VTC2022-Spring)},
  pages={1--6},
  year={2022},
  organization={IEEE}
}
```

---

# Original Research

The dataset is derived from research based on:

**Online Food Delivery Platform Dataset**

https://www.sciencedirect.com/science/article/pii/S2352340919303609

---

# License

This dataset is distributed under the **GNU General Public License v3.0 (GPL-3.0)**.

Please follow the original license terms when redistributing or creating derivative works.

---

# Attribution

This repository is maintained by **Pathi Labs LLP** to improve accessibility for AI researchers and developers.

**Pathi Labs does not claim ownership of this dataset.**

All intellectual property, research credit, and licensing belong to the original authors.

---

# About Pathi Labs

Pathi Labs LLP is an AI Research & Engineering company focused on developing intelligent systems for:

- Artificial Intelligence
- Machine Learning
- Computer Vision
- Drone AI
- Agentic AI
- Large Language Models (LLMs)
- Enterprise AI
- Autonomous Systems

🌐 Website

https://pathilabs.com

---

<div align="center">

### Building the Future of AI, Robotics & Autonomous Systems

⭐ Follow Pathi Labs for AI datasets, open-source models, and research resources.

</div>
