*** PLEASE NOTE, this software is no longer compatible with the Dirtywave M8 if you are running past Firmware ~3.1 (there was an overhaul with how the display is recreated in the vanilla TouchDesigner M8 Display when Trash80 introduced Big Fonts). At this stage there are new alternatives showing up though - check the discord :)

# M8 Display + simple visual features

See video overview for info: https://youtu.be/FMR5dIHkMnY

Built on top of the original .toe file provided by Dirtywave (0183dcf / Dec 24, 2021). Two additional files in the 'M8DisplayTouchdesigner' folder: 

### M8Display_GleixViz.toe - Adds a few additional UI elements for controlling: 

- Full view // Full device is shown, buttons light up when pressed
- Audio // Settings for routing audio from the M8 via USB
- RGB Sliders // Controls color of the buttons & some visual scenes
- RGBA Sliders // Control the color & transparency of the background (for use with spout output / OBS)
- Particles // Particles emit from buttons when pressed
- CRT TV emulation
- 8 preset visual scenes, some of which are color controllable, one of which accepts MIDI sync & transport
- Touchscreen/mouse support (click on buttons of the m8 in full view)
- Poorly (re: not) optimized, may not run well on some systems 

### M8Display_GleixViz_LightweightKeypressOverlay.toe - Lightweight, no visuals, meant for use as an overlay 

- RGB(a) Sliders // Control button color, background color & alpha (keying or output via syphon spout)
- Audio // Settings for routing audio from the M8 via USB
- Touchscreen/mouse support (click on buttons of the m8 in full view)
- Particles // Same as above. Particle container isn't cooking when not in use and shouldn't take up any resources. 
- Syphon Spout still functional, great for using as a source directly into OBS (may need to install Spout plugin for OBS - https://offworld.live/spout-plugin-for-obs-studio)
- 

Installation & connection instructions same as original below.

# M8DisplayTouchdesigner
M8 virtual display for Mac and Windows utilizing Derivative Touchdesigner

## System Requirements
Modern Mac or PC - See https://docs.derivative.ca/System_Requirements

## Instructions
1. Install Derivative Touchdesigner - https://derivative.ca/download
2. Update M8 firmware to 1.0.3 or above.
3. Download or clone this repo. Unzip the contents and keep the "Assets" folder as a sub directory form the project file.
4. Connect M8 to host computer via USB and launch "M8DisplayTouchdesigner.toe"
5. Select Serial port by clicking the arrow to the right of the "port" field. Click the "Connect" button.
