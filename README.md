# icestick_spinalHDL_pwmAudio_V2
Home of the AudioChip V2. Made for an Lattice IceStick FPGA, adaptable for ASIC microchips.

### Create Verilog from spinalHDL
```
cd spinalHDL
sbt "runMain MyImplementation"
cd ..
```
### Copy Verilog over into the icestick folder
```
cp spinalHDL/MyImplementation.v icestick/
```

### Create bitstream from Verilog and flash to icestick
```
cd icestick
make prog
```

### What this example does
Pin PMOD1 is an input. 
Pin LED D1 (99) is an output.
Input and output gets connected via an inverter.  
