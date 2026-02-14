# Swarm Commander

**Swarm Commander** is a next-generation Ground Control Station (GCS) designed specifically for managing and simulating multi-drone swarms. Bridging the gap between complex ArduPilot SITL simulations and user-friendly control, it provides a powerful, modern interface for drone fleet operations.

## 🚀 Key Features

*   **Multi-Drone Swarm Control**: Seamlessly connect to, monitor, and command multiple drones simultaneously.
*   **Immersive 3D Visualization**: Real-time 3D rendering of drone attitudes, terrain, and mission paths.
*   **Advanced Mission Planning**: Drag-and-drop mission creation with waypoint visualization and direct upload to ArduPilot.
*   **Real-Time Telemetry**: High-frequency data streaming for attitude, position, battery status, and GPS health via MAVLink.
*   **Zero-Setup Simulation**: Built to integrate instantly with ArduPilot SITL for safe, hardware-free testing.
*   **Cross-Platform**: Native standalone applications for **macOS** and **Windows**.

## 🛠️ Technology Stack

*   **Frontend**: Next.js, React, TailwindCSS, Three.js (Fiber/Drei)
*   **Backend**: Python, Flask, Socket.IO, Pymavlink, PyInstaller
*   **Communication**: WebSocket-based real-time telemetry bridge

## 📥 Downloads

*Please find the latest build artifacts below:*

### **macOS (Apple Silicon & Intel)**
*   [Download Swarm Commander for Mac](#) *(Add link here)*
    *   *Note: On first run, Right-Click > Open to bypass Gatekeeper.*

### **Windows (x64)**
*   [Download Swarm Commander for Windows](#) *(Add link here)*

## 🚦 Getting Started

1.  **Launch the App**: Double-click the executable. The backend server will start automatically.
2.  **Interface**: The dashboard will open in your default web browser (default: `http://localhost:5002`).
3.  **Connect**: Ensure your SITL instances are running. The Swarm Commander will automatically detect and list available drones.
