# PMIC Measurements

This plug-in makes measurements for validation of Power Management ICs. The tests will generate a source voltage signal and then measure the load voltage/current/efficiency/transient response of the load.

## Key Features

    Line Regulation

    Efficiency/Load Regulation

    Output Voltage Accuracy

    Line Transient Response

    Load Transient Response

## Hardware Setup


Instrumentation:

  Programmable Power Supply (NI 415x)
  
  E-Load (NI 405x)
  
  PMIC DUT


Tested hardware setup:

  NI 4151 PPS
  
  NI 4051 E-Load
  
  LTM4676A DUT 


## Software Installation

Install from NI Package Manager:

  InstrumentStudio 
  
  MeasurementLink 
  
  TestStand
  
  LabVIEW
  
  SDC (to communicate with DUT)
  
  NI DMM (required for gain and offset)
  
  NI DCPower (Support Argus hardware - 4051/52)
  
  NI Fgen (needed for channel to channel isolation)



