I wanted to use my DJI Mavic 2 Air controller with simulators but it wasn't supported.

The script reads serially from the controller and emulates as an xbox controller

### Prerequisites

- Python 3.x
- vgamepad library (`pip install vgamepad`)
- serial library (`pip install pyserial`)


### Usage

1. Connect your serial device to the computer.
2. Open the script and change the `controller_port` variable to match the COM port of your connected controller.
3. Run the script.

- ### Works with controllers of:
- DJI Mavic Air 2
- DJI Mavic Air 2S
- DJI Mini 2
