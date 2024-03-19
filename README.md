# PMIC Measurements

This plug-in makes measurements for validation of Power Management ICs. The tests will generate a source voltage signal and then measure the load voltage/current/efficiency/transient response of the load.

## Key Features

Line Regulation

Load and Efficiency Regulation

Load Tranient Response

## Hardware Setup
![image](https://github.com/NI-MeasurementLink-Plug-Ins/pmic-labview/assets/158544163/6f1ab57c-2912-42d0-97e2-9bbacf02ec51)

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

InstrumentStudio (2024 Q1 or greater)

MeasurementLink (2024 Q1 or greater)

TestStand

LabVIEW

SDC (to communicate with DUT)

NI DMM (required for gain and offset)

NI DCPower (Support Argus hardware - 4051/52)

NI Fgen (needed for channel to channel isolation)



