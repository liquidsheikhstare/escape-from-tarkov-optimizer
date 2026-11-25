# Changelog

All notable changes to Tarkov FPS Optimizer are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [1.0.0] — November 2026

### Added

- Low / Medium / High graphics presets that write every relevant graphics setting for the target GPU.
- Stutter fix module tuning frame limits, V-sync and CPU affinity to reduce frame drops and input lag.
- Shader and DirectX cache cleanup to remove the stutter caused by stale cache on map load.
- Timestamped config backups with one-click restore.
- Per-raid session FPS log recording average FPS and 1% lows.
- Fully portable, offline operation with no account, no telemetry and no background process.

### Notes

- Native C++ build, 6 MB, no runtime dependencies.
- Windows 10 and Windows 11, 64-bit.
