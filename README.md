# RTVCMv2

**RTVCMv2** is a real-time WebGPU application for volumetric rendering
and simulation of cellular cytosol data.

It visualizes 3D uint8 volume datasets (e.g. 256×256×256 RAW files) using
GPU-accelerated projection and simulates cytosolic motion through custom
WGSL shaders — all with live, interactive parameter editing.

## Features

- 🚀 WebGPU-based volume rendering
- 🧬 3D cytosol simulation via WGSL shaders
- 🧊 Supports uint8 RAW volumetric datasets
- 🎛 Real-time parameter editing (opacity, threshold, time, slicing)
- 📈 FPS monitoring and camera controls

## Tech Stack

- **WebGPU**
- **TypeScript**
- **WGSL**
- **gl-matrix**
- **Vite** (depending on version)

## Getting Started

```bash
npm install
npm run dev
