# Lab5-05: Downlink Picture Data

Lab5 repository for downlinking HK telemetry, accelerometer data, and JPEG images with the HEPTA-SAT kit.

## Web Serial Monitor

Connect your HEPTA-SAT via USB after flashing the firmware, then open the URL below in **Chrome or Edge**.

**https://hepta-sat-training.github.io/HEPTA-SAT-Serial_Monitor/**

1. **Add Port** → select your COM port
2. Leave baud rate at **38400**, then click **Connect**
3. Confirm HK telemetry in the output pane
4. Type `a` for accelerometer data or `p` for a JPEG image (shown in a modal)

## Firmware

Open `Lab5-05_Downlink_Picture_Data.ino` in the Arduino IDE and upload it to your board. For library and submodule setup, see [src/README.md](src/README.md).
