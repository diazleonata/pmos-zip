# LeEco Le 2 (s2) - PostmarketOS Build

## Device Information

- **Device Name**: LeEco Le 2
- **Codename**: `s2`
- **SoC**: Qualcomm Snapdragon 652 (MSM8976)
- **Architecture**: `aarch64`
- **RAM**: 3 GB
- **Storage**: 32 GB (varies by model)
- **Display**: 5.5" 1080x1920 IPS

## Desktop Environment

- **Profile**: `sxmo-de-dwm`
- **Type**: Minimal tiling window manager (DWM-based)
- **Target**: Lightweight, keyboard/touch-driven interface

## Build Details

- **pmbootstrap Command**:
  ```sh
  pmbootstrap init
  # Choose:
  # - Vendor: leeco
  # - Device: s2
  # - UI: sxmo-de-dwm

  pmbootstrap install
  pmbootstrap export
