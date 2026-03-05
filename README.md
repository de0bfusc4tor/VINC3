# Vinc3 — Pro DSP Analysis 🔊📊

> Audio Visual Analysis for Music Production.

![macOS Support](https://img.shields.io/badge/macOS-Sonoma_|_Sequoia_|_Tahoe-000000?style=for-the-badge&logo=apple&logoColor=white)
![M4L Support](https://img.shields.io/badge/Ableton-Live_11_|_12-ff5500?style=for-the-badge&logo=ableton&logoColor=white)

**Vinc3** is an high-fidelity audio analysis workstation engineered for professionals who demand precision, performance, and aesthetic clarity. Designed as a **Native Offline Application**, it leverages a 64-bit floating-point DSP core to provide real-time telemetry of complex audio signals without any external dependencies or latency-inducing server processing.

---

<img width="1439" height="685" alt="Vinc3demo2" src="https://github.com/user-attachments/assets/fce47b5b-dedd-4e68-b78d-c669a758fe11" />

---

## 🛰 Core Analysis Modules

### 1. Spectrum_V (Frequency Precision)
A surgical FFT analyzer using a pixel-exact inverse-logarithmic frequency sweep.
*   **Gapless Trace**: Perfectly continuous graph from 20Hz to 20kHz.
*   **Fundamental Tracker**: Real-time HUD showing the dominant frequency with musical note/octave detection.
*   **Dual-View Engine**: Switch between high-density FFT curves and 64-band bar visualization.

### 2. Spectrogram_V (Temporal History)
Visualizes spectral evolution over time in a 3D space.
*   **Ridge Mode**: Classical overlapping spectral ridges with time-decay luminosity.
*   **Colors**: Cyan, purple, green and red.

### 3. FFT Meter (Tactical Tracking)
Designed for identifying resonant peaks with military precision.
*   **Laser Crosshair**: Automatically locks onto the highest energy peak.
*   **Telemetry HUD**: Provides instantaneous Hz and dB readouts with high-contrast razor outlines.

### 4. Master Guard (Loudness Standards)
EBU R128 compliant loudness metering for professional mastering workflows.
*   **LUFS Triad**: Integrated, Short-term, and Momentary measurements.
*   **Limit Safe**: Visual guard system ensuring your levels stay within digital delivery specifications.

### 5. Oscilloscope (Waveform Integrity)
A high-energy time-domain visualizer mimicking the look of vintage hardware.
*   **Electron Beam**: Employs a multi-pass rendering engine for "white-hot" core traces and soft bloom effects.
*   **Dynamic Trigger**: Intelligent zero-crossing alignment for stable waveform viewing.

### 6. Stereo Meter (Spatial Imagery)
*   **Vectorscope (Goniometer)**: High-refresh Lissajous plotter for stereo field analysis.
*   **Stereo Spectral Dist**: A 2D spectral cloud mapping frequency against pan position.
*   **Correlation Meter**: Real-time phase coherency monitoring from -1.0 to +1.0.

### 7. Chromatic Wave (Frequency-Amplitude Sync)
A scrolling amplitude history where the color of each segment represents the dominant frequency at that moment.
*   **HSLA Mapping**: Lower frequencies shift toward purple/blue; higher frequencies toward pink/white.
*   **Colors**: Cyan, purple, green and red.
  
### 8. Peak Amp (Headroom Telemetry)
*   **Digital Margin**: Tracks the exact distance between your signal and 0dBFS.
*   **Peak Hold**: A high-persistence "ghost" line that preserves the highest digital peak until manual reset.

### 9. Spectrogram Heatmap (Density Mapping)
A vertical-scroll heatmap providing a top-down view of spectral density.
*   **Thermal Gradient**: Uses a custom color palette (Black -> Cyan -> White) to represent intensity.

### 10. Stereo Spectral
A spectral waveform.

---

## ⚙️ Technical Specifications

*   **DSP Buffer**: 8192-point FFT with 64-bit internal precision.
*   **Visual Engine**: Optimized HTML5 Canvas 2D with `requestAnimationFrame` for 120 FPS compatibility.
*   **Latency**: Interactive-priority AudioContext with ultra-low buffer overhead.
*   **Security**: 100% Offline. No data ever leaves your local machine.

## 💻 System Compatibility

Built and tested for the modern macOS ecosystem:
*   **macOS Sonoma (14.x)**
*   **macOS Sequoia (15.x)**
*   **macOS Tahoe (16.x)**

---

## 🛠 Operation Manual

1.  **Boot Sequence**: Click the circular **Power Node** in the top header to initialize the DSP engine.
2.  **Telemetry Source**: Select **[MIC]** for direct input or **[SCR]** to capture system audio via Screen Capture.
3.  **Modular Workspace**: 
    *   **Drag & Drop**: Click headers to reorganize windows.
    *   **Tactile Scaling**: Use the bottom-right corner handles to resize any analyzer.
    *   **Layer Focus**: Clicking any module brings it to the immediate foreground.

---

## 🧪 𝐂𝐫𝐞𝐝𝐢𝐭𝐬

- Sponsor / Benefactor : Vincent P.
- Development / Creation : [Deobfuscate](https://github.com/de0bfusc4tor)

---
