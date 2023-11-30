# Congenial-Fortnight
A low cost ARM based embedded DAQ for prototype use

# Vision
- Create a piece of hardware able to interface with varies sensors to facilitate prototyping or system identification. Examples: voltage and current sensing, digital in- and outputs, RS232 and RS485 communication.
- Create a piece of software which runs on a host PC to connect to the hardware mentioned above. This software is able to extract data in (semi) realtime and export it to a .csv file for further analyses.

# Technology used to create said vision
- ASAM MCD-1 XCP, a standard used by the automotive industry to tune/debug ECU (electronic control unit) in real time. Via this protocol the ARM controller can be programmed and debuged in realtime with minimal overhead to the ARM controller.
- .NET for creating the userinterface running on the host PC.
- KiCAD for developing custom electronics (PCBA).
