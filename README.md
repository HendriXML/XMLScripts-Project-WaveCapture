# XMLScripts-Project-WaveCapture
Automated wave capture for Siglent SDS1104X-E and SDS1204X-E Mixed Signal Oscilloscopes. The captured traces are written in seperate XML files and can easily be imported in Excel.

The scripts are not intended for critical usage - always asume it can be buggy.

To get this repository with all its submodules the following command might be of use 

git clone --recurse-submodules https://github.com/HendriXML/XMLScripts-Project-WaveCapture.git C:\WaveCapture

What's needed to use this script?
* Siglent SDS1104X-E or SDS1204X-E - other Siglents could work with some modifications
* NI VISA setup (It uses a COM interface that comes with it)
* Ethernet/Wifi connection on Scope (Using the above with USB fails)
* Interpreter executable (64 bit Windows, developed by me)
* Script + Script libraries

## Capture traces.xml
Captures the scopes current acquisition.

## Capture averaged traces.xml
Captures the scopes current multisegment acquisition and averages the multiple cycles.
This can take a while when using a lot of segments or a lot of wavepoints.


