# LocalAssist

A lightweight, offline-first text utility built for the **AI Yako Hackathon (Offline AI Apps Track)**. LocalAssist performs local text processing and inference using Tether's QVAC local AI stack without requiring an active internet connection.

## Features
- **Fully Offline Execution:** Core AI operations run entirely on-device with zero internet dependency.
- **Local Text Summarization:** Rapidly process notes, logs, and documents locally.
- **Privacy-First Architecture:** Zero telemetry leakage; all data stays on the host device.

## Tech Stack
- **AI Core:** QVAC Local AI Stack
- **Target Hardware:** Samsung Galaxy Book4 Edge (Windows 11, 16GB RAM)
- **Model:** Llama 3.2 1B (Local)

## Setup & Offline Execution Instructions
1. Clone this repository locally.
2. Install necessary dependencies and download the local model weights before testing.
3. Toggle off all network interfaces and Wi-Fi to verify offline capability.
4. Execute the local script or utility binary to run inference and view outputs.
## Network Features
* Live external model API calls and inference execution routed through high-throughput endpoints.
* Multi-agent workflow synchronization and live webhook event triggering.
