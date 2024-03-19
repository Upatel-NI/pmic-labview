# PMIC Measurements

This plug-in makes measurements for validation of Power Management ICs. The tests will generate a source voltage signal and then measure the load voltage/current/efficiency/transient response of the load.

## Key Features

Line Regulation

Load and Efficiency Regulation

Load Tranient Response

## Hardware Setup

Instrumentation:

Programmable Power Supply (NI 415x)
NI 4051

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


