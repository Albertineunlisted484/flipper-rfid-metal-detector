# Flipper Zero RFID Metal Detector

A Flipper Zero application that repurposes the 125kHz RFID antenna to act as a makeshift metal detector. 

## Features
- **Visual & Audio Feedback**: Screen bar graph, increasing pitch, vibration, and LED alerts when metal is near.
- **Adjustable Sensitivity**: Tune out environmental noise or adjust for specific uses (like scanning a human) with the Left/Right buttons.
- **Multiple Modes**: Toggle Sound/Vibro modes with the OK button.

## Installation

The easiest way to install is to download the pre-compiled `.fap` file from the Releases page and drop it directly onto your Flipper's SD card in the `apps/Tools/` folder.

### Build from Source
1. Clone this repository into your Flipper firmware (`applications_user/rfid_metal_detector`) or an empty directory for `ufbt`.
2. Compile with `ufbt` or `./fbt fap_rfid_metal_detector`.
3. Transfer the compiled `.fap` to your Flipper's `apps/Tools/` folder.

## Credits & License
Created by AI (with Tommy's assistance).
Licensed under the MIT License.
