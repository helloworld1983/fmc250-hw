 FMC ADC 250M 16B 4CHA

## Project description

This project concerns the development of an ADC card in FMC (VITA 57)
format. The first intended application is the sampling RF signals in BPM
applications, as specified in the [BPM
project](https://www.ohwr.org/project/bpm/wiki).

-----

 ![Top view](https://www.ohwr.org/project/fmc-adc-250m-16b-4cha/uploads/25af84f1d877e8a2e4263fc4c03daa6a/250M_top.jpg)
*FMC ADC 250M 16B 4CHA production board**



-----

## Functional Specifications

  - VITA 57.1-2010 compliance
  - Four Channel 16 bit 250 MSPS ADC. Required ADC: ISLA216P25
  - Internal ADC clock circuit: phase locked to reference clock input
    with fine  
    frequency tuning capability. See specific section. Hold mode in case
    of loss of  
    external reference is a desirable feature.
  - Internal high frequency PLL oscillator output with amplitude control
    and locked  
    to external reference.
  - Reference clock can be sourced from front panel or from FMC pins
    CLK2\_BIDIR  
    and CLK3\_BIDIR
  - The FMC pin CLK\_DIR shall be connected to 3P3V via a 10KΩ pull up
    resistor to  
    indicate CLK2\_BIDIR and CLK3\_BIDIR are driven from the carrier to
    the FMC  
    mezzanine.
  - External ADC clock input (50 MHz up to 250 MHz, 0 dBm typ.)1
  - External reference clock input: (0.5 MHz - 20 MHz digital signal, 0
    dBm typ.)2
  - External digital trigger input

-----

## Detailed Project Information

  - Documentation:
      - Schematics
        ([PDF](https://www.ohwr.org/project/fmc-adc-250m-16b-4cha/blob/master/fmc-adc-250m-16b-4cha/SCH_FMC_ADC_250M_16B_4ch.pdf),
        [Altium
        sources](https://www.ohwr.org/project/fmc-adc-250m-16b-4cha/tree/master/fmc-adc-250m-16b-4cha/Schematics))
      - PCB
        ([PDF](https://www.ohwr.org/project/fmc-adc-250m-16b-4cha/blob/master/fmc-adc-250m-16b-4cha/PCB_FMC_ADC_250M_16B_4ch.pdf),
        [Altium
        sources](https://www.ohwr.org/project/fmc-adc-250m-16b-4cha/blob/master/fmc-adc-250m-16b-4cha/FMC_ADC_250M_16B_4ch_pcb.PcbDoc))

<!-- end list -->

  - [Block
    diagram](https://www.ohwr.org/project/fmc-adc-250m-16b-4cha/uploads/cf81ca76566ecf84ca79289acfed6a32/FMC_ADC.png)
  - [Users](Users)

-----

## Contacts

### commercial producers

  - [Creotech](http://creotech.pl/product-scientific/fmc-adc-250m-16b-4cha),
    Poland

### General question about project

  - [Filip Świtakowski](mailto:filip.switakowski@creotech.pl)

-----

## Status

|**Date**|**Event**|
|----|----|
|01-09-2012|Start working on project|
|01-10-2012|First version of schematics and PCB component placement|
|17-11-2012|Schematic review|
|19-11-2012|Schematic bugs fixed, final component placement, added heatsink anad start of PCB routing|
|23-11-2012|Board 100% routed. Heat sink design sent to the mechanical workshop for verification.|
|18-02-2013|Boards delivered, still waiting for heat sinks and panels|
|20-05-2013|Boards fully tested and working. Small issues with S11 caused by baluns and 2V5 supply that is not sufficient for LDOs. With 3V3 works fine|
|30-09-2014|v1.1 tested & working|


-----

Filip Świtakowski 04 Feb 2014