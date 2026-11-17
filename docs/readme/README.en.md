<div align="center">

# TASL Voice

**Turn scripts into voice audio, subtitles and video, on your own Windows PC.**

[![Download latest](https://img.shields.io/badge/Download-Latest%20release-0b6bcb?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/anhql77/tasl-voice-ban-phat-hanh/releases/latest)
[![Tiếng Việt](https://img.shields.io/badge/Ti%E1%BA%BFng%20Vi%E1%BB%87t-README-555?style=for-the-badge)](../../README.md)

Latest version: **1.3.3** (17 Nov 2026) — adds **Auto Edit**

</div>

---

TASL Voice is the voice-production module of the TA Studio Loop (TASL) system, built for long-form storytelling workflows. The interface is in Vietnamese.

## What it does

- Converts scripts into **MP3 + SRT** output
- Reusable **voice library** and **multi-character voice assignment**
- Queue, stop, resume and reprocess workflows
- Quality-review signals for generated speech
- Local **NVIDIA** hardware acceleration
- Update checks and a rollback path

## Coming in 1.3.3 (not yet released)

- **Auto Edit**: load several scripts at once and get videos (MP4 and/or CapCut draft). One failing video does not stop the others.
- Faster speech generation (on RTX 30-series cards and newer), audio processing and video assembly.
- More consistent pictures: a reference image per character, made first; each script has a **Key** that sets the world, colours and lighting of its pictures.
- Per-scene image review and re-render of only the affected 10-minute segment.
- If G-Labs Studio is not installed, the app shows a **«Tải G-Labs Studio»** (download) button.

See the [1.3.3 release notes](../phat-hanh/v1.3.3.md) and [what to do on each PC when moving to 1.3.3](../huong-dan/06-len-ban-1.3.3.md) (both Vietnamese).

## System requirements

- Windows 10 or Windows 11, 64-bit
- NVIDIA GPU recommended (the fast speech mode of 1.3.3 needs an RTX 30-series card or newer)
- 8 GB+ GPU memory recommended
- 15 GB+ free disk space recommended (Auto Edit needs roughly 10 GB more per video; an estimate, not yet measured)
- Internet connection during installation

## Install

Download the installer from [Releases](https://github.com/anhql77/tasl-voice-ban-phat-hanh/releases/latest), run it, and follow the on-screen steps. Guide (Vietnamese): [01 - Installation](../huong-dan/01-cai-dat.md).

## More

Website: https://tastudioloop.com · Core product releases: https://github.com/anhql77/TA-Studio-Loop

> The proprietary TASL Voice source code is maintained privately. This public repository is used for release distribution and documentation.
