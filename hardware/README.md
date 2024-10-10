# HARDWARE

This folder contains all the PCB design files and 3D models for the Sitina project.

## File List

* `auxiliary/` - Auxiliary PCB design files used for production testing, validation, and other purposes.
  * `jtag_adapter/` - A small JTAG adapter for connecting the IO board to a JTAG programmer.
  * `Resonant_V_validation/` - A separate board for testing the resonant V driver used in r0.11
  * `SR_V_validation/` - A separate board for testing the controlled slew-rate & dead-time V driver in r0.9
* `enclosure/` - 3D models for the enclosure in SolidWorks format.
* `gripflex/` - grip handle flexible PCB design files.
* `gripflex-lh/` - Left handed version
* `ioboard/` - IO board (power supply, routing, house keeping MCU, etc) PCB design files.
* `ioboard-lh/` - Left handed version
* `sensorboard/` - Latest Sensor board (CCD Sensor, AFE, H/V Driver, Controller) PCB design files
* `sensorboard-backport/` - Sensor board PCB design files. This version is a back port of r0.11 to r0.9. Uses the old H/V Drivers
* `pcb_common/` - Symbol and footprint libraries. This is a submodule link to: [pcb_common](https://gitlab.com/zephray/pcb_common)