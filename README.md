# QGC Automated Flight Planner

Welcome to the **QGC Automated Flight Planner**! This software automates mission planning for drone operations, including point-to-point navigation, delivery routes, security patrols, tower inspections, and linear flight paths. Designed for ground control operations, the software ensures efficiency, accuracy, and compatibility with QGroundControl.

---

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Getting Started](#getting-started)
4. [Tools and Usage](#tools-and-usage)
   - [Point A to Point B Planning](#point-a-to-point-b-planning)
   - [Delivery Route](#delivery-route)
   - [Multi-Delivery](#multi-delivery)
   - [Security Route](#security-route)
   - [Linear Flight Route](#linear-flight-route)
   - [Tower Inspection](#tower-inspection)
5. [Screenshots](#screenshots)
6. [Support](#support)
7. [License](#license)

---

## Features

- **Automated Route Generation**: Plans precise flight paths for various scenarios.
- **Waypoint Optimization**: Adds customizable waypoint intervals and geofence buffers.
- **Multi-Tool Support**: Includes delivery routing, tower inspection, and security patrol tools.
- **QGroundControl Compatibility**: Exports `.plan` files for seamless use in QGroundControl.
- **Terrain Integration**: Adjusts flight altitude based on real-time elevation data.

---

## Installation

### Prerequisites

- **Python 3.8+**
- **Git**: [Install Git](https://git-scm.com/)
- **pip**: Package manager for Python dependencies.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/automated-flight-planning.git
   cd automated-flight-planning
