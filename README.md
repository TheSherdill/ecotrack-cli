# ecotrack-cli
Real-time server carbon footprint &amp; energy consumption monitoring tool.
# 🌱 EcoTrack: Real-Time Server Carbon Footprint Monitor

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)

**EcoTrack** is a lightweight, open-source green computing daemon designed to estimate server power usage (kWh) and environmental carbon emissions ($gCO_2eq$) in real-time based on live CPU and RAM usage.

---

## 🚀 Key Features

- ⚡ **Real-time Power Telemetry**: Monitors CPU TDP and memory consumption.
- 🌎 **Carbon Footprint Estimation**: Translates hardware usage into hourly/daily $CO_2$ emissions using global grid carbon intensity metrics.
- 🔌 **REST API & CLI Interface**: Seamless integration with Prometheus, Grafana, or local terminal workflows.
- 🐳 **Lightweight Footprint**: Optimized containerization to minimize monitoring overhead.

---

## 🛠️ Quick Start

### 1. Installation

```bash
git clone [https://github.com/TheSherdill/ecotrack-cli.git](https://github.com/TheSherdill/ecotrack-cli.git)
cd ecotrack-cli
pip install -r requirements.txt
