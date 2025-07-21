# LeEco Le 2 (s2) - PostmarketOS Build

## Device Information

- **Device Name**: LeEco Le 2
- **Codename**: `s2`
- **SoC**: Qualcomm Snapdragon 652 (MSM8976)
- **Architecture**: `aarch64`
- **RAM**: 3 GB
- **Storage**: 32 GB (varies by model)
- **Display**: 5.5" 1080x1920 IPS

## Build Details

- **pmbootstrap Command**:
  ```sh
  pmbootstrap init
  # Choose:
  # - Vendor: leeco
  # - Device: s2

  pmbootstrap install --android-recovery-zip
  pmbootstrap export
