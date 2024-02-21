# icestick_spinalHDL_pwmAudio_V2
Home of the AudioChip V2. Made for an Lattice IceStick FPGA, adaptable for ASIC microchips.

### Create Verilog from spinalHDL
```
cd spinalHDL
sbt "runMain PWMaudioMain"
cd ..
```
### Copy Verilog over into the icestick folder
```
cp spinalHDL/PWMaudio.v icestick/
```

### Create bitstream from Verilog and flash to icestick
```
cd icestick
make prog
```

### Description of the AudioChip V2
Inputs:

Outputs:

Function:

