# Vinc3 - Pro DSP Analysis

> _Precision Audio Visual Analysis for music production. Designed as a **Native Offline Application**, it leverages a 64-bit floating-point DSP core to provide real-time telemetry of complex audio signals without any external dependencies or latency-inducing server processing._

![Under Development](https://img.shields.io/badge/Status-Under%20Development-orange)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Universal%20(Silicon%20%26%20Intel)-606060?style=flat-square)
![Format](https://img.shields.io/badge/Format-Standalone-00CED1?style=flat-square)

---

<img width="1439" height="685" alt="Vinc3demo2" src="https://github.com/user-attachments/assets/fce47b5b-dedd-4e68-b78d-c669a758fe11" />

---

## 𝐂𝐨𝐫𝐞 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 𝐌𝐨𝐝𝐮𝐥𝐞𝐬

- **Spectrum_V**: Surgical FFT analyzer using pixel-exact inverse-logarithmic frequency sweeps. Includes a Fundamental Tracker HUD.
- **Spectrogram_V**: Visualizes spectral evolution in 3D space with "Ridge Mode" overlapping ridges and time-decay luminosity.
- **FFT Meter**: Tactical tracking with a Laser Crosshair that automatically locks onto the highest energy peaks.
- **Master Guard**: EBU R128 compliant loudness metering (LUFS Integrated, Short-term, and Momentary).
- **Oscilloscope**: High-energy time-domain visualizer with a multi-pass "white-hot" electron beam rendering engine.
- **Stereo Meter**: Features a high-refresh Goniometer, Stereo Spectral Distribution, and Real-time Phase Correlation.
- **Chromatic Wave**: Scrolling amplitude history with HSLA Mapping (Freq-to-Color synchronization).
- **Peak Amp**: Digital margin telemetry tracking exact distance to 0dBFS with high-persistence Peak Hold.
- **Spectrogram Heatmap**: Vertical-scroll density mapping using a custom Thermal Gradient palette.

---

## 𝐓𝐞𝐜𝐡𝐧𝐢𝐜𝐚𝐥 𝐒𝐩𝐞𝐜𝐢𝐟𝐢𝐜𝐚𝐭𝐢𝐨𝐧𝐬

- **DSP Core**: 8192-point FFT with 64-bit internal floating-point precision.
- **Visual Engine**: Optimized HTML5 Canvas 2D with `requestAnimationFrame` for 120 FPS compatibility.
- **Latency**: Interactive-priority AudioContext with ultra-low buffer overhead.
- **Security**: 100% Offline. Zero telemetry. No data ever leaves your local machine.

---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: 14.0 (Sonoma), 15.0 (Sequoia), or 16.0 (Tahoe).
- **Architecture**: Intel & Apple Silicon (Universal).
- **DAW**: Ableton Live 11 & 12 (via Screen Capture/System Audio).

---

## 𝐎𝐩𝐞𝐫𝐚𝐭𝐢𝐨𝐧 𝐌𝐚𝐧𝐮𝐚𝐥

1. **Boot Sequence**: Click the circular **Power Node** in the top header to initialize the DSP engine.
2. **Telemetry Source**: Select **[MIC]** for direct input or **[SCR]** to capture system audio via Screen Capture.
3. **Modular Workspace**:
    - **Drag & Drop**: Click headers to reorganize windows.
    - **Tactile Scaling**: Use bottom-right handles to resize any analyzer.
    - **Layer Focus**: Click any module to bring it to the foreground.

---

## 𝐂𝐫𝐞𝐝𝐢𝐭𝐬

- **Sponsor / Benefactor**: Vincent P.

---

<p align="center"><code>𝕯𝖊𝖔𝖇𝖋𝖚𝖘𝖈𝖆𝖙𝖊</code></p>
<p align="center">2026</p>
