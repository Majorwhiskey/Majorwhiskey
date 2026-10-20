<h1 align="center">Hi, I'm Amogh Ukkadgatri 👋</h1>

<p align="center">
  <b>Electronics & Communication Engineer · Embedded systems · GNSS, RF & acoustic sensing for defence</b>
</p>

<p align="center">
  <a href="https://amoghukkadgatri.vercel.app"><img src="https://img.shields.io/badge/Portfolio-amoghukkadgatri.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <!-- Replace YOUR-LINKEDIN and YOUR-EMAIL below -->
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-Say%20hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### 🛰️ About me

I build small, low-cost hardware that watches the sky and listens to the world: GNSS loggers, LoRa trackers, microphone arrays and radar trackers. My work sits where PCB design, firmware and signal processing meet, mostly aimed at defence problems like counter-UAS and GNSS jamming and spoofing.

- 🔭 **Now:** building **GNSS-GUARD**, an on-device GPS jamming & spoofing detector
- 📐 **Recently:** designed **Theoros**, a 4-layer ESP32-S3 GPS + LoRa tracker in KiCad 10
- 🎙️ **Into:** acoustic C-UAS, direction-of-arrival estimation, state estimation, TinyML on microcontrollers
<!-- - 🎓 **Education:** B.E./B.Tech in ECE, [College], [Year] -->
<!-- - 💼 **Experience:** [Role] at [Organisation], [what you worked on] -->

---

### 🔧 Featured projects

| Project | What it does | Built with |
|---|---|---|
| [**GNSS-GUARD**](https://github.com/Majorwhiskey/GNSS-GUARD)<br>🚧 *data collection* | Low-cost GPS jamming & spoofing detector. A u-blox NEO-M8L with a built-in IMU streams UBX to an ESP32. A per-second feature pipeline (C/N0 vs elevation, clock jumps, GNSS heading vs gyro, AGC and jamming indicators) feeds a small int8 model that will run on the ESP32 itself. Receive-only by design. | ESP32 · u-blox UBX · Python · TinyML |
| [**Theoros** (gps-lora)](https://github.com/Majorwhiskey/gps-lora)<br>📐 *V1.0 design complete* | USB-C GPS logger and LoRa tracker. Logs 1 Hz u-blox M10 fixes to microSD, shows status on an OLED, and sends AES-128-CCM encrypted position over sub-GHz LoRa. WiFi handles NTP, log download and OTA. 4-layer, fully machine-assembled board with fab outputs and tracker/receiver firmware. Named after the Greek *theoros*, an observer sent to watch and report back. | ESP32-S3 · KiCad 10 · RFM95W (SX1276) · Arduino |
| [**Radar Tracking & Classification**](https://github.com/Majorwhiskey/Real-time-3D-radar-tracking-and-classification-system) | Tracks simulated radar targets through noisy measurements with Kalman and particle filters, classifies their motion with SVMs, and plots true, noisy and estimated trajectories live. | Python · Kalman & particle filters · SVM |
| [**3D Acoustic Localization**](https://github.com/Majorwhiskey/3-d-Acoustic-Localization-using-Microphone-array-and-AI-) | Sound-source localization with a microphone array on a Raspberry Pi: filtering, DOA estimation, triangulation and visualization. | Python · Jupyter · Raspberry Pi · ReSpeaker |
| [**Portfolio**](https://github.com/Majorwhiskey/Portfolio) | Single static page with hand-coded canvas animations: a self-routing circuit in the hero and a dot field that spells words as you scroll. No framework, no build step. | HTML · CSS · JavaScript · Canvas · Vercel |
| [**Aroodha Foundation**](https://github.com/Majorwhiskey/Aroodha-Foundation) | Multi-page website for a foundation covering programs, events, online sessions and donations. | HTML · Tailwind CSS |

---

### 🧰 Toolbox

**Hardware & RF**

![ESP32-S3](https://img.shields.io/badge/ESP32--S3-E7352C?style=flat-square&logo=espressif&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad%2010-314CB0?style=flat-square&logo=kicad&logoColor=white)
![LoRa](https://img.shields.io/badge/LoRa-SX1276-1C75BC?style=flat-square)
![u-blox](https://img.shields.io/badge/u--blox-GNSS%20%2F%20UBX-A41E35?style=flat-square)
![PCB](https://img.shields.io/badge/PCB-4--layer%20%C2%B7%20impedance%20controlled-2E7D32?style=flat-square)

**Languages & tools**

<img src="https://skillicons.dev/icons?i=python,cpp,arduino,raspberrypi,linux,git,html,css,js,tailwind,vercel" alt="Tech stack" />

**Signal processing & ML**

Kalman & particle filters · DOA estimation · feature engineering on GNSS data · SVMs · gradient-boosted trees · autoencoders · int8 on-device inference

---

<p align="center">
  <i>If you work on GNSS integrity, counter-UAS or embedded RF, I'd love to talk.</i>
</p>
