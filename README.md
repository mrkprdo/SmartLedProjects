# SmartLED

Custom LED lighting projects powered by [WLED](https://kno.wled.ge/) and controlled with the [Kolori mobile app](https://kolori.wasmer.app/).

## Projects

<div align="center">

|                                  Starlight                                   |                            Starlite                             |
| :--------------------------------------------------------------------------: | :-------------------------------------------------------------: |
|          <img src="images/starlight.gif" width="200" height="200"/>          |    <img src="images/starlite.gif" width="200" height="200"/>    |
| 90cm LED strip light with 128 WS2815 LEDs<br/>in an 8x8 matrix configuration | Compact "Cheesecake Light"<br/>with custom 3D-printed enclosure |

### Controller

<img src="images/controller.jpg" width="200"/>

</div>

## Features

- **Custom Effects** - Create unique lighting patterns
- **Audio Reactive** - Sync lights to music
- **Boot Presets** - Auto-load effects on power-up
- **Multi-Device** - Control multiple lights from one app
- **Offline & Free** - No internet or login required

## Quick Start

### 1. Flash WLED Firmware

- Use the [WLED web installer](https://install.wled.me/)
- For Starlight: Upload configs from `starlight/wled_backup/`

### 2. Install Kolori App

- [Google Play Store](https://play.google.com/store/apps/details?id=com.mrkprdo.kolori)
- [Apple App Store](https://apps.apple.com/app/kolori)

### 3. Connect Device

**Starlight:**

- Connect device to your WiFi
- Open Kolori → Scan Network or add manually

**Starlite:**

- Connect to "starlite" WiFi (password: `starlite4321`)
- Add device in Kolori using IP: `4.3.2.1`

## 3D Models

**Starlight**: Parts and assembly files in `starlight/3d_model/`
**Starlite**: Print-ready files in `starlite/3d_model/`

## Documentation

- [Kolori User Guide](https://kolori.wasmer.app/kolori-user-guide.html)
- [Starlite Quick Start](https://kolori.wasmer.app/starlite-quick-start.html)
- [WLED Docs](https://kno.wled.ge/)

## Links

- [Kolori GitHub](https://github.com/mrkprdo/kolori)
- [WLED GitHub](https://github.com/Aircoookie/WLED)
