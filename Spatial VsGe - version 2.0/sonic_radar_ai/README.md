# Spatial VsGe V2.o

A real-time AI-based directional sound detection and visual radar system using HRTF, Superfastline, VQ-VAE, Transformers, and G-sync compatible audio-visual processing pipelines.

## Features

- RTX GPU acceleration for real-time processing
- AI-enhanced directional sound detection
- Visual radar system with object tracking
- HRTF and Superfastline spectral estimation
- VQ-VAE and Transformer-based processing

## Installation

```bash
# Install the package
sudo dpkg -i sonic-radar-rtx-compatible.deb

# Run the installation script for dependencies
cd /usr/local/bin/
sudo ./install.sh

# Run the application
python3 sonic_radar.py
```

## Requirements

- Python 3
- NVIDIA RTX GPU
- CUDA Toolkit
- OpenCV
- PulseAudio

## Building the Package

From the root directory (sonic_radar_ai):

```bash
dpkg-deb --build sonic_radar_ai
mv sonic_radar_ai.deb sonic-radar-rtx-compatible.deb
```
