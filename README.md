# Spotify Display

A compact physical display that shows the currently playing song from Spotify in real-time. This project connects to the Spotify API to pull live track data and render it on a small external screen.

> **Note:** This project is part of the Stasis Spotify Display starter project. It is currently in the prototype phase, source: https://stasis.hackclub.com/starter-projects/spotify-display

---

## Project Overview
The goal is to create a dedicated hardware device that monitors your Spotify activity. The display provides:
* **Song Title** & **Artist Name**
* **Playback Status** (Playing/Paused)
* **Album Artwork** (Planned feature)

---

## Repository Structure
The project is organized into two main categories:

| Folder | Description |
| :--- | :--- |
| `cad/` | 3D design files for the device enclosure (`.step`, `.stl`). |
| `code/` | Firmware and source code for the Arduino/ESP32 hardware. |

---

## Hardware & Design
### 3D Design
The enclosure is designed to be compact and functional. You can find the files in the `cad/` folder:
* **STEP file:** For use in CAD software like Fusion 360.
* **STL file:** Ready for 3D printing.

### Prototyping
I am currently using a cardboard prototype to test the physical layout and component fit before moving to a final 3D-printed version.
