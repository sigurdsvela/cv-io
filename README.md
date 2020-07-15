*[CHC]: Channel Count
*[ACLK]: Audio Clock
*[BD]: Bit depth


## BOM

### DAC
The output is a demuxed buffered dac. The chip writes two the buffer, while the buffer continously writes the buffer to each of the outputs(S&H)
- Schmitt Trigger (2 rising, 2 falling)
- ACLK, Clock (44.1/48)
- Clock multiplier (*CHC)
- R-2R ladder, BD-bit
- CHC * S&H

#### Component Candidates

**R-2R**