# XMLScripts-Project-WaveCapture
Automated wave capture for Siglent SDS1104X-E and SDS1204X-E Mixed Signal Oscilloscopes

To get this repository with all its submodules the following command might be of use 

git clone --recurse-submodules https://github.com/HendriXML/XMLScripts-Project-WaveCapture.git C:\WaveCapture

What's needed to use this script?
* Siglent SDS1104X-E or SDS1204X-E - other Siglents could work with some modifications
* NI VISA setup (It uses a COM interface that comes with it)
* Ethernet/Wifi connection on Scope (Using the above with USB fails)
* Interpreter executable (64 bit Windows, developed by me)
* Script + Script libraries
* XML editor to alter some values (for example an offset to get the first batch in view, scopes ip-adress). I really like the free Visual Studio Community for that.
