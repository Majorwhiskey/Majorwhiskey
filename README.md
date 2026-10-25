![Amogh Ukkadgatri. Embedded hardware and RF engineer, Bengaluru.](https://github.com/Majorwhiskey/Majorwhiskey/raw/main/assets/header.svg)

[Portfolio](https://amoghukkadgatri.vercel.app)  ·  [LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN)  ·  amoghukkadgatri@gmail.com

## Now

**Hardware Engineer, SSS Defence.** Acoustic counter-UAS. I own the sensing hardware, from microphone arrays and capture firmware to the rigs that qualify them. I'm also on the team syncing packets, data and clocks across multiple arrays so their captures line up for joint processing. *Work is private.*

**Building [GNSS-GUARD](https://github.com/Majorwhiskey/GNSS-GUARD).** A low-cost GPS jamming and spoofing detector. I'm collecting data now. Next is a small int8 model that runs on the ESP32 itself.

**Finished [Theoros](https://github.com/Majorwhiskey/gps-lora).** An encrypted GPS logger and LoRa tracker. The V1.0 board and firmware are done and ready for fabrication.

## Work

**GNSS and RF**

- [**GNSS-GUARD**](https://github.com/Majorwhiskey/GNSS-GUARD): a u-blox NEO-M8L and an ESP32 that check every second for jamming and spoofing. They compare signal strength with satellite elevation, watch for clock jumps, and compare GNSS heading with the gyro. Receive-only by design.
- [**Theoros**](https://github.com/Majorwhiskey/gps-lora): a 4-layer ESP32-S3 board that logs GPS fixes to microSD and sends position over LoRa, encrypted with AES-128-CCM. Designed in KiCad for machine assembly.

**Acoustic sensing**

- [**3D Acoustic Localization**](https://github.com/Majorwhiskey/3-d-Acoustic-Localization-using-Microphone-array-and-AI-): finds where a sound comes from in 3D with a mic array on a Raspberry Pi, using DOA estimation and triangulation. My final-year project, and how I got into C-UAS.
- **Mic-array test rig**: qualifies custom microphone arrays over ESP32 I2S. It moves to TDM capture to get past the classic ESP32's single-RX-channel limit. *· at SSS Defence, private*

**Tracking and estimation**

- [**Radar Tracking & Classification**](https://github.com/Majorwhiskey/Real-time-3D-radar-tracking-and-classification-system): follows simulated radar targets through noisy measurements with Kalman and particle filters, classifies their motion with SVMs, and plots the tracks live.

## Also built

[Portfolio](https://github.com/Majorwhiskey/Portfolio), one static page with hand-coded canvas animations and no framework · [Aroodha Foundation](https://github.com/Majorwhiskey/Aroodha-Foundation), a website for a foundation's programs, events and donations

## Background

B.E., Electronics & Communication, KLE Institute of Technology, 2026 · Chair, KLEIT–IEEE MTT-S Chapter, 2024–25 · Vice-Chair, KLEIT–IEEE Student Branch, 2023–24 · theatre with the university cultural group

## Tools

C · C++ · Python · MATLAB · ESP32 / ESP32-S3 · Raspberry Pi · KiCad · LoRa · u-blox UBX · I2S / PDM / TDM audio · Kalman and particle filters · DOA estimation · TinyML · Linux

*If you work on GNSS integrity, counter-UAS or embedded RF, I'd love to talk.*
