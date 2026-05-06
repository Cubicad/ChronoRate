# ChronoRate

ChronoRate is a time tracking add-in for Autodesk Fusion that helps designers 
and engineers measure **active** working time on each project and calculate an 
estimated billing rate.

---

## Features

- Tracks active working time per session; automatically starts and pauses based on the last recorded command 
- Works across multiple opened tabs
- Configurable session time frame 
- Configurable session accounting
- Configurable hourly-rate
- Session List table / viewer with copy fuction
- Data retention

---

## Installation

1. Download the latest version from the
   [Releases](https://github.com/Cubicad/ChronoRate/releases) page
2. Extract the `ChronoRate` folder from the ZIP file
3. Move the `ChronoRate` folder to the Fusion add-ins directory:

   - **Windows:**
     `%appdata%\Autodesk\Autodesk Fusion 360\API\AddIns\`
   - **macOS:**
     `~/Library/Application Support/Autodesk/Autodesk Fusion 360/API/AddIns/`

   > ⚠️ **Note:** verify these paths on your system - they may vary depending
   > on your Fusion version.

4. Open Fusion, go to **Utilities → Add-ins → Scripts and Add-ins**
5. Under the **Add-ins** tab, find **ChronoRate** and click **Run**
6. To load automatically at startup, check **Run on Startup**

---

## Usage

Once the add-in is launched, simply save the document with a name, and ChronoRate will automatically start tracking the session from that point on.
No further action is required.

### Gallery

<p align="center">
  <img src="assets/screenshots/screenshot1.png" width="48%" alt="Main panel">
  <img src="assets/screenshots/screenshot2.png" width="48%" alt="Settings panel">
</p>
<p align="center">
  <img src="assets/screenshots/screenshot3.png" width="48%" alt="Save file to start session tracking">
  <img src="assets/screenshots/screenshot4.png" width="48%" alt="Name of the file is displayed in Project section">
</p>
<p align="center">
  <img src="assets/screenshots/screenshot5.png" width="48%" alt="Tracking begins when the first command is detected and pause if no commands are detected within the selected time frame">
  <img src="assets/screenshots/screenshot6.png" width="48%" alt="Save to store session data">
</p>
<p align="center">
  <img src="assets/screenshots/screenshot7.png" width="48%" alt="You can access the list of sessions by clicking on the session list icon">
  <img src="assets/screenshots/screenshot8.png" width="48%" alt="Session list panel">
</p>

---

## Support the Project

If you find ChronoRate useful, consider buying me a coffee!

[![Buy Me a Coffee](https://img.buymeacoffee.com/button-api/?text=Buy+me+a+coffee&emoji=&slug=cubicad&button_colour=FFDD00&font_colour=000000&font_family=Poppins&outline_colour=000000&coffee_colour=ffffff)](https://www.buymeacoffee.com/cubicad)

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for the full version history.

---

## Privacy Policy

See [PRIVACY_POLICY.md](PRIVACY_POLICY.md).

---

## Disclaimer

See [DISCLAIMER.md](DISCLAIMER.md).

---

## License

This project is licensed under the
[PolyForm Noncommercial License 1.0.0](LICENSE).  
Commercial use and redistribution are not permitted.
