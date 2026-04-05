Spotify Display

A small physical display that shows the currently playing song from Spotify. The project connects to the Spotify API and displays song information on a small screen.

This project is part of the Stasis Spotify Display starter project, and will later be expanded with additional features once the core functionality works.

Project Overview

The goal of this project is to create a physical device that displays the currently playing Spotify track in real time. The display will show information such as:

Song title
Artist
Album artwork (optional later feature)
Playback status

The device will connect to the Spotify API and update automatically as the music changes.

Repository Structure
spotify-display/
│
├── cad/
│   ├── spotify_display_case.step
│   ├── spotify_display_case.stl
│
├── code/
│   ├── main.ino
│
│
└── README.md

cad/
Contains the 3D design files for the enclosure.

code/
Contains the example firmware used to connect to Spotify and drive the display.

3D Design

The enclosure was designed in CAD to hold the display and electronics in a compact housing.

Included files:

.STEP file for editable CAD use
.OBJ file for viewing

The design will initially be built out of cardboard as a prototype to test fit, layout, and usability before creating a more permanent version.

This allows quick iteration and changes without wasting materials.

Code

The code included in this repository is the example code from the Stasis Spotify Display starter project.

Source:
https://stasis.hackclub.com/starter-projects/spotify-display

The current goal is simply to confirm that:

The device connects to WiFi
Spotify authentication works
Song data can be retrieved and displayed

Once the basic functionality works, additional features will be added.

Planned Improvements

Future versions of this project include:

Album artwork display
Animated UI
Playback controls (play/pause/skip)
Better enclosure materials (3D print or laser cut)
Improved internal mounting for electronics
Prototype Strategy

Development will follow this process:

Build cardboard enclosure prototype
Test electronics and screen fit
Confirm Spotify API functionality
Iterate on CAD design
Build improved enclosure
Credits
Hack Club Stasis for the starter project and example code
Spotify Web API for music data
