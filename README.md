# KicadBiquadFilter
Manually variable stereo filter (BP, HP, LP) in two sections

## Status - Rev A Produced Both sections operational
### Errata
 * Section 2 feedback OpAmp incorrect - has to be bypassed
 * Footprint of Op Amp little too small for the packages in stock
 
### Issues and Notes
Issues

Wishlist for Rev B 
 - should handle connectors and Potmeters on the PCB
 - Potmeters should have optional resistor in series and parallel
 - Focus on Eurorack compatibility
 - Mono filter 
 - VCF option

## Physical Construction
 - 100x100mm
 - Several resistors has been selected as THT components so a Potmeter can be placed instead
 
The board is split in two, joined at the center of the board. Each section is a stereo section that can operate individually.
### Section 1 - State Variable filter and buffer amp
![](Filter_Section1Sch.png)
### Section 2 - State Variable filter and regulator


## Vital Components
 - Op Amp is chosen as MC33078 but can be selected as long as its pin compatible like (ua833, TL062, TL072, TL082, etc)
 
## Features
The state variable filter can be configured in different ways and needs to be calculated before the components are selected.

https://www.electronics-tutorials.ws/filter/state-variable-filter.html
