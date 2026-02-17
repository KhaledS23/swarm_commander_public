# Swarm Commander

**Swarm Commander** is a project designed to make drone swarm simulations more accessible and visual.

It bridges the gap between complex ArduPilot simulations and user-friendly control, giving you a modern dashboard to manage multiple simulated drones at once.

> ** Note:** This project is currently in **active development**. The primary focus right now is on **simulation** (SITL). While it is technically possible to control real drones via UDP, I highly recommend sticking to the simulator for now while I continue to build and refine features.

##  Key Features

*   **Multi-Drone Simulation**: Easily connect to and monitor multiple simulated drones.
*   **3D Visualization**: See your drones in real-time 3D, complete with terrain and mission paths.
*   **Mission Planning**: Drag-and-drop waypoints to create missions and upload them instantly.
*   **Real-Time Data**: Stream telemetry like battery, GPS, and attitude without the clutter.
*   **Cross-Platform**: Runs natively on **macOS** and **Windows**.

##  Downloads

Grab the latest build to try it out:

### **macOS (Apple Silicon & Intel)**
*   [Download Swarm Commander for Mac](https://github.com/KhaledS23/swarm_commander_public/blob/main/Swarm-Commander-macOS.zip)
    *   *Note: On first run, remember to Right-Click > Open to bypass Gatekeeper.*
    *   or run this script in terminal of the installer folder: xattr -d com.apple.quarantine "Swarm Commander-macos"

### **Windows (x64)**
*   [Download Swarm Commander for Windows](https://github.com/KhaledS23/swarm_commander_public/blob/main/Swarm-Commander-Windows.zip)

## Technology Stack

*   **Frontend**: Next.js, React, TailwindCSS, Three.js
*   **Backend**: Python, Flask, Pymavlink
*   **Communication**: WebSocket & UDP

##  Getting Started

1.  **Launch the App**: Double-click the executable. The backend server starts automatically.
2.  **Interface**: It opens in your browser at `http://localhost:5002`.
3.  **Connect**: read the documentaion to know how to connect simulations.

##  Join our Discord Channel
This is an early development tool, and we are expecting some things not to work right outside the box yet, 
but we would love to get your feedback, and the team will try to fix them quickly.

https://discord.com/channels/1473282227076075686/1473282227751354614

