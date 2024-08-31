# Anycubic Card
## Home Asssistant card for Anycubic Printers (via the Anycubic Cloud integration)


## Features
---

- Live animation of 3D printer
- Live camera view
- Current states of various sensors
- Tap to show/hide when printer is idle
- Power button for a switch entity
- Light button for a switch entity
- Adjustable 3D printer graphic scale
- ACE Slot configuration via popup
- Print settings configuration via popup


## Installation
---
### Method 1: HACS
1. Open _HACS_ and navigate to _Frontend_ Section
2. Open the Overflow Menu (⋮) in the top right corner and click on _Custom repositories_
3. Paste `https://github.com/WaresWichall/hass-anycubic_card` into the input field and select `Dashboard` (or `Lovelace`) from the dropdown
4. Click the Install Button on the highlighted Card titled _Anycubic_

### Method 2: Manual

1. Download ```anycubic-card.js``` from the releases section.
2. Either:
  * Move to the ```www``` folder of your Home Assistant instance
  * Or copy the file's contents via the file editor.
3. In the Resources section of Dashboards (```Settings -> Dashboards -> ... Menu -> Resources```), add ```/local/anycubic-card.js``` as a ```JavaScript Module```.
4. Save
5. Add a manual card to your lovelace dashboard using the configuration instructions below.
6. Reload Browser

## Gallery
---

<img width="400" alt="" src="https://raw.githubusercontent.com/WaresWichall/hass-anycubic_card/master/screenshots/card-main.png">
<img width="400" alt="" src="https://raw.githubusercontent.com/WaresWichall/hass-anycubic_card/master/screenshots/card-printsettings.png">
<img width="400" alt="" src="https://raw.githubusercontent.com/WaresWichall/hass-anycubic_card/master/screenshots/card-dryingoptions.png">
<img width="400" alt="" src="https://raw.githubusercontent.com/WaresWichall/hass-anycubic_card/master/screenshots/card-slotoptions.png">
<img width="400" alt="" src="https://raw.githubusercontent.com/WaresWichall/hass-anycubic_card/master/screenshots/card-materialoptions.png">

## Where's the source?

[Source code here](https://github.com/WaresWichall/hass-anycubic_cloud/tree/master/custom_components/anycubic_cloud/frontend_panel)

This card is compiled from the same repository as the main Anycubic Cloud integration due to shared code with the panel.

## Issues

[Create issues and feature requests here](https://github.com/WaresWichall/hass-anycubic_cloud/issues)

