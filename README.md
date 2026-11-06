# LiDAR Bridge (LEOXI-LIDARTRACKING)

LiDAR Bridge turns a 2D LiDAR sensor into touch and people-tracking data for interactive walls, floors and immersive rooms. It reads RPLIDAR and Hokuyo UST sensors, cleans and tracks the points, maps them onto each projection surface, and sends the result to TouchDesigner and other software over OSC, with a calibration view over NDI or Syphon.

## Download

Go to **[Releases](../../releases/latest)** and download the file for your computer:

| System | File |
|---|---|
| macOS (Apple Silicon) | `LEOXI-LIDARTRACKING-<version>-arm64.dmg` |
| Windows 10/11 (64-bit), installer | `LEOXI-LIDARTRACKING-Setup-<version>-x64.exe` |
| Windows 10/11 (64-bit), no install | `LEOXI-LIDARTRACKING-Portable-<version>-x64.exe` |

## First launch

The app is not code-signed yet, so the system will warn you the first time:

- **macOS:** open the `.dmg`, drag the app to Applications, then right-click the app and choose **Open**.
- **Windows:** when SmartScreen appears, click **More info**, then **Run anyway**.

## Supported sensors

- Slamtec RPLIDAR (USB serial)
- Hokuyo UST series (Ethernet)
- A built-in simulation mode for working without a sensor

## Questions and bug reports

Open an issue in this repository and include your system, sensor model, app version and a screenshot.

## License

The application is free to download and use. The source code is not public. See [LICENSE](LICENSE) for the terms.

NDI® is a registered trademark of Vizrt NDI AB. This application includes the NDI runtime, used under the NDI license terms.
