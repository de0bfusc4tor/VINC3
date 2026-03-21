# 𝐕𝐢𝐧𝐜𝟑 - 𝐃𝐒𝐏 𝐀𝐮𝐝𝐢𝐨 𝐀𝐧𝐚𝐥𝐲𝐳𝐞𝐫

> _3D Spectral Analysis & DSP Metering Suite. Designed for engineers, producers, and sound designers to provide immersive 3D frequency visualization and precision audio monitoring in a minimalist interface._

![Version](https://img.shields.io/badge/Version-0.9.9-green?style=flat-square)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Universal%20Silicon%20%26%20Intel-black?labelColor=606060&style=flat-square&logo=apple&logoColor=white)
![Format](https://img.shields.io/badge/Format-Standalone-00CED1?style=flat-square)

---

<img width="1440" height="867" alt="VINC3preview" src="https://github.com/user-attachments/assets/ae730ef0-b0cc-46e0-b2be-096d384e89b3" />

---

## 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

###  𝟑𝐃 𝐒𝐩𝐞𝐜𝐭𝐫𝐨𝐠𝐫𝐚𝐦 𝐄𝐧𝐠𝐢𝐧𝐞
Three-dimensional view of your audio's spectral energy.
- **Three Modes**: **Sphere** (radial energy core), **Wave** (terrain landscape), and **Cube** (geometric structure).
- **Dynamic Physics**: Features a 50% increased spike multiplier for highly responsive, energetic animations that react to overall loudness.

###  𝐅𝐅𝐓 𝐌𝐞𝐭𝐞𝐫 (𝐏𝐫𝐞𝐜𝐢𝐬𝐢𝐨𝐧 𝐅𝐫𝐞𝐪𝐮𝐞𝐧𝐜𝐲)
High-resolution Fast Fourier Transform analyzer for surgical frequency monitoring.
- **Peak Tracking**: Automatic peak detection and labeling of the most prominent frequencies.
- **Musical Note ID**: Translates raw frequencies into musical notes (e.g., A4, C#2) for tuning and harmonic analysis.
- **Logarithmic Scaling**: Detailed response from 20Hz to 20kHz with high-DPI grid rendering.

###  𝐋𝐞𝐯𝐞𝐥 𝐌𝐞𝐭𝐞𝐫𝐬 (𝐋𝐨𝐮𝐝𝐧𝐞𝐬𝐬 & 𝐃𝐲𝐧𝐚𝐦𝐢𝐜𝐬)
Industry-standard monitoring to ensure loudness compliance.
- **LUFS Monitoring**: Real-time tracking of Momentary (M), Short-term (S), and Integrated (I) LUFS.
- **Peak & RMS**: Accurate dBFS monitoring with persistent "Max Peak" hold.
- **Crest Factor**: Visualizes the peak-to-RMS ratio; indicators turn **Vibrant Red** when audio is heavily limited (< 6dB) or exceeding safety thresholds (-3dB).

###  𝐀𝐧𝐚𝐥𝐨𝐠 𝐕𝐔 𝐌𝐞𝐭𝐞𝐫 (𝐏𝐞𝐫𝐜𝐞𝐢𝐯𝐞𝐝 𝐖𝐞𝐢𝐠𝐡𝐭)
Classic hardware-inspired ballistic response for monitoring signal "weight".
- **Ballistics**: Standard 300ms integration time mimics physical studio gear.
- **Hot Zone**: Ticks and needles turn red above 0dB to signal saturation levels.

###  𝐎𝐬𝐜𝐢𝐥𝐥𝐨𝐬𝐜𝐨𝐩𝐞
- **Time Domain**: Real-time linear oscilloscope visualization.
- **Left & Right**: Monitor stereo image.

###  𝐒𝐭𝐞𝐫𝐞𝐨 𝐌𝐨𝐧𝐢𝐭𝐨𝐫
- **Triggering**. Stable **Zero-Crossing Trigger**.
- **Phase & Width**: Monitor stereo image, phase correlation and the balance between Mid/Side information to ensure mono compatibility.

###  𝐋𝐢𝐧𝐞𝐚𝐫 𝐒𝐩𝐞𝐜𝐭𝐫𝐨𝐠𝐫𝐚𝐦 (𝐒𝐩𝐞𝐜𝐭𝐫𝐚𝐥 𝐇𝐞𝐚𝐭𝐦𝐚𝐩)
A scrolling logarithmic history of frequency energy flowing from **Left to Right**.
- **History**: Identify long-term resonances and spectral imbalances over a continuous timeline.
- **Teal Gradient**: Optimized for clarity, removing clutters for a pure data-driven look.
---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: 14.0 (Sonoma), 15.0 (Sequoia), or 16.0 (Tahoe).
- **Architecture**: Intel & Apple Silicon (Universal).
- **Permissions**: Requires Microphone (for hardware input) and Screen Recording (for system audio loopback).

---

## 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

### 𝐒𝐭𝐚𝐧𝐝𝐚𝐥𝐨𝐧𝐞
1. Download the latest `VINC3.app.zip`.
2. Extract & Drag to your `Applications` folder.
3. **Note**: Follow the macOS Permissions tutorial below for first-time setup.

---

## 𝐦𝐚𝐜𝐎𝐒 𝐏𝐞𝐫𝐦𝐢𝐬𝐬𝐢𝐨𝐧𝐬

To function as a standalone analyzer. `VINC3` requires specific system access. Make sure to fill these requirements before starting using :

### 𝟏. 𝐌𝐢𝐜𝐫𝐨𝐩𝐡𝐨𝐧𝐞 𝐀𝐜𝐜𝐞𝐬𝐬
Required to analyze audio from your interface or built-in mic.
- `System Settings` > `Privacy & Security` > `Microphone` > Enable `VINC3`.

### 𝟐. 𝐒𝐜𝐫𝐞𝐞𝐧 𝐑𝐞𝐜𝐨𝐫𝐝𝐢𝐧𝐠
Required for **System Audio Loopback** (capturing audio from other apps).
- `System Settings` > `Privacy & Security` > `Screen Recording` > Enable `VINC3`.
- _Note: `VINC3` does not record pixels; this is a macOS requirement for internal audio routing._

---

## 𝐂𝐨𝐧𝐭𝐫𝐨𝐥𝐬

- **Resizable & Mobile Software**
- **Resizable & Mobile Modules**

---

## 𝐂𝐫𝐞𝐝𝐢𝐭𝐬

- **Sponsor/Benefactor**: Vincent P.

---

_This software is free. Don't forget to give it a ⭐ on Github if you liked the project._

---

<p align="center"><code>𝕯𝖊𝖔𝖇𝖋𝖚𝖘𝖈𝖆𝖙𝖊</code></p>
<p align="center">2026</p>
