# PMIC Measurements

This plug-in makes measurements for validation of Power Management ICs. The tests will generate a source voltage signal and then measure the load voltage/current/efficiency/transient response of the load.

## Key Features

    Line Regulation

    Efficiency/Load Regulation

    Output Voltage Accuracy

    Ripple

    Line Transient Response

    Load Transient Response

## Hardware Setup
 ![image](https://github.com/NI-MeasurementLink-Plug-Ins/pmic-labview/assets/158544163/250de597-a185-4c6a-935b-940b35df2d0a)


Instrumentation:

    DC Electronic Load (NI 4051)

    Programmable Power Supply (NI 4151)

    AUX Power Supply (APS 4158)

    Waveform Generator (NI 5433)

    Oscilloscope (NI 5162)

    Controller (NI 8881)

    Chassis (NI 1092)

    Digital Pattern Instrument (NI 6571)

    DUT (DC1811B-B)

    Line Injector (J2120A)




## Software Installation

Install from NI Package Manager:

      InstrumentStudio (2023 Q4 or higher)
      
      MeasurementLink (2023 Q4 or higher)
      
      TestStand (2022 Q4 or higher)
      
      LabVIEW (2021 SP1 or higher)
      
      SDC (2023 Q4 or higher - to communicate with DUT)
      
      NI DMM (21.3 or higher - required for gain and offset)
      
      NI DCPower (2023 Q4 or higher - support Argus hardware - 4051/52)
      
      NI Fgen (21.8 or higher - needed for channel to channel isolation)



